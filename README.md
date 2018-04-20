# protected-repo
A repo to: 
  * reproduce the error that occurs from someone trying to push to a branch to which they dont have acces
  * document the steps required to :point_up:

## steps
_assume steps not listed explicitly are things **not** to do (where it makes sense :man_shrugging:)_
* create a repo
* protect `master`
  * require pr reviews
  * require signed commits
* add a @iamnotwillshepherd as collaborator
* clone the repo (as evilwill)
* make some commits to `master`
* push
