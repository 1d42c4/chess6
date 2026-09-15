# Chess Library — Main Index

A complete, organized upload of the Desktop `chess` collection, split across three repositories. Start here to choose what to study or download.

| Repository | Contents | Original files | Download size |
| --- | --- | ---: | ---: |
| [chess4](https://github.com/1d42c4/chess4) | Opening courses and complete repertoires | 385 | 346.2 MiB |
| [chess5](https://github.com/1d42c4/chess5) | Strategy, endgames, reference and detailed courses | 1,123 | 315.1 MiB |
| [chess6](https://github.com/1d42c4/chess6) | Complete Chess PDF Courses and original archive | 127 | 359.4 MiB |

Together, these repositories contain **1,635 original source files**, including **1,400 PDFs**, plus the README guides and verification manifests added for this upload. The total downloadable source content is **1020.6 MiB**, including the restored 151.5 MiB ZIP archive. Sizes count file content rather than compressed Git transfers.

## Find your material

- **[chess4](https://github.com/1d42c4/chess4):** opening course books and matching workbooks (Improved Boards subjects 01–08 and 12–26), the complete White 1.d4/2.c4 repertoire, Top 50 opening courses, the Top 10 opening study, and the original `pdf` folder with additional opening courses and its ZIP library.
- **[chess5](https://github.com/1d42c4/chess5):** Improved Boards subjects 09–11 and 27–41, covering positional play, improvement, tactics, calculation, endgames and tournament skills; the complete A00–E99 Opening Atlas; the Chess Principles Encyclopedia; and the remaining mastery, practice, advice, repertoire and deep-understanding courses.
- **[chess6](https://github.com/1d42c4/chess6):** all of `group1/aipdf`, including the older-style Complete Chess PDF Courses as individual files and the original full ZIP archive.

The original Improved Boards index describes all 41 numbered subjects; its files are divided between chess4 and chess5 as shown above. Each course folder stays together. The original root README is preserved at [chess4/library/README.md](https://github.com/1d42c4/chess4/blob/main/library/README.md); it describes an earlier collection and may mention files absent from this Desktop snapshot.

## Download and read

1. Open the repository that contains the material you want.
2. Select **Code → Download ZIP**, then extract the download. For one PDF, open its file page and select **Download raw file**.
3. Browse `library/` and follow the included course indexes, starting guides, books and workbooks. PDF files can be saved to a phone or tablet and read offline.

**One archive in chess6 uses Git LFS:** `library/group1/aipdf/older style/Complete Chess PDF Courses.zip`. GitHub's generated repository ZIP may contain only its small pointer. Download the [original archive from its file page](https://github.com/1d42c4/chess6/blob/main/library/group1/aipdf/older%20style/Complete%20Chess%20PDF%20Courses.zip) using **Download raw file**, or clone chess6 with Git LFS installed and run `git lfs pull`. All other source files are stored directly in Git.

## Folder layout and completeness

Every source file is assigned to exactly one new repository under `library/`, preserving the original relative folder path. To combine the collection locally, download all three repositories and merge the contents of their `library` folders. Files with the same names in different original folders remain separate.

The source ZIP was a 134-byte Git LFS pointer. The original 158,853,550-byte ZIP was recovered and verified against the exact SHA-256 in that pointer: `1a01ec99acbe0e2b9b6153d6e546564fa50ce527544738cbab875f8e0e2216da`. The upload uses that original archive, not a newly generated replacement.

The empty source directory `group1/aipdf/new style` is retained in chess6 with a documented `.gitkeep` placeholder, because Git does not store empty folders. Each repository contains `SOURCE_MANIFEST.csv` listing its original file paths, content sizes, SHA-256 checksums, and storage method. The main index in chess4 also has `COMPLETE_SOURCE_MANIFEST.csv` covering all three repositories.

## Changes and protection

The `main` branch in each repository is protected against force pushes and branch deletion. Future file changes go through a pull request; no users or apps have a bypass exemption. Independent review approval is not required, so the owner can maintain the collection without another collaborator.

These settings preserve branch history and make changes deliberate. Files can still be changed or deleted through a merged pull request. The repository owner can change the rules or delete an entire repository, so retain a local copy.

## Use and corrections

This collection shares AI-created chess learning material. Follow the licenses and credits included with each course, and verify critical chess claims before relying on them. For a correction, identify the repository, course, file, page and specific move or explanation.

The existing [chess](https://github.com/1d42c4/chess), [chess1](https://github.com/1d42c4/chess1), [chess2](https://github.com/1d42c4/chess2) and [chess3](https://github.com/1d42c4/chess3) repositories are separate from this three-part upload.
