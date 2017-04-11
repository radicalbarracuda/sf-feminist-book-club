# How to Contribute

First, thank you for considering a contribution to our project! 

## Submitting Changes


Please send a [GitHub Pull Request to sf-feminist-book-club](https://github.com/radicalbarracuda/sf-feminist-book-club) with a clear list of what you've done (read more about [pull requests](http://help.github.com/pull-requests/)). Please follow our coding conventions (below) and make sure all of your commits are atomic (one feature per commit).

Always write a clear log message for your commits. One-line messages are fine for small changes, but bigger changes should look like this:

    $ git commit -m "A brief summary of the commit
    > 
    > A paragraph describing what changed and its impact."

## Coding conventions

### Commit message style

A well-crafted Git commit message is the best way to communicate context about a change to fellow developers (and to your future self). A diff will tell you _what_ changed, but only the commit message can properly tell you _why_.

Commit messages, unlike pull requests, are most useful when combined with development tools like `git log`. Keep this difference in mind when deciding what level of detail to include: your commit message will be more accessible as documentation when actively writing code.

**General Best Practices:**

1. Separate subject from body with a blank line
2. Limit the subject line to 50 characters
3. Capitalize the subject line
4. Describe your changes in imperative mood, e.g. "Make xyzzy do frotz" instead of "[This patch] makes xyzzy do frotz" or "[I] changed xyzzy to do frotz"
5. Use the body to explain what and why vs. how

For more tips, check out Chris Beams' [How to Write a Git Commit Message](https://chris.beams.io/posts/git-commit/).

In addition, if you are contributing solo to a branch, consider a `rebase` to clean up your commit messages. This will decrease clutter for commits such as `"Fixed the typo"`.

### Pull request content

The goal of your pull request, besides leaving a paper trail for your future self (similar to a commit message) is specifically to provide context for your _reviewers_, making it easy for them to jump into your code, demo changes if necessary, and provide constructive feedback.

We use a standard [pull request template](.github/PULL_REQUEST_TEMPLATE.md) that you can feel free to use and copy.

### Issue content

The goal of an issue is to concisely and clearly communicate the bug or issue, steps to reproduce it, and an idea (if you have one) on how to solve it.

We use a standard [git issue template](.github/ISSUE_TEMPLATE.md) that you can also feel free to use and copy.

### Code Reviews

The core maitenence team strives to review pull requests within a day or two. Feel free to tag a maintainer (@lizhubertz, @dash, @pamo) on any review and [email us](radicalbarracuda@gmail.com) if you feel the wait has been too long. 
  
Thanks!

The SF Feminist Book Club Contribution Squad
