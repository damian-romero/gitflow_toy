# gitflow_toy

A repository to learn git flow.

## ToDo:

1. An issue for a hotfix.  A hotfix branch published to GitHub via git flow hotfix publish <xxx>.  A PR of that hotfix into master .  That hotfix will be back-merged into master and develop via git flow hotfix finish <xxx> and git push for each of those will update GitHub repo.  It will mark the PR as merged and close it out.

2. An issue for a feature.  A feature branch published to GitHub  via git flow feature publish <xxx>. A PR of that feature into develop . This feature will be merged into develop via git flow feature <xxx> and git push.  The PR will be marked as merged and closed out.

3. A new release from develop that includes your new feature.  Release branch published to GitHub via git flow release publish <xxx> A PR for the release.  This release will be back-merged into master via git flow release finish <xxx> and git push.

## Changelog

v.0.1.0:
 * Basic project setup:
 * README.md and gitignore, and resources.md

v.0.1.1:
 * Hotfix for resources.md links, iss #1
 * This hotfix failed since I wanted to do a pull request
 * noticed that `git flow hotfix publish` is not working on Mac brew install git-flow v. v.0.4.1

v.0.1.2:
 * Hotfix for resources.md links, iss #2
 * This fix creates resources/
 * Also updated the version of this README.md file