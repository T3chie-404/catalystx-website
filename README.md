# CatalystX Validator Website

Public website for CatalystX, a Solana validator and validator-backed infrastructure operator.

## Positioning

- SWQoS and staked QUIC forwarding for RPC operators
- Validator-sourced real-time shred delivery
- Introductions to already connected RPC and infrastructure providers
- Direct and pool-based Solana staking

The active validator is in Rotterdam, with standby sites in Frankfurt and Madrid. Operator-reported transition times are approximately 200 ms for planned failover and approximately 40 seconds for an unplanned emergency failover; these figures are not an SLA.

## Local development

Install Ruby and Bundler, then run:

```bash
bundle install
bundle exec jekyll serve --host 0.0.0.0
```

The generated site is written to `_site/`.

## Branch and deployment flow

- Pushes to `dev` run the Jekyll build check only.
- Pull requests targeting `main` run the same build check.
- Pushes to `main` build and deploy to the `gh-pages` branch.

The production domains are [catalystx.sol](https://catalystx.sol) and [catalystxsol.com](https://catalystxsol.com).

## Validator

- [StakeWiz profile](https://stakewiz.com/validator/ErvMUdtMC7AX55zKdYSyy4DnWNCrTsWn5GwprSG7ocnx)
- Vote account: `ErvMUdtMC7AX55zKdYSyy4DnWNCrTsWn5GwprSG7ocnx`
- Identity account: `BNtHBLo1L2vAG7PBQ6mJvWz7GqVPxBnioXsY2Gjtubrg`

Operated by [S3RDV LLC](https://s3rdv.com).
