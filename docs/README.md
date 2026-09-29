# /docs

The minimal careers page. Plain HTML/CSS, no build step - open
`index.html` or serve the folder with anything (`python3 -m http.server`).

Our public website is under construction; until then this page is the
candidate-facing summary of the repository, and the repository itself is
our internal careers desk. Publishing: the repository is public and GitHub
Pages serves this folder (source: `/docs` on `main`) at
https://itamar-halevi.github.io/careers/ . Everything the page
links to lives under `/docs` so the published page is self-contained.

The markdown in `/roles`, `/apply`, and `/process` is where we work;
`/docs/roles` holds the published copies. When a role opens, closes, or
changes, update `/roles` first, then mirror the copy here and the one-line
entry in `index.html`. If they disagree, `/roles` wins - file an issue for
Tomer.
