# Adoption guide

**Status: discussion draft only.** Obtain qualified legal review before using PCL for a commercial release. This guide is not legal advice and does not itself license any material.

## 1. Identify the covered work

Identify the copyright holders and confirm they control all rights they intend to grant. Inventory dependencies, third-party assets, contributors, pre-existing grants and platform agreements. Separate project code, creative assets, and branding where their terms differ.

## 2. Use a fixed version

For evaluation, copy [PCL-1.0-draft.1.txt](PCL-1.0-draft.1.txt) into the target project's LICENSE file, filling only the copyright placeholder. Do not remove the draft status or modify substantive terms while claiming to use the identical version. For production, use a legally reviewed final version once available.

Suggested notice:

```text
Copyright (c) [year] [copyright holder(s)]

The material identified in this notice is licensed under the
Permissive Commercial License, version 1.0 — Draft 1 (2026-11-26).
See the accompanying LICENSE file for the complete terms.

This is a custom source-available license, not an OSI-approved license.
Third-party material is subject to its own applicable terms.
```

For a mixed-license project, name the covered paths or assets explicitly and maintain a third-party notices file. A repository being public does not establish which license applies to its contents.

## 3. Machine-readable metadata

If tooling supports custom SPDX references, a suggested local identifier for this exact draft is:

```text
SPDX-License-Identifier: LicenseRef-PCL-1.0-draft.1
```

Supply the actual license text in the repository and in any relevant SPDX document's extracted licensing information. This is a custom reference, not an official SPDX-listed identifier. Some package managers or scanners may require a license-file field or other custom metadata. Do not substitute MIT or another recognized identifier to satisfy a validator.

## 4. Distribution

Preserve notices, include the exact license or a durable reference to it, and mark modifications. Check the three-part test before selling or monetizing an unchanged or superficially modified version. If uncertain, seek permission from the relevant copyright holder.

For creative publications, identify the licensed material and link to the exact version in the credits or description. A platform's own license settings may grant separate rights and should not be treated as implementing PCL automatically.

## 5. Version changes

Existing license grants remain effective for compliant recipients. Publish new revisions under a distinct designation and state explicitly which project versions use them. Do not relicense contributions without authority. Do not claim PCL covers third-party assets merely because they are included in a repository.

## 6. Before production adoption

- Obtain jurisdiction-specific review of Sections 3, 6, 7 and 9.
- Verify contributor permissions, ownership, and dependency compatibility.
- Determine whether a separate commercial EULA or consumer disclosures are necessary.
- Check name and trademark clearance.
- Record the exact final license version alongside each release.

No project outside this repository has been changed as part of publishing the draft.
