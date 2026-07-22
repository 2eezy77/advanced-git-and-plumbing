# Advanced Git and Plumbing

Notes from Jose I. Montero on Git internals, plumbing commands, and professional workflows, based on the [Boot.dev](https://www.boot.dev) Advanced Git course (ThePrimeagen).

This repo is kept as a short, honest record of what I studied: how Git stores objects, how refs and the index work, and how to rebase, reset, and work with remotes with intention.

## What I focused on

### Internals and plumbing
- `.git` objects, refs, and the index
- Blobs, trees, and commits as a content-addressable store
- Plumbing commands underneath everyday porcelain (`add`, `commit`, `status`)

### History and recovery
- Rebase vs merge for a readable history
- Reset for undoing and recovering safely
- Branches as context, not just names

### Collaboration and hygiene
- Remotes, push/pull, and GitHub hosting
- Local and global `.gitconfig`
- `.gitignore` patterns for a clean working tree

## Course context

| Detail | Value |
| --- | --- |
| Instructor | ThePrimeagen |
| Scope | About 8 hours, 75 interactive lessons |
| Completion | December 15, 2025 |
| Certificate ID | `74ea3f12-426f-49e8-83fe-2277c67f6ab4` |

Early commits in this repository used letter-prefixed messages and disposable sample files from the course sandbox. Those practice files were removed so the current tree stays focused on learning notes rather than leftover exercise clutter.

## License

MIT. See [LICENSE](LICENSE).
