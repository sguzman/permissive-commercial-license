# Permissive Commercial License (PCL)

**A public copyright license proposal for broad commercial reuse, with a narrow restriction on substantially unchanged commercial substitutes.**

| Specification | Status |
| --- | --- |
| Version | 1.0 — Draft 1 |
| Date | 26 November 2026 |
| Classification | Source-available / custom copyright license |
| Legal review | Pending; not recommended for production adoption until reviewed |
| OSI approval | None; the commercial redistribution restriction is incompatible with the Open Source Definition |
| Official SPDX identifier | None claimed |
| Maintainer | [Salvador Guzman](https://github.com/sguzman) |

[Read the complete draft](PCL-1.0-draft.1.txt) · [Adoption guide](ADOPTION.md) · [FAQ and examples](FAQ.md) · [Design and review notes](DESIGN.md) · [Version history](CHANGELOG.md)

## 1. Purpose

PCL is intended for authors who want to make their work widely accessible and commercially useful without granting permission for substantially unchanged copies to be commercially distributed as direct substitutes for the original.

The license does not seek to prevent competition, commercial reuse, independent development, or profitable derivative works. It distinguishes competition through meaningful creation from commercial redistribution of an effectively unchanged substitute.

The word *permissive* describes the breadth of the proposed grant in ordinary language. It does not imply that PCL is an OSI-approved or conventional permissive open-source license.

PCL is designed to cover software, games, documentation, mathematical demonstrations, video, artwork, and other copyrightable materials expressly placed under it. It does not create ownership over mathematical facts, ideas, methods, or public-domain material.

## 2. Permissions and obligations

The following is an explanatory summary, not a substitute for the license text.

| Activity | Treatment under the draft |
| --- | --- |
| Personal, educational, academic, research, and internal business use | Permitted |
| Study, copy, modify, fork, and improve the Work | Permitted |
| Distribute unchanged copies without commercial monetization | Permitted |
| Sell substantially improved or meaningfully transformed versions, including competing versions | Permitted |
| Sell unchanged copies that are not commercial substitutes | Permitted |
| Incorporate code into materially distinct commercial products | Permitted |
| Create proprietary derivatives or distribute binaries without releasing source | Permitted |
| Charge for genuine support, hosting, customization, instruction, or maintenance | Permitted, subject to the commercial-substitution rule |
| Publish monetized commentary, tutorials, reviews, and gameplay | Permitted, subject to other applicable rights |
| Commercially distribute a substantially unchanged direct substitute | Not authorized |
| Rebrand an unchanged game or application and sell it as a substitute | Not authorized |
| Reupload an effectively unchanged video for revenue as a substitute | Not authorized |
| Remove required copyright and license notices | Not authorized |
| Misrepresent a derivative as an official or endorsed release | Not authorized |
| Use trademarks or patented inventions | Not expressly granted |
| Demand support, maintenance, updates, or warranties under PCL | Not provided |

Conditions of permitted redistribution: retain attribution, preserve the applicable license information, and reasonably identify modifications. Third-party rights and mandatory law still apply.

No royalties, mandatory upstream contribution, general noncompete clause, or source-disclosure requirement are imposed by the draft.

## 3. The commercial-substitution test

Section 3 restricts distribution only when all three elements are present:

1. **Commercial distribution.** Payment or revenue directly attributable to making the copy available, including monetized publication.
2. **Substantially unchanged work.** The protected expression or functionality remains effectively the same, without material transformations that provide independent value.
3. **Commercial substitution.** The offering serves substantially the same audience and principal purpose as an original authorized offering, providing substantially the same principal value instead of it.

If any element is absent, the narrow restriction does not apply. All other license conditions remain applicable.

| Commercial distribution? | Substantially unchanged? | Commercial substitute? | Section 3 |
| --- | --- | --- | --- |
| No | Either | Either | Permitted |
| Yes | No | Either | Permitted |
| Yes | Yes | No | Permitted |
| Yes | Yes | Yes | Not authorized |

The test is qualitative. There is no arbitrary minimum number of changed lines, minutes of new footage, or percentage of replaced assets. A new logo or different file format does not alone make an otherwise unchanged copy meaningfully distinct.

## 4. Practical examples

| Scenario | Intended result |
| --- | --- |
| A developer sells a new game built on a PCL-covered engine with original gameplay and assets. | Permitted |
| A developer materially improves an existing game and sells it to the same audience. | Permitted |
| A publisher changes a game's name and splash screen and sells the same game. | Not authorized |
| A mirror provides an unchanged copy free of charge without monetizing the distribution. | Permitted |
| A distributor charges only reasonable actual physical media or distribution costs. | Permitted |
| A developer sells support for a PCL application. | Permitted |
| A video creator publishes monetized analysis or gameplay with independent value. | Permitted |
| A channel reuploads the original math video unchanged to earn advertising revenue. | Not authorized if it is a commercial substitute |
| A translator publishes a materially valuable localized adaptation. | Generally permitted; the actual transformation and substitution test still governs |
| A competing developer independently implements the same algorithm without copying protected expression. | Outside the restriction |

More cases, including gray areas, appear in the [FAQ](FAQ.md). These examples are interpretations of the intended draft, not binding legal opinions.

## 5. Warranty, liability, and maintenance

Sections 6–8 provide an as-is/as-available disclaimer, broad limitations of liability, and no contractual obligation under the license to maintain or support the Work.

The intention is to protect authors and contributors from claims based on bugs, inaccurate results, security defects, downtime, incompatibility, or other failures. These provisions operate only to the extent permitted by applicable law. No copyright license can guarantee that an author will never be sued or eliminate mandatory consumer, safety, or other legal obligations.

## 6. Relationship to other licensing models

PCL is not MIT with a marketing label. Its restriction materially changes recipients' rights.

| Feature | MIT | GPL-3.0 | CC BY 4.0 | PCL draft |
| --- | --- | --- | --- | --- |
| Commercial use | Yes | Yes | Yes | Yes |
| Commercial sale of unchanged substitutes | Yes | Yes | Yes | Restricted |
| Meaningful competing derivatives | Yes | Yes | Yes | Yes |
| Proprietary software derivatives on distribution | Yes | No, subject to GPL obligations | Not designed for software | Yes, subject to PCL conditions |
| Attribution / notices | Required | Required | Required | Required |
| Source disclosure on distribution | No | Generally required for covered binaries | Not applicable | No |
| OSI-approved software license | Yes | Yes | No | No |

PCL is not intended as a drop-in replacement for licenses that forbid additional restrictions. Combining PCL-covered material with GPL-covered material for distribution may be incompatible. Separate components and independent works require their own analysis. MIT or other previously granted rights cannot be withdrawn by relabeling an existing copy.

For reference: [Open Source Definition](https://opensource.org/osd), [GNU license compatibility guidance](https://www.gnu.org/licenses/license-compatibility.en.html), [SPDX License List](https://spdx.org/licenses/).

## 7. Adoption

The current text is a discussion draft. Before adopting it in production, have qualified counsel review the exact version, particularly the commercial-substitution test, enforceability, warranty provisions, and applicable consumer law.

For evaluation and review, the [adoption guide](ADOPTION.md) provides an exact-version notice, guidance on marking covered files, treatment of third-party material, and an optional custom SPDX reference. No official SPDX registration is implied.

The canonical draft is versioned in this repository. Do not silently change the terms while retaining the same version designation. The license text—not this README, examples, or FAQ—controls an actual grant.

## 8. Status and feedback

This is an independently maintained license proposal, not a standard endorsed by a foundation, standards organization, or legal authority. No legal review, court validation, or formal name/trademark clearance is claimed.

Feedback on ambiguity, practical edge cases, compatibility, and legal drafting is welcome through [GitHub Issues](https://github.com/sguzman/permissive-commercial-license/issues). See [design and review notes](DESIGN.md) for the outstanding questions.

The repository publishes a reusable draft template; merely hosting the text does not apply PCL to other repositories or to third-party work. The license text may be copied verbatim for evaluation or adoption, with its version and draft status retained. Proposed revisions may be shared for review as clearly marked proposals. Other repository materials are not automatically licensed under PCL.
