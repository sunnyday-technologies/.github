# Security policy — Sunnyday Technologies

This is the **default policy** for Sunnyday Technologies repositories. Several
projects publish their own `SECURITY.md`; where one exists, **it takes
precedence over this file** — it will be more specific about what counts as a
serious finding for that project.

Repositories with their own policy include
[Open3DCP](https://github.com/sunnyday-technologies/Open3DCP),
[Open3DPP](https://github.com/sunnyday-technologies/Open3DPP),
[M3-CRETE](https://github.com/sunnyday-technologies/M3-CRETE),
[M3-CRETE-FIRMWARE](https://github.com/sunnyday-technologies/M3-CRETE-FIRMWARE),
[CADCLAW](https://github.com/sunnyday-technologies/CADCLAW),
[paramat](https://github.com/sunnyday-technologies/paramat) and
[MARB](https://github.com/sunnyday-technologies/MARB).

## Reporting

Preferred: GitHub's private reporting — **Security → Report a vulnerability** on
the affected repository. That keeps the report confidential until a fix is out.

If the repository has private reporting disabled, or you would rather not use
GitHub, email **security@sunn3d.com**.

Please do not open a public issue for a finding that is exploitable, that
exposes personal data, or that could lead to physical injury.

## What we consider a security finding

Our repositories are a mix of open hardware, firmware configuration, developer
tooling, published data standards, and static sites. Across all of them:

- **Physical safety.** Several projects publish buildable hardware designs and
  firmware configuration for machines with real stored energy, moving mass, and
  heated or pressurised components. A published design, quantity, or setting
  that could injure someone who follows it is our most serious defect class —
  report it privately and treat it as urgent.
- **Credentials and personal data** committed to a repository, present in
  published artifacts, or leaking into generated reports, renders or logs.
- **Integrity of published artifacts.** A released file whose contents differ
  from what the repository or changelog says, an identifier resolving somewhere
  unintended, or a released version altered rather than superseded — including
  anything that would make an existing DOI resolve to changed content.
- **Code execution** reachable from input a user would reasonably treat as data
  rather than as a program.
- **Supply chain.** A dependency, upstream reference, release, or checksum that
  points somewhere other than the genuine project it names.

## Out of scope

- Third-party or vendor data being wrong at its source. Several projects record
  published third-party claims and verify none of them; that is a data-quality
  issue — open a normal issue.
- Vulnerabilities in upstream dependencies. Report those to the upstream
  project; tell us as well if our usage widens the impact or defeats the fix.
- The inherent hazards of competently operating experimental equipment as
  documented. Our hardware is research equipment for qualified teams, which is
  stated plainly in those projects and is not a defect.
- Automated scanner output with no demonstrated impact.

## Response

We aim to acknowledge within five working days, and faster for anything with a
credible injury path or live data exposure. Fixes are published with the reason
stated in the changelog; a released artifact is superseded rather than silently
rewritten, so anyone relying on an earlier version can tell what changed.

We are a small team and run no bug-bounty programme. We will credit reporters
who want it.
