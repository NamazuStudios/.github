# Security Policy

This policy applies to all software published by Namazu Studios LLC, including Namazu Elements, its SDKs and tooling, and the Namazu Cloud managed service.

We take security reports seriously and we would rather hear about a problem early and awkwardly than late and publicly. Thank you for taking the time.

## Reporting a vulnerability

**Email security@namazustudios.com.**

Do not open a public GitHub issue, post in Discord, or discuss the issue publicly until we have had a chance to address it. Public disclosure before a fix exists puts the studios and players running Elements at risk.

If you would prefer to use GitHub, you can also report privately through the **Security** tab of the affected repository (Report a vulnerability). Both routes reach the same people.

### What to include

The more of this you can provide, the faster we can act:

1. **A description of the vulnerability** and the impact you believe it has.
2. **The affected component and version.** Which repository, which release or commit.
3. **Steps to reproduce**, or a proof of concept. This is the single most useful thing in a report.
4. **Your assessment of severity**, if you have one, and any CVSS vector you have calculated.
5. **Whether the issue is already public** anywhere, and whether you intend to publish.
6. **How you would like to be credited**, or that you would prefer not to be.

Please report in English if you can. Encrypted reports are welcome: ask us for a key at the address above and we will provide one.

Send us whatever you need to in order to demonstrate the issue. Unlike our general support channels, a security report is a context in which we will accept sensitive material, and we will handle it accordingly: restricted to the people working the issue, and deleted once the matter is closed. Send only what is actually relevant to the vulnerability.

If a vulnerability touches a console platform, do not describe the platform specifics in your initial mail. Tell us that console platform detail is involved and we will move the conversation to a channel where that discussion is permitted.

### Confidentiality of what you send us

**Anything proprietary or non-public you share with us in the course of a security report is treated as confidential, and no separate non-disclosure agreement is required for that to be true.**

We do this deliberately. Waiting on paperwork before a reporter feels safe describing an issue is exactly the kind of delay that gets people exploited. If you have found something, we would rather you tell us today than negotiate an NDA first.

Concretely, this means:

- Material you send us as part of a report is restricted to the people working the issue.
- We do not use it for any purpose other than investigating, fixing, and validating the fix.
- We do not disclose it to third parties, except where we must coordinate with an upstream maintainer or a platform holder to get the issue fixed, and in that case we will tell you first.
- Published advisories describe the vulnerability, not your environment. Your specifics are stripped.
- We delete what we no longer need once the issue is closed.

This applies to the security reporting channel only. It does not extend to our general support channels, which are public by design. See [SUPPORT.md](SUPPORT.md).

If your organization requires a signed agreement anyway, tell us and we will sign one. Please send the report first.

## What happens next

We are a small team, so here is honestly what to expect:

| Stage | Target |
| --- | --- |
| Acknowledgement that we received your report | 3 business days |
| Initial assessment and a severity call | 10 business days |
| Status update, and thereafter | Every 2 weeks until resolved |
| Fix for a critical issue | As fast as we can, prioritized above other work |

If you have not heard from us within a week, please follow up. Mail does get lost, and a nudge is not a nuisance.

We will tell you what we conclude, including when we decide something is not a vulnerability. If we disagree with your assessment we will explain why rather than simply closing the thread.

## Scope

**In scope:**

- The Namazu Elements platform, its SDKs, CLI, and officially published tooling and container images.
- The Namazu Cloud managed service and its control plane.
- Namazu Studios web properties, where the issue has real security impact.

**Out of scope:**

- Findings from automated scanners submitted without a working proof of concept or a demonstrated impact.
- Vulnerabilities that require a compromised host, a malicious dependency you introduced, or physical access.
- Issues in third party dependencies, unless the way we use the dependency is what creates the exposure. Please report those upstream, and tell us so we can pin or patch.
- Missing hardening headers, TLS configuration preferences, and similar findings with no demonstrated impact.
- Denial of service through raw volume, rate limiting complaints, and social engineering of our staff or users.
- Anything in a deployment you control that stems from your own configuration rather than a defect in our software.

Elements is a self-hosted platform under MPL 2.0. A misconfigured instance is not itself a vulnerability in Elements, but if our defaults or our documentation are what led you into the misconfiguration, that is worth reporting and we want to know.

## Supported versions

Security fixes land on the current release line. We will backport a fix for a critical issue to the previous minor release where it is practical to do so.

If you are running an older version, the fix is to upgrade. We cannot maintain security patches indefinitely across every historical release, and pretending otherwise would be worse than saying so plainly.

Namazu Cloud customers are patched by us as part of the service.

## Disclosure

We practice coordinated disclosure.

- We will work with you on a timeline. Our default is to publish once a fix is available and users have had a reasonable window to upgrade, typically **90 days** from the report at the outside.
- We will credit you in the advisory and release notes unless you ask us not to.
- We publish advisories through **GitHub Security Advisories** on the affected repository, and request a CVE where one is warranted.
- If an issue is already being exploited, we will move faster and will say so.

We ask that you give us a reasonable opportunity to fix an issue before publishing. We will not ask you to stay quiet indefinitely, and we will not use legal pressure to delay a disclosure we simply find inconvenient.

## Safe harbor

If you make a good faith effort to comply with this policy while researching a vulnerability, we will consider your research authorized, we will not pursue legal action against you, and we will work with you if a third party does.

Good faith means:

- You do not access, modify, or destroy data belonging to anyone else, and you stop as soon as you have confirmed an issue exists.
- You do not degrade the service for other users.
- You do not exfiltrate data, and you delete anything you incidentally obtained once you have reported it.
- You give us reasonable time to respond before disclosing.

Please test against your own instance rather than another studio's production deployment.

## Bounties

We do not currently run a paid bug bounty program. We are a small company and we would rather promise nothing than promise a payout we cannot honor consistently.

What we do offer is a genuine response, public credit, and a fix. If you have found something serious, tell us and we will find a way to thank you properly.

## Everything else

For non-security questions and general support, see [SUPPORT.md](SUPPORT.md).
