# CI/CD Projects

## Task 1: Continuous Integration (CI)

Built a CI pipeline to automatically run checks on every push and pull request.

### Pipeline Includes:
- Linting with ESLint
- Unit tests with Jest
- Triggers on PRs and pushes to `main`

### What I Learned:
- How to structure CI workflows with GitHub Actions
- Running automated tests and linters before merging code
- Handling path and working-directory issues

---

## Task 2: Continuous Deployment (CD)

Built a CD workflow to deploy applications automatically or update environments.

### Pipeline Includes:
- Build and push Docker images
- Trigger automated deployments
- Update static sites or simple environments

### What I Learned:
- Managing Docker login tokens for CI/CD
- Deploying Docker images automatically
- Triggering deployments on PR merges

---

## Challenges Solved
- Stopped untracked files showing up in CI using `.gitignore`
- Fixed workflow path errors in GitHub Actions
- Managed Docker Hub tokens securely