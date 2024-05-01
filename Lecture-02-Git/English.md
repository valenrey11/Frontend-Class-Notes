# 📚 Class 2: Topic "Git"

## 📁 Git
- Stores history of project.

## 🔑 SSH Authentication
- Two keys:
  1) Local (private, one per PC).
  2) Remote public (of remote repo).

## 🔄 Fetch vs Pull
- Fetch: Gets project history (all branches).
- Pull: Gets code changes (within branches).

## 📍 HEAD
- Points where you are in git history.
- Example: Could point to 3 commits before the last one.

## 🛠️ Three Stages
1) Working directory: Local changes.
2) Staging area: Modified files for future commit.
3) Commit history: Recorded changes.

## 🔧 Commands
- `branch`: Shows all branches (and current).
- `checkout`: Moves to commit hash or branch.
- `revert`: Creates new commit reverting the last one.
- `rebase`: Changes git history, moves commits between branches.
- `reset`: "Resets where HEAD points".
  - `hard`: Affects all stages.
  - `mixed`: Affects stages 1 & 2.
  - `soft`: Affects stage 1.
- `amend`: Changes commit name or adds staged files to last commit.
- `cherry pick`: Grabs arbitrary commit from one branch and moves it to another.

## 🔍 Tips
1) When connecting local to remote, avoid adding files at the beginning.
2) Always know who else is working on the feature branch to collaborate effectively.
