# Support

Namazu Elements is free and open source software, published under the Mozilla Public License 2.0 by Namazu Studios LLC. Anyone can use it, ship with it, and get help with it.

This document explains how support works: what the community channels are, what you can expect from us, and what to do when you need more than best effort.

## Where to get help

All community support happens in public, in the GitHub repository for the component you are working with.

Elements spans several repositories (the core platform, the SDKs, the CLI, the documentation, and others). Please file against the repository the problem actually lives in. If you are not sure which one that is, file it wherever seems closest and we will move it. Filing in the wrong place is not a problem. Filing in five places at once is.

| I want to... | Go here |
| --- | --- |
| Ask a question about how something works | GitHub Discussions on the relevant repository |
| Report a bug or unexpected behavior | GitHub Issues on the relevant repository |
| Request a feature or an API change | GitHub Issues on the relevant repository |
| Ask something quick, or talk to other developers | Our public [Discord](https://discord.gg/NbWbshq6kf) |
| Report a security vulnerability | See [Security reports](#security-reports) below |
| Get help with a console platform | See [Console platforms](#console-platforms) below |
| Discuss commercial support or hosting | technology@namazustudios.com |

Please do not send support questions by direct message or private chat. We will politely redirect you to one of the channels above. This is not us being difficult: it is the only way a small team can support a growing project, and it means the next person with your problem finds the answer instead of asking again.

### About Discord

We are active in our public Discord and happy to talk there. It is the right place for quick questions, orientation, "am I thinking about this correctly," and conversation with other developers building on Elements.

It is not a substitute for filing an issue. Chat is not searchable in any useful way, it does not survive, and it does not turn into documentation. If a Discord conversation turns out to be a real bug or a real gap in the docs, we will ask you to open an issue so that the answer outlives the thread. The same best effort terms apply: a maintainer being online is not a commitment that a maintainer is available.

## What "best effort" means

Community support is provided on a best effort basis by the maintainers, in and around our other work.

**What we commit to:**

- We read every issue and discussion.
- We triage new issues in the order they arrive, typically within a few business days.
- We prioritize by impact on the project as a whole: correctness bugs, data loss, security, and regressions come first.
- When we resolve something that was not obvious, we fold the answer back into the documentation.

**What we do not commit to:**

- A guaranteed response time or resolution time.
- Weekend, holiday, or after-hours response.
- Debugging your application code, your infrastructure, or your deployment.
- Prioritizing your issue because it is blocking your release.
- Private or confidential handling of anything other than a security vulnerability.
- Support for console platforms, which is never public.

Best effort is genuine effort. It is not a service level agreement, and it should not be planned against for a launch. If you have a date that matters, see [Commercial support](#commercial-support).

## How to file an issue we can actually help with

The quality of an issue is the single biggest factor in how fast it gets resolved. In practice, well-formed issues get answered quickly and vague ones sit.

Please include:

1. **Version.** The Elements version, plus your JDK version and OS.
2. **What you expected to happen, and what actually happened.** Be specific.
3. **A minimal reproduction.** The smallest configuration or code path that shows the problem. This is the most valuable thing you can provide.
4. **Relevant logs and stack traces.** As text in a code block, not as screenshots.
5. **What you have already tried.**

Issues without a reproduction may be converted to Discussions until one is available.

### Anonymize your report

Everything you send us through the community channels is public, and it needs to stay that way.

**Do not send us confidential material.** We accept it in exactly two situations: under a paid support agreement, or as part of a security vulnerability report. Everywhere else we cannot take it. That includes game logic, proprietary schemas, unreleased content, player data, credentials, API keys, internal architecture documents, and anything covered by an NDA you hold with a third party. If you send us confidential material outside those two channels, we will delete it and ask you to refile publicly.

This is not squeamishness. Accepting confidential material creates handling obligations, and a company that has not signed an agreement with us has no assurance about how we handle it. Declining it is the honest position for both of us.

**Anonymize before you file.** A good sanitized report keeps everything we need and removes everything you cannot share:

- Replace real class, table, collection, and field names with generic ones.
- Reduce the problem to a minimal reproduction against a clean Elements install, not against your game.
- Scrub identifiers, hostnames, tokens, keys, and player data from logs and stack traces. Keep the frames and the exception, which is the part we need.
- Describe the API and the behavior, not the feature you are building.

If the problem genuinely cannot be reproduced without your proprietary code, that is a signal that you have crossed from open source support into consulting. We are glad to do that work under a support AddOn or a statement of work. See [Commercial support](#commercial-support).

Security vulnerabilities are handled privately and are exempt from this. See [Security reports](#security-reports).

## Console platforms

We cannot provide any public support for console platforms.

Console SDKs, toolchains, and platform documentation are covered by NDAs with the platform holders. Discussing them in a public issue, a public repository, or Discord would breach those agreements, for us and potentially for you. Please do not post console specific details, error messages, or SDK internals in any of our public channels. We will remove them.

How console support actually works:

- **Console support for Elements is distributed privately, as a separate extension.** It is not part of the public open source distribution and it is not available on GitHub.
- Access requires that you hold current developer status with the platform holder in question, verified through their program.
- Any discussion of platform specifics happens through **the platform holder's own approved support channels**, not through ours. That is where those conversations are permitted to occur, and it is usually where the authoritative answer lives anyway.
- Distribution of the extension itself is arranged under a commercial agreement. Contact **technology@namazustudios.com** to start that process.

If you are unsure whether something is console specific, treat it as if it is and ask us privately first.

## Security reports

Do not open a public issue for a security vulnerability.

Email **security@namazustudios.com** with a description of the issue and, if possible, a proof of concept. We will acknowledge receipt and coordinate a disclosure timeline with you. We credit reporters in the release notes unless you would rather we did not.

## Contributions

Patches are welcome and are the fastest path to a fix. See CONTRIBUTING.md for the development setup, coding standards, and the pull request process. A pull request with a failing test that demonstrates the bug is extremely helpful even if you cannot write the fix.

## Commercial support

If you need response times you can plan a release around, we sell support as an AddOn to **Namazu Cloud**, our managed hosting layer for Elements on AWS.

Support packages are listed in the **AddOns** section of your Namazu Cloud account. They provide what community support deliberately does not: a contracted response time, a private support channel, named engineers, and escalation for production incidents. This is the right choice if you have a launch date, live players, or an operations schedule that depends on getting an answer by a particular hour.

We also take on scoped professional services engagements (migrations, integrations, performance work, and custom feature development) under a separate statement of work. **Console platform extensions and any work requiring us to handle your confidential material fall into this category or under a support AddOn, never under community support.**

Contact **technology@namazustudios.com** to talk through which one fits, or browse the AddOns section directly at [namazustudios.com](https://namazustudios.com).

## A note on why it works this way

Elements is free because an open, widely used platform is good for our business and good for the studios building on it. Public support is the other half of that trade. Every question answered in the open becomes documentation, and the project gets better for everyone using it.

We would rather spend our time making the platform good than answering the same question privately ten times. Thank you for helping us do that.
