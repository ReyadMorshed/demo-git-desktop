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
    Ans: C. The list of commits on the currently checked-out branch

12. **When you see “No local changes” in GitHub Desktop, what does it mean?**  
    A. Git is not installed  
    B. Your working directory matches the last commit on the current branch  
    C. There are untracked files only  
    D. Your repo is not connected to GitHub  
    Ans: Your working directory matches the last commit on the current branch

13. **Which action in GitHub Desktop corresponds to creating a local copy from a remote repository on GitHub?**  
    A. Add existing repository  
    B. Create a new repository  
    C. Clone a repository  
    D. Publish repository  
    Ans: C. Clone a repository

14. **You see a blue dot next to a branch name in GitHub Desktop’s branch list. What does it usually indicate?**  
    A. The branch is remote-only  
    B. The branch is protected  
    C. The branch has uncommitted changes  
    D. The branch is currently checked out  
    Ans: D. The branch is currently checked out

15. **In Git, what is the purpose of the `HEAD` pointer?**  
    A. It stores all commit messages  
    B. It points to the currently checked-out commit/branch  
    C. It points to the remote repository  
    D. It stores your username and email  
    Ans: B. It points to the currently checked-out commit/branch

16. **In GitHub Desktop, how can you discard changes in a specific file (revert it to last commit)?**  
    A. Delete the file manually from the OS  
    B. Right-click the file in the Changes list and select “Discard changes”  
    C. Press a “Reset repo” button  
    D. Commit with an empty message  
    Ans: B. Right-click the file in the Changes list and select “Discard changes”

17. **Which of the following is true about untracked files in Git?**  
    A. They are included in commits by default  
    B. They are files Git is not currently tracking; you must stage them to start tracking  
    C. They are stored only on GitHub  
    D. They are always ignored by `.gitignore`  
    Ans: B. They are files Git is not currently tracking; you must stage them to start tracking

18. **In GitHub Desktop, what does “Add existing repository” do?**  
    A. Creates a new repo on GitHub  
    B. Adds a local folder that already has a `.git` folder to GitHub Desktop’s list  
    C. Clones a repo from GitHub  
    D. Deletes a repo from disk  
    Ans: B. Adds a local folder that already has a `.git` folder to GitHub Desktop’s list

19. **You committed accidentally to the wrong branch in GitHub Desktop. What is a safe, typical way to move that commit to the correct branch?**  
    A. Delete the entire repo and start over  
    B. Use “Undo last commit” in GitHub Desktop, switch branches, then commit again  
    C. Force push to remote  
    D. It is impossible  
    Ans: B. Use “Undo last commit” in GitHub Desktop, switch branches, then commit again

20. **Which setting is important to configure (typically on first use of Git) for correct commit attribution?**  
    A. Default remote name  
    B. Username and password for GitHub Desktop only  
    C. Git user name and email (`user.name`, `user.email`)  
    D. Branch protection rules  
    Ans: C. Git user name and email (`user.name`, `user.email`)

21. **What does “Clone repository → URL” let you do in GitHub Desktop?**  
    A. Enter a URL to a GitHub profile and download all repos  
    B. Enter any valid Git repository URL (GitHub, GitLab, etc.) and clone it locally  
    C. Copy only `.gitignore` from a remote  
    D. Only works for GitHub Enterprise  
    Ans: B. Enter any valid Git repository URL (GitHub, GitLab, etc.) and clone it locally

22. **What is the main reason to create a `.gitignore` file when using GitHub Desktop?**  
    A. To prevent GitHub Desktop from opening the project  
    B. To prevent Git from tracking build artifacts, logs, and other unwanted files  
    C. To disable history for a repo  
    D. To block pull requests  
    Ans: B. To prevent Git from tracking build artifacts, logs, and other unwanted files

23. **In GitHub Desktop, what does “Open in Visual Studio Code” do?**  
    A. Clones the repo into VS Code  
    B. Opens the repo folder in VS Code as a project/workspace  
    C. Installs Git in VS Code  
    D. Only opens the last modified file  
    Ans: B. Opens the repo folder in VS Code as a project/workspace

24. **What happens if you try to push from GitHub Desktop when your local branch is behind the remote branch?**  
    A. Push will always succeed  
    B. GitHub Desktop will force push automatically  
    C. GitHub Desktop will ask you to pull first, then push after resolving any conflicts  
    D. Your local commits will be lost  
    Ans: C. GitHub Desktop will ask you to pull first, then push after resolving any conflicts

25. **Which statement about branches and pull requests on GitHub is correct?**  
    A. You can only create a pull request from `main`  
    B. A pull request merges changes from one branch into another, usually after review  
    C. You don’t need branches; pull requests work only on local commits  
    D. A pull request deletes the source branch automatically  
    Ans: B. A pull request merges changes from one branch into another, usually after review

---

## Section 2 – Short Answer / Explanation (Git + GitHub Basics)

### 1. Difference between:

- **Working directory**  
  The actual files and folders on your computer that you are editing.  
  Represents the current state of your project (including untracked and modified files).

- **Staging area (Index)**  
  A “holding zone” where you mark changes that should be included in the next commit.  
  You selectively add files here using `git add`.

- **Local repository**  
  The hidden `.git` folder that stores the full history of commits, branches, and metadata.  
  It’s where Git permanently records changes once you commit.

---

### 2. Problem version control solves

- Tracks changes over time, allowing rollback to earlier versions.
- Enables collaboration without overwriting each other’s work.
- Provides accountability (who changed what, when, and why).
- Supports branching/merging for parallel development.

---

### 3. Difference between `git clone` and GitHub fork

- **`git clone`**: Creates a local copy of an existing remote repository (any Git server).
- **Fork**: Creates a _new copy_ of someone else’s repository under your GitHub account, so you can modify independently and propose changes back via pull requests.
- Forks are GitHub-specific; cloning is a general Git operation.

---

### 4. Importance of good commit messages

1. Helps teammates (and your future self) understand _why_ a change was made.
2. Makes debugging and reviewing history easier, especially when tracking down bugs or regressions.

---

### 5. Pull vs Fetch

- **Pull**: Downloads changes from the remote and _merges_ them into your current branch.
- **Fetch**: Downloads changes from the remote but does **not** merge; you can inspect them first.
- Pull = Fetch + Merge.

---

### 6. Merge conflict

- Happens when Git cannot automatically reconcile differences between two branches.
- Example: Two people edit the same line in a file differently.
- Requires manual resolution before completing the merge.

---

### 7. Purpose of a Pull Request (PR) review

- Ensures code quality through peer review.
- Allows discussion, suggestions, and approval before merging.
- Acts as a checkpoint for collaboration, catching bugs or design issues early.

---

### 8. Why avoid working directly on `main`/`master`

- Keeps the main branch stable and production-ready.
- Prevents accidental breaking changes from being pushed.
- Encourages feature branches, which isolate work and make collaboration/review easier.

---

## Section 2 – Extra Short Answer Questions (Concepts + Desktop Workflow)

### 9. Difference between a local repository and a remote repository

- **Local repository**: Stored on your computer; where you make changes, commits, and test code.
- **Remote repository**: Hosted on a server (e.g., GitHub); acts as a shared version accessible to collaborators.

---

### 10. Reasons GitHub Desktop says a folder is not a Git repository

- The folder does not contain a `.git` directory (Git was never initialized).
- The folder is empty or only contains files but has not been set up with `git init`.

---

### 11. Difference between “Commit to main” and “Push origin”

- **Commit to main**: Saves changes to your local repository’s main branch.
- **Push origin**: Uploads those local commits to the remote repository on GitHub.

---

### 12. Viewing changes before committing

- In GitHub Desktop, select the file in the **Changes** tab.
- The app shows a **diff view** highlighting added (green) and removed (red) lines.

---

### 13. Using “Undo last commit”

- Used when you realize the last commit message or included changes were incorrect.
- It removes the commit from history but keeps the changes staged, allowing you to recommit properly.

---

### 14. Typical workflow to fix a bug using a feature branch

1. Create a new branch from `main` (e.g., `bugfix/issue-123`).
2. Make code changes to fix the bug.
3. Commit changes locally.
4. Push the branch to GitHub.
5. Open a Pull Request to merge the fix into `main`.
6. After review, merge and delete the feature branch.

---

### 15. Safe options when switching branches with uncommitted changes

- **Commit the changes** on branch A before switching.
- **Stash the changes** so they can be reapplied later.
- **Discard changes** if they are not needed.

---

### 16. Risks of force push (`git push --force`)

- It rewrites history on the remote repository.
- Can overwrite teammates’ commits, causing data loss or confusion.
- GitHub Desktop avoids it to maintain safe, collaborative workflows.

---

### 17. Information shown in the History tab for each commit

- Commit message.
- Author name and avatar.
- Date and time of commit.
- List of changed files with diffs.

---

### 18. Cloning a repository from an organization

- In GitHub Desktop, choose **File → Clone Repository**.
- Select the **Organization tab** instead of personal repositories.
- Pick the repository from the organization list and clone it locally.

---

## Section 3 – GitHub Desktop–Focused Scenarios

### 1. Creating a commit and pushing it to GitHub

1. Open GitHub Desktop and ensure the correct repository is selected.
2. In the **Changes** tab, review the modified files.
3. Optionally, check/uncheck files to include/exclude them from the commit.
4. Write a **summary** (required) and **description** (optional) for the commit.
5. Click **Commit to main** (or the current branch).
6. After committing, click **Push origin** to send the commit to GitHub.

---

### 2. Commit visible locally but not on GitHub

- You likely forgot to **Push origin** after committing.  
  Committing only saves changes locally; pushing uploads them to GitHub.

---

### 3. Switching to a different branch

1. In GitHub Desktop, go to the **Current Branch** dropdown at the top.
2. Select the branch you want to switch to from the list.
3. If the branch doesn’t exist locally, choose **Choose a branch to merge into current branch** or **New Branch** to create one.

---

### 4. Meaning of Fetch, Pull, and Push origin

- **Fetch origin**: Downloads information about new commits from the remote without merging them into your local branch.
- **Pull origin**: Fetches and merges commits from the remote branch into your local branch.
- **Push origin**: Uploads your local commits to the remote repository on GitHub.

---

## Section 3 – Extra Scenario-Based Questions (Desktop + Real-World Problems)

### 5. Missing changes after cloning at home

- You may have committed locally but **forgot to push** the changes from your office computer.
- The remote repo doesn’t have your latest commits, so cloning at home shows the older state.

---

### 6. Teammate doesn’t see changes after pulling

- They might be on the wrong branch (e.g., not on `main`).
- They may not have pulled from the correct remote (e.g., pulling from their fork instead of the shared repo).
- They could have local conflicts preventing the pull from completing.

---

### 7. Checking out a PR branch locally

1. In GitHub Desktop, go to the **Branch** menu.
2. Select **Choose a branch to checkout**.
3. Look under the **Pull Requests** section.
4. Select the PR branch to check it out locally and test.

---

### 8. Excluding log files and build artifacts

1. Add the file patterns (e.g., `*.log`, `build/`) to a `.gitignore` file in the repo.
2. Commit the updated `.gitignore`.
3. If the files were already tracked, remove them from Git with `git rm --cached <file>` (or use GitHub Desktop’s “Discard changes” after untracking).
4. They will no longer appear in the Changes tab.

---

### 9. Publishing a local repo to GitHub

1. Open GitHub Desktop and select the local repository.
2. Click **Publish repository** in the top bar.
3. Fill in details such as repository name, description, and visibility (public/private).
4. Click **Publish Repository** to push it to GitHub for backup.

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
   - Modify `README.md` (for example, add a new section). (adding this line for new branch)
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
