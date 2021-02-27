# mc-exercise

### Allee McCoy | Aloysious | Kassie Bradshaw | Marie Marcos

1. Ted did a `git pull origin master` into his `Feature Branch` Big no-no
2. Sebsequently when Carol and Bob worked on thier feature they did not perform the `git pull origin master` from "Main" prior to going into thier  `Feature Branch` to work.
+ pulling the master into a feature is bad news...Don't do it!
+ When both teams tried to submit changes problems occured...this is becuase:
4.  Ted and Carol have been making changes to the `main` in thier `feature branch` which means they're in fast forward mode, or ahead of themselves so to speak.
5.  Bob and Carol are living in the past, they're making edits but they never pulled down the most current content, when they push thier changes they will be the ones to cause the merge conflict.


### What should have happened:

1. Everyone does a  `Git pull origin` from main and then creates thier own features to work from
2. The team should dicscuss naming conventions and workflow
3. set a standard, work from well named branches, communicate when a pull request has been made, and when one is ready for review.
4. Have multiple sets of eyes on review, dont leave it all up to one person, this allows for more code review of submitted files.
