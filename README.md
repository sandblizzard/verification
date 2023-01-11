# Profile verification

In order to automatically reward users when they make a contribution or credit accounts when bounties are created we need to link profile and wallet address.

We will maintain a list of user profiles and wallet addresses.

## Add yourself

Make a pull request into the repo with your wallet address and write your address in the PR comment like

```
solanaAddress: ""
```

Please see the `profile.list.json` for format

## How it works

The user signs the PR using the local key. We index the PRs and link the signed PR and the wallet address(es) in the PR. This is then stored on chain and used when users wants to reward or be awarded.

# User flow

TBD
