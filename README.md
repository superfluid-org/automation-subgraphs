# Superfluid Automation Subgraphs &middot; ![License: MIT](https://img.shields.io/badge/License-MIT-green.svg) [![Twitter Follow](https://img.shields.io/twitter/follow/Superfluid_HQ?style=social)](https://twitter.com/Superfluid_HQ)

Superfluid Automation Subgraphs index the [peripheral Superfluid automation contracts](https://docs.superfluid.org/docs/category/automations): Vesting Scheduler, Flow Scheduler and Auto-Wrap.

## Endpoints
The endpoints are in the [@superfluid-finance/metadata](https://www.npmjs.com/package/@superfluid-finance/metadata) package. Each network entry that has them lists `subgraphVesting`, `subgraphFlowScheduler` and `subgraphAutoWrap`, each with a `hostedEndpoint`.

## Development
```sh
pnpm install
pnpm gen
pnpm build
pnpm test
```

The subgraphs are in `subgraphs/` (`vesting-scheduler`, `flow-scheduler`, `wrap-scheduler`). They are deployed with the GitHub Actions workflows in `.github/workflows/`.

## Automation Smart Contracts
- Inspect the source code in the [protocol-monorepo](https://github.com/superfluid-org/protocol-monorepo/tree/dev/packages/automation-contracts)
- Find the deployment addresses programmatically from [@superfluid-finance/metadata](https://github.com/superfluid-org/protocol-monorepo/tree/dev/packages/metadata)

## Other
The Graph Supported Networks CLI names: https://thegraph.com/docs/en/developing/supported-networks/

## License
The Superfluid Automation Subgraphs are [MIT licensed](./LICENSE).
