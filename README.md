# someonedos

Independent security researcher. Vulnerability disclosures handled through
[VulnCheck](https://www.vulncheck.com) (CVE Numbering Authority).

## Published CVEs

| CVE | Product | Type | CVSS | References |
| --- | --- | --- | --- | --- |
| [CVE-2026-136920](https://nvd.nist.gov/vuln/detail/CVE-2026-136920) | OneDev < 17.2.4 | Git argument injection via fuzzy commit query — arbitrary file creation/truncation, DoS | 7.2 High | [VulnCheck advisory](https://www.vulncheck.com/advisories/onedev-before-17.2.4-git-argument-injection-via-fuzzy-commit-query) (credited) · [GHSA-hcv4-7hc3-p6gh](https://github.com/advisories/GHSA-hcv4-7hc3-p6gh) · [fix commit 25d36b2](https://github.com/theonedev/onedev/commit/25d36b2cbd35cb779259e409bfe49d6e17538a81) |
| [CVE-2026-136169](https://nvd.nist.gov/vuln/detail/CVE-2026-136169) | Cockpit CMS ≤ 2.14.1 | Stored XSS via unescaped linked-item `_id` values | 5.4 Medium | [GHSA-hq9w-j2p2-2gw4](https://github.com/advisories/GHSA-hq9w-j2p2-2gw4) |

## In review

- Wallos < 5.11.2 — payment-schedule unbounded loop DoS via unvalidated subscription `frequency` (submitted, CVE pending)

## Notes

- All findings were verified dynamically against unmodified release builds in isolated local environments.
- Fix for CVE-2026-136920 was released by the vendor (17.2.4) prior to advisory publication; CVE assigned retroactively by VulnCheck.
