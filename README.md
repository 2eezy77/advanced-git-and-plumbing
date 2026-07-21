# Advanced Git and Plumbing

**Completed by Jose I. Montero** | December 15, 2025

Notes and practice artifacts from a deep dive into Git internals, plumbing commands, and professional workflows, based on the [Boot.dev](https://www.boot.dev) course by ThePrimeagen.

This repository focuses on how Git stores data, how hashes and refs work, and how to manipulate history with intention rather than trial and error.

## Course overview

- **Instructor:** ThePrimeagen
- **Scope:** ~8 hours, 75 interactive lessons
- **Focus:** Git internals, rebasing, reset, remotes, and repository hygiene

## Skills covered

### Git internals and plumbing

Git as a content-addressable filesystem:

- Exploring `.git` objects, refs, and the index
- How Git stores blobs, trees, and commits on disk
- Low-level plumbing commands that sit under everyday porcelain (`add`, `commit`)

### Advanced workflow and history

- Rebase vs merge for a clean, linear history
- Reset to undo and recover with confidence
- Branching as context switching, not just naming

### Collaboration and configuration

- Remotes, push/pull, and GitHub hosting
- Local and global `.gitconfig`
- `.gitignore` patterns for clean working trees

## Chapter breakdown

| Chapter | Focus | Key concept |
| --- | --- | --- |
| 1–2 | Setup and repos | What a repository actually is |
| 3 | Internals | Filesystem storage and plumbing |
| 4 | Config | Identity and global settings |
| 5–7 | Branch / merge / rebase | Integrating changes cleanly |
| 8 | Reset | Undoing changes safely |
| 9–11 | Remote and GitHub | Hosting, ignore rules, collaboration |

## Repository contents

| Path | Purpose |
| --- | --- |
| [`contents.md`](contents.md) | Index of practice files |
| [`titles.md`](titles.md) | Sample titles collection |
| [`classics.csv`](classics.csv) | CSV practice data |
| [`quotes/`](quotes/) | Quote files used in course exercises |

## Proof of completion

- **Completion date:** December 15, 2025
- **Certificate ID:** `74ea3f12-426f-49e8-83fe-2277c67f6ab4`
- **Repository:** [github.com/2eezy77/advanced-git-and-plumbing](https://github.com/2eezy77/advanced-git-and-plumbing)

## License

MIT — see [LICENSE](LICENSE).
