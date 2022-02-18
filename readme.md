# Present your work with Git and Rebase

## Exercise 3 - Rebase to reorder and squash commits

Scenario:
- You are working on this awesome rolling Rick feature.
- You've just demonstrated your work so far to your team.
- Your team is ofcourse impressed and can't wait until it's done.
- They like the layout and the bouncy button and want to use that for another feature.
- They ask if there's a chance you can merge that work early, even though you're not done with Rick just yet.
- Sure you say, I'll just make the bouncy button a bit more re-usable and create a pull request.

Instructions for exercise:
- Checkout branch `start`.
- Create a new branch `exercise`.
- Have a look at the commits in `solution-pr` and `solution` branch.
- Reorder `exercise` branch so that the commits for styling the button comes before the button with it's functionality
- Squash the smaller "fix" commits into their appropriate commits creating logical atomic commits.
- Reword the styling commit so that the commit message is more accurate.
- Create a new branch `exercise-pr` that could be pushed for pull request against `main` branch.

Tips:
- [Rebase](https://git-scm.com/docs/rebase) the `exercise` branch.
- Use a GUI client such as [GitExtensions](http://gitextensions.github.io/) (Win), [Fork](https://git-fork.com/) (Mac + Win) or [GitKraken](https://www.gitkraken.com/) (Linux, Mac, Win) so that you don't have to figure out the git cli commands for doing the above.
- I've written a bit about reordering, rewording and squashing commits using GitExtensions on [my blog](https://blomholm.no/posts/how-i-git-it-basic-rebase/#change-the-order-of-the-commits)

[Click here for next exercise](https://github.com/kraftlauget/git-ws-4)
