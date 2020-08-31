## Release for v.0.2.0, ToDO n.3

### [Add new release from develop that includes your new feature.]

4264  git flow release start v.0.2.0

4266  git add README.md

4267  git commit -m'Bumped to version 0.2.0'

### [Add last-minute fixes here]

4275  git commit -am'last-minute fix: change misspelling walkthoughs/ -> walkthroughs/'

4282  git commit -am'last-minute fix: fix spacing in hotfix-wt.md'

### [Published to GitHub via git flow release publish]

4283  git flow release publish v.0.2.0

### [Add PR for the release.]

### [Back-merge into master via git flow release finish and git push.]

4290  git checkout develop

4291  git flow release finish v.0.2.0

4293  git push origin --all --follow-tags
