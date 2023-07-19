git-create-new-feature-branch
# Git - Create New Feature Branch

Based on "Feature Branch: A Quick Walk Through Git Workflow" at https://blog.mergify.com/feature-branch-a-quick-walk-through-git-workflow/

How to Create a Feature Branch in Git?

```
git checkout main
git pull
git checkout -b new-feature
git add <some-file>
git commit
git push -u origin new-feature
```

**Note**: A recommended naming for feature branches is:

```
feat/my_new_feature_short_name
```
