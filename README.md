# Respectful Software

Is your software respectful to its community?

Since neither OSS nor FOSS define how to work with a community, any
_Free/Libre and Open Source Software_ can completely disregard and disrespect
it. For example, if you need to contribute an important fix to said software,
its owners can, but not limited to,

- force you to give up your personal information and then sell it to the
advertisement company

- force you to sign a CLA, make software proprietary and then sell your work
without your permission or any kind of attribution at all

- force you to pay for an ability to contribute

Obviously that this is totally unacceptable. The following guidelines is an
attempt to fix this gap in the (FL)OSS definition, as well as encourage authors
to make software with respect to the community in mind.

Refer to the [RFC 2119] to clarify MUST, SHOULD, etc keywords.

1. Software MUST be (FL)OSS
- If your software isn't (FL)OSS, it is more than disrespectful already.

2. Software MUST be friendly to the community
- That is, there MUST be a way to contribute to it, report a bug and ask for a
  new feature.

3. Software MUST NOT charge contributors
- Contributors are those people who fix bugs and add new features to your
  software. In return, software MUST respect them.

4. Contributors MUST NOT be forced to sign a CLA
- A CLA is extremely harmful to the contributors since it allows code owners to
  change license terms at their own discretion. As a result, software could be
  turned into proprietary, allowing to profit from contributors work without
  any attribution.

- Instead, consider using the [DCO] which does not force contributors to give up
  their rights.

5. Software MUST NOT have tracking/telemetry without user concern
- Software that acts like spyware is disrespectful to everyone, or rather
  malicious.

6. CoC/Contributor Covenant SHOULD NOT be used to police community
- A CoC is usually enforced to ban people who disagree with political decisions
  that software maintainers make. Thus, software maintainers MUST NOT ban people
  who disagree with political decisions, or those who disagree in general.

- Even if your software needs a CoC for a good reason, it is still disrespectful
  to the community. It's a matter of trust. Do you trust and respect your
  community? If you do, then a CoC is unnecessary. Stop attempting to regulate
  anyone and especially enforce dumb rules. It is highly unwelcome to everyone.
  It brings no value to the development process. It makes it hard to communicate
  with software maintainers **respectfully** since a CoC indicates that they
  have no respect for the community in the first place. Keep this in mind if
  you're going to add a CoC.

- Instead, consider adopting the [GNU KCG]. Unlike a CoC, it covers very
  important topics, namely what to do in various complex situations and more
  importantly, how to work with a community.

7. Software SHOULD NOT be hosted on a proprietary platform
- Unlike open-source and community-driven platforms, proprietary platforms tend
  to exploit their users in various ways in order to extract maximum profit.
  Software MUST NOT be hosted on such platforms.

8. Software MUST NOT demand personal information
- Such as real name, address, phone number and so on. This information is
  directly attached to you and your real life. Thus, software MUST provide a way
  to not give any kind of personal information that can be used to track you
  down and harm you in any possible way.

9. Automation MUST NOT be used to handle contributions
- In no way automation, such as stale bots, MUST ever be used to close and/or
  lock bug reports or feature requests, unless resolution has been provided and
  reporter satisfied with it. This applies to the other ways of contributing as
  well.

[RFC 2119]: https://www.ietf.org/rfc/rfc2119.txt
[DCO]: https://developercertificate.org
[GNU KCG]: https://www.gnu.org/philosophy/kind-communication.html
