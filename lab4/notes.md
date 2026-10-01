Q1. `--global` here means for all repositories on my system use this username and email. If left out, different usernames and emails could be given for different repositories.

Q2. In `ls -a`, all files are shown, including hidden files, not just the normal ones. (`ls -a` means list all.)

Q3. Only 1 file is being offered to track, and there is nothing in the list that I did not write.

Q4. `.gitignore` ignores the files and folders added to it, so the `.venv/`, `__pycache__/`, `.pyc` files and `.DS_Store` no longer appear in `git status`.

Q5. `.gitignore` should be committed because it is part of the project's configuration and tells Git what files to ignore.

Q6. `README.md` moved from "Changes not staged for commit" to "Changes to be committed". This means it moved from the working directory to the staging area after `git add`.

Q7. Git printed the commit information, including the commit hash, branch and commit message. It also said how many files were changed.

Q8. The first seven characters are the short version of the commit hash. They identify that specific commit in the Git history.

Q9. The four steps are edit the files, check the changes with `git status`, stage the changes with `git add`, and commit them with `git commit`.

Q10. `README.md` is a standard special file that gives information about the project. GitHub automatically displays it on the repository's front page.

Q11. `gh auth login` authenticates my GitHub account in the terminal and saves the authentication credentials, so GitHub does not ask for my password every time I push.

Q12. The `README.md` is showing on the front page because GitHub automatically renders the README as the main description of the repository.

Q13. No, pushing did not change my local history. It only uploaded my existing commits to GitHub.

Q14. A private repository exists on GitHub but only people with permission can access it. If a repository does not exist on GitHub, there is no online repository to access at all.
