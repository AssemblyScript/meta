![AssemblyScript Logo](https://avatars1.githubusercontent.com/u/28916798?s=64) AssemblyScript Working Group
=================

The Working Group repository contains discussions, goals, roadmaps, assets, etc. directly related to AssemblyScript development or project organization.

**Related**

* [AssemblyScript Compiler](https://github.com/AssemblyScript/assemblyscript)
* [AssemblyScript Community Group](https://github.com/AssemblyScript/community-group)

**Contents**

* [Goals](#goals)
* [Governance](#governance)
  * [Technical Decisions](#technical-decisions)
  * [Organizational Decisions](#organizational-decisions)
* [Groups](#groups)
  * [Working Group](#working-group)
  * [Community Group](#community-group)
* [Teams](#teams)
  * [Compiler](#compiler)
  * [Advocate](#advocate)
  * [Developer Experience](#developer-experience)
* [Getting Involved](#getting-involved)

# Goals

The goals of the Working Group are:

* Target feature parity with WebAssembly and related technology.
* Support non-browser use cases well (i.e. serverless, blockchain, etc...).
* Stay backwards-compatible to TypeScript syntax and JavaScript APIs as much as possible and reasonable.
* Complement current web projects, and support building WebAssembly modules "from scratch". By offering "fine-grain" control to developers.
* Focus on developer experience, and try to be a great language for new and existing web developers. 

# Governance

Following the [definitions described in opensource.guide](https://opensource.guide/leadership-and-governance/#what-are-some-of-the-common-governance-structures-for-open-source-projects), governance is split into two parts:

## Technical Decisions

Technical Decisions can be interpreted as contributions being made to projects in the AssemblyScript Github Organization.

For this, we will be following BDFL. Daniel Wirtz ([@dcodeIO](https://github.com/dcodeIO)) is the designated project lead. Thus, in the case there is conflict between contributors, the lead will be the one to make the final decision.

## Organizational Decisions

Organizational decisions can be interpreted as contributions to the general project direction, goals, roadmap, maintainers, etc...

For this, we will be following a meritocracy. Where consensus will be requested on issues opened on this repo to get a community vote, and can find a path going forward.

# Groups

The AssemblyScript Project has meetings and correspondance divided into groups. These groups communicate and work together very closely, and the meetings provide interested parties a way for focused discussions.

## Working Group

The Working Group is for those who would like to contribute to the project directly. Whether that be through getting advice on technical implementations, proposing a specific change or addition, or just generally talking about the AssemblyScript project and where it is headed.

## Community Group

The [Community Group](https://github.com/AssemblyScript/community-group) is for those who would like to discuss with other community members (including members of the Working Group) using AssemblyScript in their applications. Its goal is to communicate core feature requests and use cases to aid in prioritizing the working group's efforts, which can help reduce duplicating efforts amongst the community, and allow the community to be collectively more productive!

# Teams

The Working Group is divided into teams. The teams make design, architectural, and organizational decisions for their relevant domains and repositories by consensus. If consensus can't be made, then the project lead may act as a tie-breaker.

**Membership guidelines**:

* Anyone who is making significant contributions to the project (whether it be code, documentation, outreach, etc...) in the domains associated with the Working Group is welcome to request to join a team!
* Membership does not require any required responsibilities outside of general activity in the respective domain. The project is open source and contributions are made at one's own accord. So help when you can. If things get busy on a member's end, that is okay! We welcome back all awesome contributors after a haitus.
* All members of a team must adhere to the [Code of Conduct](./CODE_OF_CONDUCT.md).
* Membership does not imply commit access to a repository. Commit access should be handled by the maintainer of the repository, or by consensus of the respective team.

## Compiler

The Compiler team works directly on the AssemblyScript compiler, its standard library or provided tools, mostly under the [AssemblyScript/assemblyscript](https://github.com/AssemblyScript/assemblyscript) repository.

* **Daniel Wirtz** ([@dcodeIO](https://github.com/dcodeIO)) - Author of AssemblyScript
* **Max Graey** ([@MaxGraey](https://github.com/MaxGraey)) - Author of large parts of the Standard Library
* **Joshua Tenner** ([@jtenner](https://github.com/jtenner)) - Regular Contributor
* **Bowen Wang** ([@bowenwang1996](https://github.com/bowenwang1996)) - Regular Contributor, [NEAR](https://nearprotocol.com/)
* **Duncan Uszkay** ([@DuncanUszkay1](https://github.com/DuncanUszkay1)) - Regular Contributor, [Shopify](https://www.shopify.com/)
* **Aaron Turner** ([@torch2424](https://github.com/torch2424)) - Regular Contributor, [Fastly](https://www.fastly.com/)

## Advocate

The Advocate team works on projects, demos, talks, giving feedback on "messaging" about the project, and writing articles to help grow popularity and improve outreach.

* **Aaron Turner** ([@torch2424](https://github.com/torch2424)) - [Speaker](https://youtu.be/ZlL1nduatZQ)
* **Joshua Tenner** ([@jtenner](https://github.com/jtenner)) - [Speaker](https://dev.to/jtenner/an-assemblyscript-primer-for-typescript-developers-lf1)
* **Willem Wyndham** ([@willemneal](https://github.com/willemneal)) - [Teacher](http://www.cs.umd.edu/class/spring2019/cmsc388I/assemblyscript.html)

## Developer Experience

The Developer Experience team works on projects such as tools, or anything that helps people be productive with AssemblyScript.

* **Aaron Turner** ([@torch2424](https://github.com/torch2424)) - Author of [Wasm By Example](https://github.com/torch2424/wasm-by-example) and [as-bind](https://github.com/torch2424/as-bind)
* **Joshua Tenner** ([@jtenner](https://github.com/jtenner)) - Author of [as-pect](https://github.com/jtenner/as-pect) and [as2d](https://github.com/as2d/as2d)
* **Willem Wyndham** ([@willemneal](https://github.com/willemneal)) - Developer Experience at [NEAR](https://nearprotocol.com)
* **Bowen Wang** ([@bowenwang1996](https://github.com/bowenwang1996)) - Developer Experience at [NEAR](https://nearprotocol.com)

# Getting Involved

We're happy to help you get involved! Currently, there are a few things you could do to start getting involved with the Working Group:

* Reach out to a team member, and get invited to the AssemblyScript Slack.
* Join one of our [upcoming public meetings](https://github.com/AssemblyScript/working-group/issues?q=is%3Aissue+is%3Aopen+public+meeting).
* Open an issue on the [working-group repository](https://github.com/AssemblyScript/working-group/issues), or any of the [AssemblyScript repositories](https://github.com/AssemblyScript).
