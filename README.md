[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/AM0044/spiderfoot/master/LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/AM0044/spiderfoot)](https://github.com/AM0044/spiderfoot/commits/master)
[![OpenSSF Scorecard](https://api.scorecard.dev/projects/github.com/AM0044/spiderfoot/badge)](https://scorecard.dev/viewer/?uri=github.com/AM0044/spiderfoot)

**About**
SpiderFoot is an OSINT automation tool for threat intelligence and attack-surface
mapping. It collects data about a target (domains, IPs, emails, names, and more)
by running a large set of independent collection **modules** and correlating what
they find.

This fork exists to **trim the project down to a minimal, working baseline** and
then rebuild outward deliberately, rather than carrying the full upstream surface
area and its accumulated dead weight.

**Upstream project**
[`smicallef/spiderfoot`](https://github.com/smicallef/spiderfoot).
This fork tracks its own path and does not aim to stay in sync.

**Current focus**
- Removing deployment scaffolding so the core runs as a plain Python app.
- Reviewing and updating outdated or vulnerable dependencies.
- Resetting stale docs (this file replaces the old README).

**License**
Inherits its license from upstream SpiderFoot — see the LICENSE file and retain
upstream attribution as required.
