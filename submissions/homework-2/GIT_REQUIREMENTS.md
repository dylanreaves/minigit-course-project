# Homework 2 — Part 2 Submission

Student name: Dylan Reaves

GitHub username: dylanreaves

## 1. Git Command Observations

| Command or workflow | What did you observe? | What was the user trying to accomplish? | What problem or risk did it address? |
|---|---|---|---|
| 1. git status | The command shows the current branch and whether the working tree has modified or staged files. | The user was trying to understand the current state of their local work before performing another action. | It reduced the risk of the user forgetting about the files they changed or accidentally committing the wrong work. |
| 2. git diff | The command displays the exact line changes that were made to files that have not been staged. | The user was trying to review what the exact lines of a file to see what they had changed. | It helps verify what exact changes occurred in a file which helps the user avoid accidental or incomplete edits before they commit. |
| 3. git add `<file>`| The command adds selected files to the staging area which designates files that will be included in the next commit. | The user was trying to select what work they had completed and should be prepared to be included in the next commit. | It reduces the risk of accidently committing changes that weren't intended to be committed. |
| 4. git commit | The command creates a new snapshot of the staged changes with a message to describe the changes made. This new snapshot is then added to the project history and can be viewed again at any point. | The user was trying to preserve a meaningful checkpoint with a description that describes the current version of the project at that point in time. | It prevented completed work from existing as temporary edits and helps the user better understand the collection of changes between previous versions. |

## 2. User Needs

### UN-GIT-01 — Project Status Awareness

> A contributor needs a way to understand the current state of their local project because they need to know which changes are new, currently selected, or already preserved before committing.

### UN-GIT-02 — Controlled Change Selection

> A contributor needs a way to choose and verify exactly what changed files should be included in the next project version because some work may be incomplete or unrelated.

### UN-GIT-03 — Version History

> A contributor needs a way to preserve, review and access previous project versions, because they need to understand how the project changed over time and also potentially need to restore their project back to a previous state if needed.

## 3. User Requirements

| ID and short title | User requirement | Source user need | Rationale |
|---|---|---|---|
| UR-GIT-01: View Project Status | A contributor shall be able to view the current state of their project and identify which files have been changed or selected for the next project version. | UN-GIT-01 | The contributor needs to understand the current state of their work before deciding what action to take next. |
| UR-GIT-02: Review Changes | A contributor shall be able to review the changes made to project files before those changes are preserved in a new project version. | UN-GIT-01 | Reviewing changes allows the contributor to identify accidental or incomplete edits before preserving them. |
| UR-GIT-03: Select Changes | A contributor shall be able to select specific changed files to include in the next project version without including unrelated changes. | UN-GIT-02 | The contributor needs to be able to control what work is included so incomplete or unrelated changes are not preserved accidentally. |
| UR-GIT-04: Preserve and Review Versions | A contributor shall be able to save a project version with a description and later review previously saved versions. | UN-GIT-03 | Saving and reviewing versions allows the contributor to track the project's progress and understand how it has changed over time. |

