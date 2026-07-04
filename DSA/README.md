<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:2b1d0e,100:8B5E3C&height=200&section=header&text=DSA%20Corner&fontSize=55&fontColor=FFFFFF&animation=fadeIn&fontAlignY=38&desc=Data%20Structures%20%26%20Algorithms%2C%20one%20PR%20at%20a%20time&descAlignY=58&descSize=17)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=8B5E3C&center=true&vCenter=true&width=650&lines=Pick+a+problem.+Solve+it.+Submit+it.;Arrays.+Trees.+Graphs.+Dynamic+Programming.;Every+solution+lives+in+its+own+folder.;No+solution+is+too+small+to+share.)](https://git.io/typing-svg)

![Language](https://img.shields.io/badge/Language-Python-8B5E3C?style=for-the-badge&logo=python&logoColor=white&labelColor=2b1d0e)
![Problems](https://img.shields.io/badge/Problems-Growing-C4A484?style=for-the-badge&labelColor=2b1d0e)
![Contributors Welcome](https://img.shields.io/badge/Contributors-Welcome-brightgreen?style=for-the-badge&labelColor=2b1d0e)

</div>

## 📖 What This Is

This is the DSA corner of the [coffee-and-code](../README.md) repo. It's a shared bank of Data Structures and Algorithms problems where anyone can practice solving them and submit their own solution next to everyone else's. Think of it as a group LeetCode session that lives in Git history instead of disappearing after you close the tab.

You don't need to be fast, and you don't need to get it right the first time. Push your solution, get feedback, push again.

## 🗺️ Table of Contents

- [Folder Structure](#-folder-structure)
- [Naming Convention](#-naming-convention)
- [How to Solve a Problem](#-how-to-solve-a-problem)
- [How to Add a New Problem](#-how-to-add-a-new-problem)
- [Difficulty Legend](#-difficulty-legend)
- [Contribution Workflow](#-contribution-workflow)
- [Code Style](#-code-style)

## 📁 Folder Structure

```
DSA/
├── README.md
├── problems/
│   ├── 001-two-sum.py
│   ├── 002-reverse-linked-list.py
│   └── 003-binary-search.py
├── ik-awais/
│   ├── 001-two-sum.py
│   └── 002-reverse-linked-list.py
├── syed-shayan-rizvi/
│   └── 001-two-sum.py
└── <your-github-username>/
    └── (your solutions go here)
```

- **`problems/`** holds the actual problem statements. Each file is the source of truth for what needs to be solved.
- **Every contributor gets their own top-level folder**, named after their GitHub username, sitting right beside `problems/`.
- Inside your folder, your solution file must share the exact same name as the problem it solves.

## 🏷️ Naming Convention

This is the one rule that keeps this whole folder from turning into chaos: **your solution file name must match the problem file name, character for character.**

<div align="center">

| Location | File |
|----------|------|
| Problem | `DSA/problems/004-valid-parentheses.py` |
| Your solution | `DSA/<your-username>/004-valid-parentheses.py` |

</div>

If the problem is `004-valid-parentheses.py`, your solution is also `004-valid-parentheses.py`, just sitting in your own folder instead of `problems/`. That's what lets anyone browse the repo and instantly see who's solved what.

## 🧩 How to Solve a Problem

1. Browse [`problems/`](problems) and pick one that looks interesting (or intimidating, that works too)
2. Open the problem file to read the statement, constraints, and any starter code or examples
3. Create your own folder if you don't already have one: `DSA/<your-github-username>/`
4. Write your solution in a file with the **same exact name** as the problem file
5. Test it locally before you commit
6. Open a pull request

<details>
<summary><b>Example walkthrough</b> (click to expand)</summary>

<br>

Say `DSA/problems/012-merge-intervals.py` looks fun. Here's what you'd do:

```bash
git checkout -b dsa/012-merge-intervals
mkdir -p DSA/your-username
touch DSA/your-username/012-merge-intervals.py
# write your solution
git add DSA/your-username/012-merge-intervals.py
git commit -m "Add solution for 012-merge-intervals"
git push origin dsa/012-merge-intervals
```

Then open a PR against `main`. Someone will review it, maybe suggest a cleaner approach, and merge it in.

</details>

## ➕ How to Add a New Problem

Want to contribute a problem instead of just a solution? That's just as welcome.

1. Pick the next available number in sequence, don't reuse an existing one
2. Add a file to `problems/` named `<number>-<short-problem-name>.py`
3. Include a clear docstring at the top with the problem statement, input and output format, and at least one example
4. Tag the difficulty in a comment (see the legend below)
5. Open a PR titled something like `Add problem: 015-course-schedule`

## 🎚️ Difficulty Legend

![Easy](https://img.shields.io/badge/Easy-brightgreen?style=flat-square)
![Medium](https://img.shields.io/badge/Medium-yellow?style=flat-square)
![Hard](https://img.shields.io/badge/Hard-red?style=flat-square)

Tag every problem file with one of these in a comment near the top, so people can filter by how much pain they're in the mood for.

## 🔁 Contribution Workflow

Same Git etiquette as the rest of the repo, just scoped to this folder:

- Branch naming: `dsa/<problem-code>` (e.g. `dsa/007-lru-cache`)
- Commit messages: present tense, specific (`Add solution for 007-lru-cache`, not `update`)
- One problem per PR keeps reviews fast and focused
- Link the problem file in your PR description so reviewers know exactly what you solved

## 🧹 Code Style

- Keep solutions in Python for now, to keep things comparable across contributors
- Name your function something that describes what it does, not just `solve()`
- A short comment on your approach (brute force, two pointers, DP, whatever) helps reviewers and future you
- If you found a more optimal approach after your first pass, feel free to add both and note the trade-off

---

<div align="center">

**Every problem solved here is one less surprise in an interview.** 🧠☕

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:8B5E3C,100:2b1d0e&height=120&section=footer)

</div>