# DevOps Internship Task 3 - Git Workflow Documentation

## Objective
To manage a DevOps project using Git best practices, including branching, Pull Requests (PRs), and tagging.

## Implementation Steps

### 1. Repository Setup (a, e, d)
* Initialized the repository locally and pushed to GitHub.
* Created a **.gitignore** file to exclude Python caches and virtual environments.
* Added a **README.md** for project overview.

### 2. Branching Strategy (b)
* Created and maintained three core branches:
    * **master**: The stable, production-ready code.
    * **dev**: The integration branch for code stability checks (currently behind `master` in this run).
    * **feature/add-script-logic**: The working branch for new development.

### 3. Feature Development and Integration (c)
* Development was isolated on the **feature/add-script-logic** branch.
* A **Pull Request (PR #1)** was created to merge the feature into **master**.
* The feature was merged via the PR, ensuring review and control before integration.

### 4. Release and Tagging (e)
* After the feature was confirmed stable on `master`, a release marker (**v1.0.0**) was applied using an **annotated tag**.

## Conclusion
This workflow ensures code is developed in isolation, reviewed via PRs, and stable points are marked for release.
