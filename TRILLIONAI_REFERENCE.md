# Semgrep — TrillionAI Engineering Reference

This is an engineering **source research archive**, not a deployment of Semgrep and not the proprietary TrillionAI Audit application.

## Upstream provenance
- Original project: https://github.com/semgrep/semgrep
- Original branch: `develop`
- Pinned upstream commit: `06d9993409f6698f78f6956cd39d968e7f4d7b6a`
- Expected pinned upstream Git tree: `5d2f52f238791554ed973215fd030f22b278395d`
- Tracked inventory: 16,078 Git tree entries, including 12,876 blobs (approx. 599.3 MB).
- Repository main-branch goal: actual upstream tracked source at the root, not only a README.
- Import state: **VERIFIED — source imported directly to `main` and remote Git tree checked**.
- [Successful GitHub Actions source import](https://github.com/Anselm04/Semgrep-Source-Code-Reference/actions/runs/43647604268)
- Verified destination `main` Git tree: `b7db2424990b9b3ebbd03ef809af491b0af60ef0`
- Git root source comparison: all original upstream root entries except `.github` match by Git object SHA; `.github/workflows` is excluded to prevent imported CI execution.
- New TrillionAI-specific file: `TRILLIONAI_REFERENCE.md`.
- Original Git submodule at `tests/semgrep-rules` is a pointer, not included submodule content.

## Licensing and boundaries
The original repository root `LICENSE` is GNU Lesser General Public License 2.1 (LGPL-2.1); some directories and bundled parser libraries carry their **own licence texts**. Their licensing is not overwritten or replaced. Original `COPYRIGHT` and other notices must be preserved. Some additional Semgrep products, services and rules may carry different licensing. Do not automatically copy this source into proprietary TrillionAI Audit; separately review obligations for particular files or linking, and implement proprietary orchestration independently.

The upstream source tree references the submodule `tests/semgrep-rules` as a Gitlink. The Gitlink is preserved as source metadata, but **its external contents are not fetched or included in this archive**. Git LFS objects, if any, are not independently downloaded.

## Verified import

- [Successful source import and integrity verification](https://github.com/Anselm04/Semgrep-Source-Code-Reference/actions/runs/43647604268)
- Pinned upstream original tree: `5d2f52f238791554ed973215fd030f22b278395d`.
- Verified main branch Git tree: `2531814f75521b5d4a2c68145842d923087e76eb`.
- Compared 16,078 original Git tree entries against the destination; zero discrepancies outside intentional GitHub CI removal and this research document.
- Original root licence and subdirectory copyright/licence notices remain in source.
- The root tree differs because original upstream GitHub Actions workflows are omitted and `TRILLIONAI_REFERENCE.md` was added. This is a source archive, not a build or test certification.

## Safe import
The [import workflow](.github/workflows/import-semgrep-source.yml) should fetch the exact source revision, import its root tree to `main`, keep this document as `TRILLIONAI_REFERENCE.md`, and exclude upstream GitHub Actions workflow definitions from the imported root to prevent unintended execution. The pinned original Git tree is compared with the fetched upstream commit, and all tracked root tree entries are compared after import except the known CI and provenance changes.

**The source import has passed GitHub remote integrity verification and source directories are directly accessible on `main`.** Never bypass secret push protection. If upstream fixtures are blocked, remove only the documented blocked paths and verify the resulting filtered source tree.

## Research goals
1. Security rule parsing and matching
2. Source-code vulnerability findings, severities and confidence
3. False-positive minimisation and bounded scanning
4. Multi-language capabilities and scanning limitations
5. Machine-readable results, evidence integrity and remediation
6. Safely integrating an external scanner into original Node.js/TypeScript and Flutter software

No paid services, cloud integrations or upstream execution are authorised by this reference import.
