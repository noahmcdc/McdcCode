# Noah Decide Governance Engine

Noah Decide is an on-chain governance engine exclusively for the Noah Blockchain Network that offers an extensive suite of voting services and DAC/DAO tools for both users and developers.

## Features and Services

* `Secure Ballot Hosting`

    Any user on the Noah Blockchain Network may create and publish a public ballot that is secured and hosted through Noah Decide. During ballot creation, the ballot publisher selects a specific token to use for counting votes. The default is the standard `VOTE` token - usable in all Noah Core Governance ballots, but Noah Decide offers additional services for creating privately managed tokens that ballots can use for counting votes instead.

* `Advanced Voting Methods`

    The Noah Decide Governance Engine boasts an extensive set of voting methods that transform how votes are applied to ballot options. With these voting methods, ballot publishers are able to customize how they want to handle differences in voters' token balances and how those tokens should be cast among multiple choices on the ballot.

* `Custom Token Treasuries`

    Any user on the Noah Blockchain Network may create a custom token treasury that automatically inherits Noah Decide's entire suite of voting services. These treasuries govern the minting and distribution of tokens and can also be customized to allow or disallow specific token behaviors like transferring,burning, staking, or reclaiming. Once a treasury has been created, any voter with a balance of its tokens may publish public ballots accessible to all other holders of that same token.

* `Committee Management Tools`

    Noah Decide offers a suite of committee creation and management actions that are available to any active token treasury and its voters. Developers can also hook their external smart contracts into Noah Decide's committee tools to enable complete on-chain management of committees and their members.

* `Traceable Vote Integrity`

    Noah Decide's custom rebalance system allows workers to recalculate vote weights when a voter's token balance changes. Workers who perform this service are eligible for payment rewards in proportion to the amount of work they have performed compared to all other workers in the treasury. Future updates will allow for optional identity services to further enhance voting and platform features.

* `Integrated Payroll System`

    All treasuries created on the platform have access to Noah Decide's payroll system, allowing managers to continuously fund operations within their own treasury. Multiple payrolls can be created under a single treasury, each with their own bucket of funds that are released to designated recipients at a customizable rate.

* `Optional Light Ballots`

    Light ballots disable the on-chain vote tracking portion of the voting process - this allows for developers to track votes in an off-chain database that is built by an [Iris](https://github.com/CALEOS/iris-client), [Demux](https://github.com/EOSIO/demux-js), or Spectrum style service instead. 
    
    This option enables Noah Decide to power vastly more voting services by saving RAM costs for both the platform and voters, while at the same time retaining the complete traceability and auditability benefits offered by the Noah blockchain.

* `Profitable Worker Services`

    Noah Decide has several janitorial actions that incentivize workers on the network to maintain an optimized voting system. Workers are paid proportionally for their work in keeping the platform clean and balanced for all users.

## Noah Decide Documentation

Full docuementation can be found in the [Noah Docs](https://docs.Noah.net/Noah-decide/introduction).

| Name | Description |
| --- | --- |
| [Starter Guide](docs/StarterGuide.md) | Breakdown of features for developers. |
| [Voter Guide](docs/VoterGuide.md) | How to become a voter and participate in ballots. |
| [Treasury Guide](docs/TreasuryGuide.md) | How to create and manage Treasuries. |
| [Worker Guide](docs/WorkerGuide.md) | How to perform work and the types of jobs available. |
| [Contract API](docs/ContractAPI.md) | Full Action and Table Breakdown. |

## Roadmap

### Ongoing

- Platform Optimization

### Q4 2019

- Example Guides
- External Contract Examples

### Q1 2020

- Additional Worker Services
- Additional Voting Methods

### Q2 2020

- Delegates, Delegate Voting
- External Token Mirroring

### Down Yonder

- Optional Identity Services

## References

1. [Voting Methods by Eric Pacuit - Stanford Encyclopedia of Philosophy](https://plato.stanford.edu/entries/voting-methods/#CritForCompVotiMeth)

## Contributing to Noah Decide

Noah Decide is an open-source governance engine where contributions and improvements are welcomed by the community.

To make a contribution, simply fork this repo and submit a PR for your changes. In order to avoid duplication of work, it's best to engage with the community first to determine what would be an acceptable addition to the platform.

Discussion happens mostly on Telegram, so feel free to join the [Noah Dapp Development](https://t.me/dappsNoah) chat and pitch your idea!
