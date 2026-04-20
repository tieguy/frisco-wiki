# frisco-wiki

Content for https://frisco.wiki — structured subjects and prose articles.

## Layout

- `subjects/*.yaml` — structured claims about people, places, institutions,
  and events. Each subject owns its own claims and sources.
- `articles/*.md` — prose views that reference subjects. Markdown footnotes
  cite sources defined on the referenced subjects.

This repo holds no build tooling or application code. It is consumed by the
[friski-code](https://github.com/tieguy/friski-code) repository as a git
submodule. See that repo's design plan and CLAUDE.md for the authoring
workflow and schema.
