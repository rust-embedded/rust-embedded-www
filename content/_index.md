+++
+++
# Rust on Embedded Devices Working Group

We do Embedded Rust, defined broadly as Rust for resource-constrained environments and platforms where hardware-level work is critical. Our job is to work with the community to improve the embedded ecosystem, maintain and develop core crates used for Embedded Rust, and coordinate community communication.

We try to make Rust embedded development easier and better end-to-end, from targeting a piece of hardware to providing higher-level APIs and application solutions. Embedded tooling and documentation are critical here, so we work on that as well.

We are an [official working group][gov] of the Rust language.

## Check out what's going on!

- The [Embedded Rust Showcase][showcase] is a place to check out some of the amazing successes of embedded Rustaceans. The projects there demonstrate some of the best that Embedded Rust has to offer.
- Join our ongoing discussion on Matrix <[#rust-embedded:matrix.org][chat]>! We have a weekly open meeting there every Tuesday 2000 (8PM) CET (Berlin Time) — folks are welcome to come see what we are up to.
- Our meeting [agenda/minutes][agenda] is a series of Github Discussions pages documenting what we are doing. It's a great place to nominate an existing Github Issue or PR, or any other topic that you think would benefit from a synchronous discussion.
- Our curated list of [Awesome Embedded Rust][aer] resources is a grab-bag of great stuff.
- Our [REWG coordination repository][wg] is the place to go for "official" information: REWG structure and leadership, RFCs, meeting minutes, etc.

## Learn Some Embedded Rust!

- The [MB2 Discovery Book][discovery] is a complete walkthrough of Rust development for Embedded Rust beginners, targeted to a platform and filled with examples.
- The [Embedded Rust Book][book] is our entry point for developers experienced in Rust and embedded.
- The [Embedonomicon][embedonomicon] covers important "under the hood" topics for advanced Embedded Rust. An appendix provides instructions to vendors wishing to bring their targets into the Embedded Rust ecosystem.
- We have an entire ["bookshelf"](@/bookshelf.md) of embedded Rust documents. Some are a bit out of date, but we encourage you to check there for other things you might want to know.


## Want to help?

Everyone can contribute to the Rust Embedded WG efforts! There are several ways to help out:

- We offer a Github repo where you can file [REWG Issues][wg-issues]: let us know where the gaps are! If you think the language, the compiler, the tooling, the documentation or the crate ecosystem is lacking some feature, information or library to build embedded software, let us know. We'll bring it up to the Rust teams or help organize the community to build crates or tools to fill gaps.
- We encourage you to participate in our [RFC (Request For Comments)][rfc] process. We are always looking into ways to improve. This may involve things like changing how we run the WG or making major breaking changes in core crates. To ensure we are *actually* making things better we need your input! That's why all these changes are preceded by an "RFC", a discussion thread (which may or may not be backed by a proper RFC document) where we evaluate the pros and cons of a proposal and explore alternatives. Only after there's consensus on accepting the proposal is the proposal made effective.
- There's always a pile of [help-wanted issues][open-issues], but the WG members only have so much free time. You can help us fixing bugs, implementing features, writing tests, trying out examples and tutorials, writing documentation, fixing typos, etc. We can often mentor you through these tasks and review your work. In some cases you may not even need previous embedded experience or access to embedded hardware to help us out so don't let that discourage you from checking out our help-wanted issues.
- We have several teams focused on different areas: tooling, Cortex-M crates, etc. Each team maintains several projects (crates, docs and / or tools) that live under the REWG Github organization. You can help with these projects informally. You may subsequently be invited to join a team.

## Our Vision

- To improve the absolute quality (functionality, safety, performance) of embedded software in the wild.
- To improve the productivity of embedded software development teams, by reducing the tangible and intangible costs of achieving a level of quality.
- To improve the experience for programmers developing for embedded systems.
- To make embedded systems programming more accessible for people that are not already embedded systems developers.

[aer]: https://github.com/rust-embedded/awesome-embedded-rust
[agenda]: https://github.com/rust-embedded/wg/discussions
[blog]: https://blog.rust-embedded.org/
[book]: https://docs.rust-embedded.org/book
[chat]: https://matrix.to/#/#rust-embedded:matrix.org
[discovery]: https://docs.rust-embedded.org/discovery-mb2/
[embedonomicon]: https://docs.rust-embedded.org/embedonomicon/
[gov]: https://rust-lang.org/governance/teams/launching-pad/#team-wg-embedded
[joining]: https://github.com/rust-embedded/wg/blob/master/rfcs/0136-teams.md#adding-new-members
[newsletter]: https://rust-embedded.github.io/blog/
[open-issues]: https://github.com/search?q=org%3Arust-embedded+is%3Aopen+label%3A%22help+wanted%22&type=Issues
[rfc]: https://github.com/search?q=org%3Arust-embedded+is%3Aopen+label%3Arfc&type=Issues
[showcase]: https://showcase.rust-embedded.org/
[wg]: https://github.com/rust-embedded/wg
[wg-issues]: https://github.com/rust-embedded/wg/issues
