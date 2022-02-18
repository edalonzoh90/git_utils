# git cheat sheet
Commands frequently used


| Command | Description |
| --- | --- |
| **Rebase** |
| `git rebase master` | Set master as the base branch of the feature |
| **Merges** |
| `git reset --hard master` | Sync a branch from other brach |
| `git push --force` | Force push ignoring incoming changes |
| **Tags** |
| `git tag` | List tags |
| `git tag -a r.0624 -m 'Release 0624'` | Create a local tag |
| `git tag -a r.0623 9fceb02 -m 'Release 0623'` | Tag an specific commit |
| `git show r.0624` | Show specific tag |
| `git push origin r.0624` | Sincronize tag with remote |
| `git push origin --tags` | Sincronize more than one tag |
| `git tag -d r.0624` | Delete local tag |
| `git push origin --delete r.0624` | Delete remote tag |





