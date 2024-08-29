Created using repository template https://github.com/alma-poc2/test-template

Template repository version 1.0

To update latest changes from repository template to a repository, add template as remote and pull changes:

```
git remote add template https://github.com/alma-poc2/test-template
git fetch --all
git merge template/main --allow-unrelated-histories
```

## Template inmplications

Using this template combined with github app https://github.com/repository-settings/app enforces test-admin team as repository admins.

Moreover, .github directory is protected from tampering by requiring changes to be made by PR reviewed by codeowners specified in .github/CODEOWNERS file
