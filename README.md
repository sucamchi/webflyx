# WebFlyx

![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![Boot.dev](https://img.shields.io/badge/Boot.dev-Learn%20Git-7B3FE4)

A practice repository from the [Boot.dev](https://www.boot.dev) course
**"Learn Git"**. The content is a pretend movie catalogue for a streaming
service called WebFlyx; the real point is the commit history, which was
built step by step while learning Git.

## What's inside

| File | Content |
|------|---------|
| `contents.md` | An index of the repository |
| `titles.md` | Movie titles in the collection |
| `classics.csv` | Classic movies with director and year |
| `quotes/` | Memorable quotes from *Dune* and *Star Wars* |

## Reading the history

The commits are lettered in the order the course asked for them (`A:`,
`B:`, `C:`...), so `git log` doubles as a record of each lesson:

```bash
git log --oneline --graph --all
```

You can see a feature branch (`add_classics`) being created, merged back
into `main` both locally and through a pull request, and changes pulled in
from a second remote.

## What I learned

- The basic loop: `git add`, `git commit`, `git status`, `git log`
- How Git stores snapshots, and what a commit hash points to
- Configuring Git (`git config`) with my name, email and default branch
- Creating and switching branches, and merging them (fast-forward vs. merge
  commit)
- Working with remotes: `git remote`, `git push`, `git pull`, `git fetch`
- Opening and merging a pull request on GitHub
- Writing small commits with clear messages so the history tells a story

## Resources

- [Boot.dev: Learn Git](https://www.boot.dev/courses/learn-git)
