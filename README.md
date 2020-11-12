# gitflow_toy

A repository to learn git flow.

## Contents:

This reporsitory contains both `resources/` for learning _the flow_, and my own `walkthroughs/` including my own mistakes and progress (git commands and notes can be found in there).

The following "ToDo" list was a series from exercises assigned to me by [astrochun](https://astrochun.github.io) for my software development duties at the [UA libraries](https://new.library.arizona.edu/).

I have now completed this ToDo list and I might add an actual ToDo document in the future, but the following section will remain in this repo.

## ToDo:

~~1. An issue for a hotfix.  A hotfix branch published to GitHub via git flow hotfix publish <xxx>.  A PR of that hotfix into master .  That hotfix will be back-merged into master and develop via git flow hotfix finish <xxx> and git push for each of those will update GitHub repo.  It will mark the PR as merged and close it out.~~

~~2. An issue for a feature.  A feature branch published to GitHub  via git flow feature publish <xxx>. A PR of that feature into develop . This feature will be merged into develop via git flow feature <xxx> and git push.  The PR will be marked as merged and closed out.~~

~~3. A new release from develop that includes your new feature.  Release branch published to GitHub via git flow release publish <xxx> A PR for the release.  This release will be back-merged into master via git flow release finish <xxx> and git push.~~

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

v.0.1.3:
 * Hotfix for resources.md links, iss #3
 * renamed resources.md > useful_links.md
 * added some links to useful_links.md

v.0.2.0:
 * Includes walkthroughs for hotfixes and features
 * Requires check of md documents and directories

v.0.2.1:
 * Hotfix for feature-wt.md and hotfix-wt.md, iss #11r
 * fix comment spacing on feature-wt.md and hotfix-wt.md

v.0.2.3:
 * Minor update to resources/useful_links.md, two additional resources #17

v.0.3.0: - v.0.3.2
 * Next major release
 * Added 10+ new links to `useful_links.md` including a cool cheatsheet for Git
 * Fixed add duplication from `git commit -a` in walkthroughs