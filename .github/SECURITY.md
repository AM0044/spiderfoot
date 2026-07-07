# Security Policy

> **Note:** This is a stripped-down, work-in-progress fork of
> [SpiderFoot](https://github.com/smicallef/spiderfoot). It is maintained on a
> best-effort basis and is **not** the official SpiderFoot project. For issues
> in upstream SpiderFoot, please report them to that project instead.

## Supported versions

Only the latest state of the `master` branch receives security fixes. Because
this fork is under active cleanup, older commits and tags are not supported.

| Version            | Supported          |
| ------------------ | ------------------ |
| `master` (latest)  | :white_check_mark: |
| Older commits/tags | :x:                |

## Reporting a vulnerability

Please **do not** open a public issue for security vulnerabilities.

Report privately using GitHub's private vulnerability reporting: open the
**Security** tab of this repository and choose **"Report a vulnerability"**, or
use this link:

<https://github.com/AM0044/spiderfoot/security/advisories/new>

When reporting, please include where possible:

- A description of the vulnerability and its potential impact.
- Steps to reproduce, or a proof-of-concept.
- The affected file(s), module(s), or component(s).
- Any suggested remediation, if you have one.

## What to expect

This project is maintained by a single person on a best-effort basis, so
response times are not guaranteed. The intent is to:

- Acknowledge a valid report as soon as reasonably possible.
- Investigate and confirm the issue.
- Develop and release a fix on `master`.
- Credit the reporter, unless anonymity is requested.

## Disclosure

Please practice coordinated disclosure: allow a reasonable opportunity to
address the issue before any public disclosure. Reports handled through
GitHub's private advisory workflow remain confidential until a fix is published.

## Intended use

SpiderFoot is an OSINT and attack-surface-mapping tool intended for lawful,
authorized security assessment and research. Only run it against systems and
data you own or have explicit permission to assess.
