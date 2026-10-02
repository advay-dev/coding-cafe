1. --global: It applies the setting to every repository for your user account (stored in ~/.gitconfig). Omitting it applies the setting only to the current repository (stored in .git/config).

2. Contents of .git: It holds the repository's entire history and metadata: HEAD, config, objects/, refs/, hooks/, info/, description, and index once you've staged something. Deleting it removes all version history and leaves just plain files.

3. Untracked files: 6. Untracked code is any file listed there: Git sees it but isn't recording its changes yet.

4. git status after .gitignore: Files and folders matching the ignore patterns disappear from the untracked list, so the output gets much shorter. .gitignore itself shows up as a new untracked file.

5. Committing .gitignore: Committing it shares the same ignore rules with everyone who clones the repo, which keeps junk and secrets out consistently. If it were ignored, the rules would exist only on your machine.

6. README.md movement: It starts under "Untracked files" (working directory), then moves to "Changes to be committed" after git add (staging area). After git commit it vanishes from the status output because it's now in the repository and the working tree is clean.

7. git commit output: [main (root-commit) 5fad48f] Lab work so far
 7 files changed, 2013 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 README.md
 create mode 100644 week02/lab01-log.txt
 create mode 100644 week02/notes.md
 create mode 100644 week04/lab2_cc_2026.ipynb
 create mode 100644 week06/lab3.ipynb
 create mode 100644 week07/lab4notes.md

8. First seven characters: This is the short hash (mine: 5fad48f). It's a compact, unique-enough identifier for referring to a commit in commands like git show or git checkout.

9. 