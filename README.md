<h1 align="center">Yash Pandya</h1>
<p align="center"><b>Offensive Security Researcher</b> · Bug Bounty Hunter · Vulnerability Research</p>

<p align="center">
  <img src="https://img.shields.io/badge/Focus-Offensive%20Security-3e7852?style=flat-square">
  <img src="https://img.shields.io/badge/Web%20%7C%20API%20%7C%20Mobile%20%7C%20Cloud-informational?style=flat-square">
  <img src="https://img.shields.io/badge/Bug%20Bounty-HackerOne%20%7C%20Bugcrowd-orange?style=flat-square">
  <img src="https://img.shields.io/badge/Apple%20%7C%20ImageMagick%20%7C%20Jackson-Credited%20CVEs%20%26%20advisories-critical?style=flat-square">
</p>

---

### 👋 About

I break web, API, mobile and cloud systems to find where the real risk is, prove it with a working
proof of concept, and write it up. Original memory-safety and application research with responsible
disclosure, bug bounty, and anonymized case studies from the field.

- 🎯 Depth over coverage: broken access control, authN/authZ, business logic, mobile, memory-safety research
- 🧪 Proof, not promises: every finding ships with a reproducible PoC
- ✍️ I publish what I find

---

### 🏆 Credited CVEs & Advisories

**Apple** — macOS
- [CVE-2026-112456](https://support.apple.com/en-ae/149521) — HFS heap corruption (out-of-bounds write), fixed in macOS 27.2

**Apache** — ActiveMQ Artemis
- [CVE-2022-35278](https://nvd.nist.gov/vuln/detail/CVE-2022-35278) — Stored XSS / content injection in the web console (pre-2.24.0)

**ImageMagick** — published repository advisories
- [GHSA-x48p-6655-8qgv](https://github.com/ImageMagick/ImageMagick/security/advisories/GHSA-x48p-6655-8qgv) — Heap buffer over-write (`-morph`)
- [GHSA-7438-vh5v-v52h](https://github.com/ImageMagick/ImageMagick/security/advisories/GHSA-7438-vh5v-v52h) — Heap buffer over-write (convex-hull, 32-bit)
- [GHSA-vm77-q83h-5fhg](https://github.com/ImageMagick/ImageMagick/security/advisories/GHSA-vm77-q83h-5fhg) — Despeckle 32-bit overflow (incomplete fix of CVE-2026-34238)
- [GHSA-qq8x-fq3x-43h4](https://github.com/ImageMagick/ImageMagick/security/advisories/GHSA-qq8x-fq3x-43h4) — MVG encoder code injection
- [GHSA-5222-mhv9-26rg](https://github.com/ImageMagick/ImageMagick/security/advisories/GHSA-5222-mhv9-26rg) — Heap buffer over-read (minimum bounding-box)

**FasterXML Jackson** (binary dataformats)
- [CVE-2026-104016](https://nvd.nist.gov/vuln/detail/CVE-2026-104016) · [CVE-2026-110747](https://nvd.nist.gov/vuln/detail/CVE-2026-110747) — protobuf parser integer overflow → memory exhaustion
- [CVE-2026-104895](https://nvd.nist.gov/vuln/detail/CVE-2026-104895) — Smile async parser · [CVE-2026-68496](https://nvd.nist.gov/vuln/detail/CVE-2026-68496) — Smile · [CVE-2026-68495](https://nvd.nist.gov/vuln/detail/CVE-2026-68495) — CBOR

*More disclosures in coordinated-disclosure timelines; listed here once published.*

---

### 🔬 Research & Writing

30+ write-ups: disclosures, memory-safety research, and anonymized case studies.

- **An out-of-bounds write in Apple HFS** (CVE-2026-112456) · **ImageMagick memory-safety series** (5 advisories)
- **Cross-tenant BOLA in a multi-tenant fintech** · **OTP brute-force → MFA bypass** · **Stored XSS → admin takeover (CVSS 9.0)**
- **Hunting RCE in modern stacks** · **HTTP request smuggling: a field guide** · **Business-logic flaws scanners never find**

📚 Markdown archive → **[github.com/bewithyash/field-notes](https://github.com/bewithyash/field-notes)** · rendered → **[blog.imperonlabs.com](https://blog.imperonlabs.com)**

---

### 🧰 Focus areas

`Broken Access Control` · `BOLA / IDOR` · `Auth / Session` · `Business Logic` · `Mobile (Android/iOS)` · `API Security` · `Memory-safety / fuzzing`

---

<p align="center">
  <img height="150" src="https://github-readme-stats.vercel.app/api?username=bewithyash&show_icons=true&hide_border=true&title_color=3e7852&icon_color=3e7852&count_private=true" />
</p>
