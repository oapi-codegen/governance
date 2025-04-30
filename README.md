# Governance for `oapi-codegen` and its associated projects

This repository maintains the documentation around the governance of the [`oapi-codegen`](https://github.com/oapi-codegen/oapi-codegen) project, as well as its related projects, all found under the [oapi-codegen GitHub org](https://github.com/oapi-codegen/oapi-codegen).

> [!IMPORTANT]
> This documentation intends to cover _the current state_ of how [`oapi-codegen`](https://github.com/oapi-codegen/oapi-codegen) is being maintained.
>
> Over time, this will evolve.

## Contributor types

There are a number of key contributor types to `oapi-codegen`.

### User

#### Requirements

To be a user of `oapi-codegen`, you will use `oapi-codegen`.

#### Responsibilities and privileges

- Users use `oapi-codegen`
- Users raise Issues/Discussions for bugs or feature enhancements

### Contributor

A Contributor is someone who materially contributes to `oapi-codegen`, through providing support to others, documentation improvements, bug fixes, feature development, or otherwise.

#### Requirements

- To move from a User to a Contributor, you need to contribute to the project

#### Responsibilities and privileges

- Contributors may help provide support to others in the issue tracker
- Contributors may create Pull Requests to resolve bugs or feature enhancements

### Maintainer

> [!WARNING]
> There is currently no intermediate between a Contributor and a Core Maintainer.

### Core Maintainer

A Core Maintainer is someone who has strong competence in their understanding of `oapi-codegen`, and is given rights to make decisions around the future of the project and how the roadmap should be shaped.

They are knowledgeable around large parts of the codebase, and work to balance user both reviewing + merging user contributions, and making large changes to progress the project.

#### Requirements

> [!WARNING]
> There is no current contributor ladder

#### Responsibilities and privileges

- Core Maintainers are part of the [`@oapi-codegen/maintainers` team](https://github.com/orgs/oapi-codegen/teams/maintainers)
- Core Maintainers have `Admin` access across all repositories in the Org
- Only Core Maintainers can review a PR
- Only Core Maintainers can merge PRs
- Core Maintainers will make key product decisions around prioritisation of features and bug fixes, and deciding when to create a new release
- Only Core Maintainers can create a new release of `oapi-codegen` or a library in the ecosystem
- Core Maintainers will have `Owner` access on the GitHub organisation
- Core Maintainers will retain `Owner` access in perpetuity

## Sponsorship

To make the development of `oapi-codegen` [more sustainable over time](https://github.com/oapi-codegen/oapi-codegen/discussions/1606), it is possible to pay one of the Core Maintainers for an hour of time a month, and any additional sponsorship over that time is still likely to result in only one hour of work, but is appreciated!

To be clear, this is **not** "pay-to-play". The work being performed during this sponsored time is not negotiated or influenced up-front, and can be used at the discretion of the Core Maintainer.

This model allows the Core Maintainer to spend more time intentionally working on the project, allocating a number of hours explicitly per month towards it.

There are options to pay for "bug/feature bounties", in which a conversation with the Core Maintainer can be used to discuss how many hours of work the bug/feature should take to implement, and then can issue payment for it.
