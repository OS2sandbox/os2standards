# Operational Governance


##### 🇩🇰 [Read in danish](../docs/governance_implementation_advice_en.md)

_[The OS2 governance model - (in danish)](https://www.os2.eu/governancemodellen) was originally written for a non-developer audience. In order to elaborate and make the outlined goals more operational, this guide is a series of implementation methods to quickly and easily get started on being compliant_

## Getting started
_How to get started with ensuring that your project is compatible with [The OS2 governance model - (in danish)](https://www.os2.eu/governancemodellen)_

- All source code and documentation for the project is placed in repositories under a GitHub organization owned by OS2.

- Development of new source code and documentation follows a [GitHub flow](https://docs.github.com/en/get-started/using-github/github-flow)

- Documentation that both describes use, but also how to quickly get started with developing and contributing, is placed in a documentation repository under the same organization, and automatically builds a searchable documentation site. A simple template for this can be found here: https://github.com/OS2offdig/OS2-docs-template

- Each repo has a team of maintainers, the team can be staffed by vendors or sufficiently trained developers/users.

- Each project has a project coordinator who keeps track of and shares issues and divides them into milestones on GitHub. The available project budget dictates how these roles are filled.

- The projects are built as reusable, well-documented services that communicate in and out via open standard protocols. Business logic, standard communication code and service orchestration are placed in self-explanatory modules together with documentation and deployment methods in code. In this way, the bar is lowered to develop an exit strategy and open up supplier collaborations. A PoC on a template for this is available here-> https://github.com/OS2sandkasse/dev-polyglot-microservices


- Container images of them are automatically built every time a pull request is approved and new, tested code is merged into the main branch.
A finished template for this is not available, but this PoC can serve as inspiration-> https://github.com/OS2sandkasse/dev-polyglot-microservices/blob/main/.github/workflows/build.yml