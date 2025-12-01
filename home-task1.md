# Git & GitHub (with GitHub Desktop) – Home Task Questions

---

## Section 1 – Core Git Concepts (MCQs)

1. **What is Git?**  
   A. A code editor  
   B. A distributed version control system  
   C. A hosting service for repositories  
   D. A continuous integration tool  
   Ans: B. A distributed version control system

2. **What is GitHub?**  
   A. A programming language  
   B. A GUI editor for Git  
   C. A cloud platform to host Git repositories and collaborate  
   D. A desktop app for Git
   Ans: C. A cloud platform to host Git repositories and collaborate

3. **Which of the following best describes a commit?**  
   A. A backup of your entire computer  
   B. A named pointer to a branch  
   C. A snapshot of changes in your repository at a point in time  
   D. A list of remote repositories  
   Ans: C. A snapshot of changes in your repository at a point in time

4. **In Git, what is a branch?**  
   A. A copy of your operating system  
   B. A pointer to a particular commit line, often used for separate lines of development  
   C. A list of commits  
   D. A remote backup of your code  
   Ans: B. A pointer to a particular commit line, often used for separate lines of development

5. **What does the `origin` usually refer to?**  
   A. Your local branch name  
   B. Your main remote repository (often on GitHub)  
   C. Your staging area  
   D. Your working directory  
   Ans: B. Your main remote repository (often on GitHub)

6. **What is the purpose of `.gitignore`?**  
   A. To ignore remote branches  
   B. To ignore specific local folders that contain Git  
   C. To list files and directories Git should not track  
   D. To hide commits from history  
   Ans: C. To list files and directories Git should not track

7. **Which of the following is the correct order in a typical Git workflow?**  
   A. Push → Commit → Modify files → Pull  
   B. Modify files → Commit → Push  
   C. Clone → Push → Commit  
   D. Commit → Modify files → Pull  
   Ans: B. Modify files → Commit → Push

8. **If you clone a repository from GitHub to your machine, what do you get?**  
   A. Only the latest commit  
   B. Only the main branch  
   C. A full copy of the repository (commits, branches, etc.) at that time  
   D. Only untracked files  
   Ans: C. A full copy of the repository (commits, branches, etc.) at that time

9. **What is a pull request (PR) on GitHub?**  
   A. A direct push of commits to `main`  
   B. A request to copy files to your local machine  
   C. A request to merge changes from one branch into another, usually with code review  
   D. A way to delete a remote branch  
   Ans: C. A request to merge changes from one branch into another, usually with code review

10. **Which statement is TRUE about local commits and GitHub?**  
    A. Once you commit locally, your changes are automatically on GitHub.  
    B. Local commits are only on your machine until you push them to the remote.  
    C. Git does not allow local commits without internet.  
    D. You must create a new repo for every commit.  
    Ans: B. Local commits are only on your machine until you push them to the remote.

---

### Section 1 – Extra MCQs (Git + GitHub Desktop)

11. **In GitHub Desktop, what does the History tab show?**  
    A. Only remote commits  
    B. Only untracked files  
    C. The list of commits on the currently checked-out branch  
    D. All branches and their commits at once

12. **When you see “No local changes” in GitHub Desktop, what does it mean?**  
    A. Git is not installed  
    B. Your working directory matches the last commit on the current branch  
    C. There are untracked files only  
    D. Your repo is not connected to GitHub

13. **Which action in GitHub Desktop corresponds to creating a local copy from a remote repository on GitHub?**  
    A. Add existing repository  
    B. Create a new repository  
    C. Clone a repository  
    D. Publish repository

14. **You see a blue dot next to a branch name in GitHub Desktop’s branch list. What does it usually indicate?**  
    A. The branch is remote-only  
    B. The branch is protected  
    C. The branch has uncommitted changes  
    D. The branch is currently checked out

15. **In Git, what is the purpose of the `HEAD` pointer?**  
    A. It stores all commit messages  
    B. It points to the currently checked-out commit/branch  
    C. It points to the remote repository  
    D. It stores your username and email

16. **In GitHub Desktop, how can you discard changes in a specific file (revert it to last commit)?**  
    A. Delete the file manually from the OS  
    B. Right-click the file in the Changes list and select “Discard changes”  
    C. Press a “Reset repo” button  
    D. Commit with an empty message

17. **Which of the following is true about untracked files in Git?**  
    A. They are included in commits by default  
    B. They are files Git is not currently tracking; you must stage them to start tracking  
    C. They are stored only on GitHub  
    D. They are always ignored by `.gitignore`

18. **In GitHub Desktop, what does “Add existing repository” do?**  
    A. Creates a new repo on GitHub  
    B. Adds a local folder that already has a `.git` folder to GitHub Desktop’s list  
    C. Clones a repo from GitHub  
    D. Deletes a repo from disk

19. **You committed accidentally to the wrong branch in GitHub Desktop. What is a safe, typical way to move that commit to the correct branch?**  
    A. Delete the entire repo and start over  
    B. Use “Undo last commit” in GitHub Desktop, switch branches, then commit again  
    C. Force push to remote  
    D. It is impossible

20. **Which setting is important to configure (typically on first use of Git) for correct commit attribution?**  
    A. Default remote name  
    B. Username and password for GitHub Desktop only  
    C. Git user name and email (`user.name`, `user.email`)  
    D. Branch protection rules

21. **What does “Clone repository → URL” let you do in GitHub Desktop?**  
    A. Enter a URL to a GitHub profile and download all repos  
    B. Enter any valid Git repository URL (GitHub, GitLab, etc.) and clone it locally  
    C. Copy only `.gitignore` from a remote  
    D. Only works for GitHub Enterprise

22. **What is the main reason to create a `.gitignore` file when using GitHub Desktop?**  
    A. To prevent GitHub Desktop from opening the project  
    B. To prevent Git from tracking build artifacts, logs, and other unwanted files  
    C. To disable history for a repo  
    D. To block pull requests

23. **In GitHub Desktop, what does “Open in Visual Studio Code” do?**  
    A. Clones the repo into VS Code  
    B. Opens the repo folder in VS Code as a project/workspace  
    C. Installs Git in VS Code  
    D. Only opens the last modified file

24. **What happens if you try to push from GitHub Desktop when your local branch is behind the remote branch?**  
    A. Push will always succeed  
    B. GitHub Desktop will force push automatically  
    C. GitHub Desktop will ask you to pull first, then push after resolving any conflicts  
    D. Your local commits will be lost

25. **Which statement about branches and pull requests on GitHub is correct?**  
    A. You can only create a pull request from `main`  
    B. A pull request merges changes from one branch into another, usually after review  
    C. You don’t need branches; pull requests work only on local commits  
    D. A pull request deletes the source branch automatically

---

## Section 2 – Short Answer / Explanation (Git + GitHub Basics)

1. **Explain the difference between:**

   - Working directory
   - Staging area
   - Local repository

2. **What problem does version control (like Git) solve for developers and teams?**

3. **What is the difference between `git clone` and a GitHub fork?**

4. **Why is writing a good commit message important? Give two reasons.**

5. **What does it mean to “pull” from a remote repository? How is it different from “fetch”?**

6. **What is a merge conflict and when does it happen?**

7. **In GitHub, what is the purpose of a Pull Request (PR) review (comments, approvals, etc.)?**

8. **Why is it a good idea not to work directly on the `main`/`master` branch for every change?**

---

### Section 2 – Extra Short Answer Questions (Concepts + Desktop Workflow)

9. **In your own words, describe the difference between a local repository and a remote repository.**

10. **You created a new project folder, opened GitHub Desktop, and chose “Add existing repository”, but GitHub Desktop says it does not appear to be a Git repository. What are two possible reasons for this?**

11. **Explain the difference between “Commit to main” and “Push origin” in GitHub Desktop.**

12. **How can you see what changed in a file before you commit it using GitHub Desktop?**

13. **When would you use “Undo last commit” in GitHub Desktop, and what does it do?**

14. **Describe a typical workflow to fix a bug using a feature branch and GitHub Desktop.**

15. **Suppose you have uncommitted changes on branch A, but you need to switch to branch B in GitHub Desktop. What safe options do you have?**

16. **Why is it risky to use force push (`git push --force`) and why does GitHub Desktop usually avoid it for normal workflows?**

17. **What information do you typically see for each commit in the History tab of GitHub Desktop?**

18. **How can you clone a repository from GitHub if it belongs to your organization and not your personal account?**

---

## Section 3 – GitHub Desktop–Focused Scenarios

1. **You have modified several files in your local repository.**  
   Describe the exact steps in GitHub Desktop to create a commit and push it to GitHub.

2. **You committed your changes in GitHub Desktop, but when you check GitHub in the browser, you don’t see your latest commit.**  
   What step did you likely forget?

3. **How do you switch to a different branch in GitHub Desktop?**  
   Describe the steps.

4. **You see a “Fetch origin” button in GitHub Desktop. Sometimes it changes to “Pull origin” or “Push origin”.**  
   Explain what each of these means:
   - Fetch origin
   - Pull origin
   - Push origin

---

### Section 3 – Extra Scenario-Based Questions (Desktop + Real-World Problems)

5. **You pushed code to GitHub yesterday from your office computer using GitHub Desktop. Today, you cloned the same repo at home but your latest changes are missing. What likely went wrong?**

6. **A teammate complains they don’t see your changes in their local repo even after pulling `main`. On GitHub, your commit is visible. What might they be doing wrong?**

7. **You are reviewing a pull request on GitHub and want to test it locally using GitHub Desktop. How can you check out the PR branch locally?**

8. **Your repo has large log files and build artifacts that you don’t want to track in Git. They already appear in the Changes tab. What steps should you take so they are no longer tracked or shown there?**

9. **You created a repo locally in GitHub Desktop but forgot to Publish it. Later, you want to push it to GitHub for backup. What steps do you take in GitHub Desktop to publish it?**

---

## Section 4 – Practical / Hands-On Tasks (GitHub Desktop Oriented)

1. **Task 1 – Create a Local Repo and Publish to GitHub**  
   Using GitHub Desktop:

   - Create a new local repository called `demo-git-desktop`.
   - Add a file `README.md` with a short description.
   - Commit the change.
   - Publish the repository to your GitHub account using GitHub Desktop.

2. **Task 2 – Create a Branch, Make a Change, and Open a Pull Request**  
   Using GitHub Desktop and GitHub (web):

   - Create a new branch called `feature-update-readme` from `main`.
   - Modify `README.md` (for example, add a new section).
   - Commit the change on `feature-update-readme`.
   - Push the branch to GitHub.
   - Open a Pull Request on GitHub to merge `feature-update-readme` into `main`.

3. **Task 3 – Update Local Branch from Remote (Pull Changes)**  
   Scenario: Another teammate has merged changes into `main` on GitHub.

   - Describe the steps in GitHub Desktop to update your local `main` branch so it matches the remote `main`.

4. **Task 4 – Handling a Simple Merge Conflict in GitHub Desktop**  
   Scenario:

   - On GitHub (web), you edit `README.md` on `main` and commit the change.
   - Locally, on branch `main`, you edit the same lines in `README.md` differently and commit using GitHub Desktop.
   - When you try to push, Git requires you to pull first and a merge conflict occurs.

   **Question:**

   - Describe the steps you would follow in GitHub Desktop and your editor to resolve this merge conflict and successfully push the final merged version to GitHub.

---
