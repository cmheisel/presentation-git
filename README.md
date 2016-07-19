# Getting good at Git - An introduction

* About me
* Version control
  * Track changes to files
    * What changed
    * Who changed it
    * When did they change it
* Why version control
  * Semi-infinite undo button
  * Ease collaboration
  * ???
* Repositories
  * Collection of files/folders and ALL of the changes that've been made to them
  * .git folder
* Clone
  * Make a copy of the entire repository onto my machine
* Change sets
  * Make changes to code
  * Add them to the stage
* Commit
  * A set of changes permanently added to the history
  * An undo point
* Push
  * Send my changes up to the remote copy of the repository
  * Why? What happens if my laptop catches on fire
  * Or I want my friends to see the changes
* Branch
  * A set of commits occurring from a moment in the history of another Branch
  * Really it's a way for people working on different to do it in relative isolation
  * It's like your code goes on a vacation and doesn't check twitter or facebook for a while
* Merging
  * But in reality you want to stay mostly up to date with your teammates
  * Brings all the changes from the target branch into the destination branch
* Pull request
  * Kind madam or sir, I hereby present this difference between my branch and your branch for your consideration
  * Results in a merge
* Github flow
  * How most folks use it
  * Branch
  * Commit
  * Test
  * Merge and deploy
* Fork (Github)
  * You want to make some changes to someone elses code
    * Because someone is wrong on the Internet
  * You could clone their repository
    * But clones can die in a fire unless...
    * You have a remote repository you can push to
  * A fork is your personal, remote copy of their code at the moment you fork it
  * You can clone it locally
  * Make changes
  * and PR
