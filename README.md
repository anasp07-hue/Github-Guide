# Intro to Git & GitHub for CS Students

> **Your professor said "submit it on GitHub" and nobody showed you how.** This guide fixes that.

A short, skimmable beginner's guide to Git and GitHub: cloning, committing, pulling, pushing, branches, and pull requests. It includes diagrams, a cheatsheet, and "press for more detail" dropdowns so you can skim first and dig in only when you need to.

> [!IMPORTANT]
> **Start here.** New to Git? Follow the pages below in order. Trying to get one thing done? Use the table right below. Need a command fast? Go straight to the [Cheatsheet](info-vault/cheatsheet.md).

---

## What Do You Need to Do?

| I need to… | Go here |
|---|---|
| Set up Git on my computer (first time) | [One-Time Setup](info-vault/02-setup.md) |
| Get the starter code for an assignment | [Clone, Commit, Pull, Push → Step 1](info-vault/03-clone-commit-pull-push.md#step-1-get-the-repo-git-clone) |
| Upload / turn in my work | [Clone, Commit, Pull, Push → Step 5](info-vault/03-clone-commit-pull-push.md#step-5-upload-to-github-git-push) |
| Work on a group project | [Branches](info-vault/04-branches.md), then [Group Project Workflow](info-vault/05-pull-requests.md#group-project-workflow) |
| Fix an error I'm getting | [Fixing Common Problems](info-vault/06-fixing-common-problems.md) |
| Undo something | [Undoing Things](info-vault/06-fixing-common-problems.md#undoing-things) |

---

## Contents

| # | Page | What you'll learn | Time |
|---|------|-------------------|------|
| 1 | [What Are Git & GitHub?](info-vault/01-what-is-git-and-github.md) | The big picture, plus the words people keep using | 5 min |
| 2 | [One-Time Setup](info-vault/02-setup.md) | Install Git, sign in, and get ready to push | 10 min |
| 3 | [Clone, Commit, Pull, Push](info-vault/03-clone-commit-pull-push.md) | **The assignment workflow.** Start here if you're in a rush | 10 min |
| 4 | [Branches](info-vault/04-branches.md) | Work on something without breaking your main code | 8 min |
| 5 | [Pull Requests (PRs)](info-vault/05-pull-requests.md) | Propose changes, get feedback, and merge | 8 min |
| 6 | [Fixing Common Problems](info-vault/06-fixing-common-problems.md) | "Push rejected", merge conflicts, and other panics | 10 min |
| ⭐ | [**Cheatsheet**](info-vault/cheatsheet.md) | Every command on one page. Bookmark it! | n/a |

 Want the section-by-section breakdown and a "which pages should I read?" diagram? See the full **[Table of Contents](info-vault/00-Table%20of%20Contents.md)**.

---

## Get a Copy

You can read the guide right here on GitHub. To keep your own copy, clone it:

```bash
git clone https://github.com/anasp07-hue/Github-Guide.git
cd Github-Guide
```

> [!TIP]
> Don't have Git yet? Click the green **`<> Code`** button above → **Download ZIP**, then unzip it. (The guide's [Setup page](info-vault/02-setup.md) shows you how to install Git.)

---

## 👀 How to View It

The guide is plain Markdown (`.md`) files, so **any text editor works**. To see the diagrams and dropdowns properly, use one of these:

| | App | How to open the guide |
|---|---|---|
| **Recommended** | **Obsidian** | **Open folder as vault** → select the cloned folder. Start from **Table of Contents**, and open **Graph view** to see how the pages connect. |
| Works great | **VS Code** | **File → Open Folder** → select the cloned folder, open any `.md` file, then press `Cmd+Shift+V` (Mac) or `Ctrl+Shift+V` (Windows/Linux) for the preview. |

<details>
<summary><b>▶ Press for more detail: why Obsidian?</b></summary>

<br>

This repo is already set up as an Obsidian vault (that's the `.obsidian` folder). Opening it in Obsidian gives you:

- **Diagrams that just work.** Mermaid diagrams render without any plugins.
- **Graph view.** A color-coded map of all the pages and how they link together.
- **Clickable links** between pages, plus backlinks showing which pages link to the one you're on.

</details>

<details>
<summary><b>▶ Press for more detail: VS Code diagrams don't show up</b></summary>

<br>

VS Code's built-in preview doesn't draw Mermaid diagrams. Install the **Markdown Preview Mermaid Support** extension (link below), then reopen the preview.

</details>

### Quick Setup Links

**Obsidian**
- [Download Obsidian](https://obsidian.md/download) (free)
- [Obsidian Help: getting started](https://help.obsidian.md)

**VS Code**
- [Download VS Code](https://code.visualstudio.com/download) (free)
- [Markdown in VS Code](https://code.visualstudio.com/docs/languages/markdown) (how to use the preview)
- [Markdown Preview Mermaid Support](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-mermaid) (extension that draws the diagrams)

---

## What's Inside

```text
.
├── README.md                          ← you are here
├── .obsidian/                         ← Obsidian settings (graph colors, etc.)
└── info-vault/
    ├── 00-Table of Contents.md        ← full contents
    ├── 01-what-is-git-and-github.md
    ├── 02-setup.md
    ├── 03-clone-commit-pull-push.md
    ├── 04-branches.md
    ├── 05-pull-requests.md
    ├── 06-fixing-common-problems.md
    └── cheatsheet.md
```
