Assignment 4 — Repository with at least three meaningful commits

Objective

Create a Git repository and learn how to make at least three meaningful commits.

Answer

1. Git Identity Setup

git config --global user.name "Nitesh"
git config --global user.email "niteshkumarshakya15@gmail.com"

2. Repository Setup

git init
git branch -M main

3. Commit 1 — Add README

echo "# HTML & CSS Assignments" > README.md
git add README.md
git commit -m "docs: add README"

4. Commit 2 — Add Assignment Files

git add 01-*.md 02-*.md 03-*.md 04-*.md 05-*.md
git commit -m "docs: setup & git assignments (1-5)"

5. Commit 3 — Add HTML Assignment Files

git add 06-*.html 07-*.html 08-*.html 09-*.html 10-*.html
git commit -m "feat: HTML basics assignments (6-10)"

6. View Commit History

git log --oneline

Good Commit Message Rules

- Use present tense and imperative wording.
- Use prefixes such as "feat:", "fix:", "docs:", "style:", and "refactor:".
- Keep one logical change per commit.

Result

Learned how to stage files, create meaningful commits, and view Git commit history.