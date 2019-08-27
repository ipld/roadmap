**Welcome to the IPLD Roadmap!**

Please use GitHub issues to discuss anything you'd like to see added to the Roadmap or any 
questions you have about the current Roadmap.

# IPLD Roadmap

## IPLD Vision

Enable the Internet of Data.

The IPLD project vision is quite large, so there's a big disparity between what we are doing
**now** and what the project's intended scope is.

The teams spends most of its time in two categories of work: research engineering and dependency engineering.

Research engineering is code and spec writing for things that are not solidified yet and should rarely be used
or relied upon yet by others.

Dependency engineering is code and spec writing for things people *already* depend on, or will rely on very soon.

When planning and documenting our activity we try to distinguish between these two activities as best we can because the
process, timelines, and guarantees we can make about each category are very different.

The project is not currently spending much time on: external messaging, education, evangelism, or product development.
We do some of this work occasionally, but it's not our top priority at this moment.

## IPLD Priorities

1. IPLD must be a good dependency for other projects.
2. IPLD must strive to deliver on the vision of an "Internet of Data."

### Requirements

1. IPLD must provide primitives for building decentralized data-structures.
2. IPLD must provide data-structures for common applications.
3. IPLD must provide specifications for representing common types of data.
4. IPLD data-structures must easily replicate across peers.

## 2019 Top Level Targets

1. **Q1/Q2**
   - [x] Solidify primitives.
   - [x] Solidify core libraries.
3. **Q3** 
   - Mature schemas in order to provide codegen in Go.
   - Define "shippable" UnixFSv2.
   - Implement core Rust libraries w/ WASM compilation.
4. **Q4**
   - Implementation of UnixFSv2.

## OKR's

Quarter OKR's (Objective, Key Result) are in the [okr directory](./okrs).
