# Hotfixes walkthough (ToDo #1 for this repo)


## Hotfix 1 for iss #1 (FAILED ATTEMPT TO PUSH, I MERGED)


3985  git flow hotfix start v.0.1.1

###[Do stuff here]

3990  git add .

3991  git push

3992  git push --set-upstream origin hotfix/v.0.1.1


### Trying to publish hotfix/v.0.1.1

###[THIS COMMAND DOES NOT WORK ON MAC brew git-fow v.0.4.1]

3993  git flow hotfix publish

3994  git flow hotfix publish v.0.1.1

3995  git flow version

3998  brew upgrade git-flow

4006  port install git-flow

4034  brew install git-flow

4036  git flow version

4037  cd Projects/gitflow_toy

###[etc. etc.]


### Back to Hotfix 1 for iss #1 (FAILED ATTEMPT TO PUSH, I MERGED)

4039  git status

4040  git add .

4041  git commit -m'see iss #1'

###[The following command will automatically merge without letting you do a pull request]

4042  git flow hotfix publish

4043  git flow hotfix finish v.0.1.1

###[So I push and decide to create another hotfix for another issue later]

4044  git push git push origin --all --follow-tags

4045  git push origin

###[hotfix finish did *not* delete the hotfix branch]

4058  git checkout master

4059  git flow hotfix finish v.0.1.1

4060  git push origin --all --follow-tags

###[cannot push tags here]

4061  git push

4066  git fetch --tags


## Hotfix 2 for iss #2 (CREATED A PULL REQUEST BUT DIDNT FOLLOW UP WITH `FINISH`)


4065  git flow hotfix start v.0.1.2

4069  git status

###[Bump version on README.md]

4071  git add .

4072  git commit -am'Bumped version number to 0.1.2'

4077  git status

###[Fix stuff here]

4078  git add .

4079  git commit -am'See iss #2'

4080  git push origin

4081  git push --set-upstream origin hotfix/v.0.1.2

4082  git checkout master

###[On GH: Pull request, and I merged manually --bad]

4084  git flow hotfix finish v.0.1.2

4093  git push origin --all --follow-tags

4094  git status


## Hotfix 3 for iss #4 (SUCCESFUL, though the comments say issue # 3)


4139  git flow hotfix start v.0.1.3

###[Bump version on README.md]

4153  git add README.md

4154  git commit -am'Bumped version number to 0.1.3'

###[Fix stuff here]

4163  git add .

4165  git commit -am'See iss #3'

4167  git push origin

4168  git push --set-upstream origin hotfix/v.0.1.3

###[On GH: Pull request]

###[Merge with hotfix finish]

4169  git checkout master

4172  git flow hotfix finish v.0.1.3

4174  git push origin --all --follow-tags

4175  git pull --all