# Security Policy

We take the security of all of our software products seriously. Thank you for taking the time to
responsibly disclose any issues you find.

## Reporting Security Issues

If you believe you have found a security vulnerability in any of our organization's repositories, or
any of our downstream dependencies (that are not otherwise disclosed to them yet) please report it
to us through responsible coordinated disclosure.

**Please do not report security vulnerabilities through public channels.**

Instead, please send an email to [security@mvup.co](mailto:security@mvup.co). All security bugs
should be reported to this email address. This list is delivered to a small security team. Your
email will be acknowledged within 24 hours and you'll receive a more detailed response to your email
within 48 hours indicating the next steps in handling your report. If you would like, you can
encrypt your report using our [public key](https://github.com/mvup/our-pgp-key).

Please include as much of the information listed below as you can to help us better understand and
resolve the issue:

- The type and description of the issue
- Full paths of source file(s) related to the manifestation of the issue
- The location of the affected source code (tag/branch/commit or direct URL)
- Any special configuration required to reproduce the issue
- Step-by-step instructions to reproduce the issue
- Proof-of-concept or exploit code (if possible)
- Impact of the issue, including how an attacker might exploit the issue

This information will help us triage your report more quickly.

### Escalation

This email address receives a large amount of spam, so be sure to use a descriptive subject line to
avoid having your report be missed. After the initial reply to your report, the security team will
endeavor to keep you informed of the progress being made towards a fix and full announcement. As
recommended by [RFPolicy](https://bhgomes.net/rfpolicy.txt), these updates will be sent at least
every five days. In reality, this is more likely to be every 24-48 hours.

If you have not received a reply to your email within 48 hours, or have not heard from the security
team for the past five days, there are a few steps you can take (in order):

1. Contact the security coordinator directly: [Brandon H. Gomes](mailto:bhgomes@pm.me).
2. Post on the [Discussions Forum](https://github.com/orgs/mvup/discussions)

Please note that the forums are public areas. When escalating in these venues, please do not discuss
your issue. Simply say that you're trying to get a hold of someone from the security team.

## Disclosure Process

We have a 5-step disclosure process:

1. The security report is received and is assigned a primary handler. This person will coordinate
   the fix and release process.
2. The problem is confirmed and a list of all affected software and versions is determined.
3. Code is audited to find any potential similar problems.
4. Fixes are prepared for all releases which are still under maintenance. These fixes are not
   committed to the public repository but rather held locally pending the announcement.
5. On the embargo date, the
   [security mailing list](https://groups.google.com/g/mvup-security-announcements)
   is sent a copy of the announcement. The changes are pushed to the appropriate public repositories
   and new builds are deployed when possible. Within 6 hours of the mailing list being notified, a
   copy of the advisory will be published in a public place.

This process can take some time, especially when coordination is required with maintainers of other
projects. Every effort will be made to handle the bug in as timely a manner as possible, however
it’s important that we follow the release process above to ensure that the disclosure is handled in
a consistent manner.

## Receiving Security Updates

The best way to receive all the security announcements is to subscribe to the
[security announcements mailing list](https://groups.google.com/g/mvup-security-announcements)
(alternatively by sending an email to
[mvup-security-announcements+subscribe@googlegroups.com](mailto:mvup-security-announcements+subscribe@googlegroups.com)
). The mailing list is very low traffic, and it receives the public notifications the moment the
embargo is lifted.

## Bounties

We do not currently have a bounty program. Please refer back to this page when we add one.

## References

This disclosure policy is inspired by the
[GitHub](https://github.com/github/.github/blob/main/SECURITY.md) and
[Rust](https://www.rust-lang.org/policies/security) disclosure policies.

