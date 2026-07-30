# English

## Git Workflow

### Purpose

For this System Engineering portfolio project, Design and Validation of a Smart Home Security System, I use Git to manage project artifacts, track changes, and document my engineering process.

My goal is to maintain a stable project baseline while keeping ongoing work organized and traceable throughout the project lifecycle.

### Workflow Decision

Before starting the project, I initialize a Git repository and create a clear folder structure consisting of README, docs, diagrams, models, and notes.

I keep the complete and current version of the project in the main branch.

For each major project activity, such as System Requirements Specification, System Architecture, Trade-off Evaluation, and Verification & Validation, I create a separate temporary feature branch.

I complete the related work in the feature branch and create commits to document important progress and engineering decisions. Once the activity is finished, I merge the branch into main and delete the feature branch.

### Why I Choose This Approach

#### Repository Initialization

I initialize the repository before starting the project so that the entire engineering process is tracked from the beginning. This allows me to maintain a complete history of project decisions, changes, and improvements.

#### Clear Folder Structure

- I create a structured folder hierarchy to keep project artifacts organized and easy to navigate.
- The README serves as the project's landing page and provides an overview of the project objectives, scope, and repository structure.
- The docs folder contains engineering documents and specifications.
- The diagrams folder stores architecture and design diagrams.
- The models folder contains system models and analysis artifacts.
- The notes folder contains learning notes, observations, and project reflections.
- This structure makes the repository easier to understand, maintain, and review.

#### Main Branch as the Single Source of Truth

- I use the main branch as the single source of truth because it always represents the latest completed and integrated version of the project.
- Anyone reviewing the repository can look at the main branch and immediately understand the current state of the project.

#### Feature Branch Workflow
- I use feature branches to isolate unfinished work from the stable project version.
This allows me to work on requirements, architecture, trade-off studies, and verification activities without affecting the stable baseline stored in main.

#### Temporary Feature Branches
- Feature branches are temporary and only exist while a specific activity is being developed.
- After the work is merged into main, I delete the feature branch because its purpose has been completed.
- I do not keep permanent branches for individual documents or activities because the completed work already exists in main. Permanent branches can become outdated over time, require additional synchronization effort, increase repository complexity, and make project management more difficult.
- Deleting a feature branch after merging does not delete the completed files. The changes already exist in the main branch and remain part of the repository history.

#### Maintainable Project Structure
This workflow keeps the repository simple, clean, and easy to manage while preserving a complete history of engineering activities and decisions.

### Example Workflow
- I create a feature branch for a project activity, such as feature/system-requirements.
- I develop the related artifact and create commits during development.
- After completing the activity, I merge the work into main.
- I then delete the feature branch.
- For the next project activity, I create a new feature branch and follow the same process.

### Key Learning
- I learned that Git is not only a version control tool but also a configuration management and traceability tool.
- Using a stable main branch together with temporary feature branches helps me maintain a reliable project baseline, isolate incomplete work, avoid outdated branches, keep the repository organized, and preserve the complete history of engineering decisions.

