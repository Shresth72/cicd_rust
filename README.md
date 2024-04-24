# Setting Up CICD in Rust with Testing

## Setting up Github CICD from a remote repository

```bash
git remote add ci https://github.com/remote_ci_repo

git fetch ci

git merge --allow-unrelated ci/main
```
