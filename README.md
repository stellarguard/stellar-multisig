# @stellarguard/multisig-utils

Utilities for working with Stellar mulitsig.

## Installation

```bash
npm install @stellarguard/multisig-utils --save
# or
yarn add @stellarguard/multisig-utils
```

## Usage

```js
import {
  needsMoreSignatures,
  getMultisigServerEndpoint
} from '@stellarguard/multisig-utils';

const moreSignatures = needsMoreSignatures(transaction, server);

if (moreSignatures) {
  const multisigEndpoint = await getMultisigServerEndpoint(
    moreSignatures[0].account
  );

  const result = submitToMultisigServer(transaction, multisigEndpoint);

  if (result.stellarGuard) {
    console.log(`Authorize your transaction at ${result.url}`);
  }
}
```

## Examples

See [src/example.ts](src/example.ts) for examples.

## Limitations

1. needsMoreSignatures currently only works with public key signers.
2. needsMoreSignatures does not correctly identify that an account needs more signatures if the transaction changes something (like adds more signers, creates new accounts and then uses them, changes thresholds) that would then require more signers for a later operation in the transaction.
