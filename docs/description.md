# Git Flow Explanation

Git Flow is a branching model for Git, created by Vincent Driessen. It makes release management easier by using specific branches for specific parts of the development lifecycle.

## Key Branches

### 1. Master/Main
- Stores the official release history.
- Only stable code.

### 2. Develop
- Integration branch for features.
- Contains the latest delivered development changes for the next release.

### 3. Feature Branches
- Created from: `develop`
- Merged back into: `develop`
- Used for developing new features.

### 4. Release Branches
- Created from: `develop`
- Merged back into: `develop` and `master`
- Used for preparing a new production release.

### 5. Hotfix Branches
- Created from: `master`
- Merged back into: `master` and `develop`
- Used for quick fixes in production.
