# Git commit template

Git commit template to improve your project's commit messages.

This commit template has a bunch of information inside,
and it's set up so you can freely edit it as you like.

If you want to learn why we use this kind of template,
see our repo [How to write a great git commit message](https://github.com/joelparkerhenderson/git_commit_message)

If you want to improve your git speed and capabilities,
see our repo  [Git alias configuration for shortcuts and enhancements](https://github.com/gitalias/gitalias)


## Help ##

Subject line imperative verbs:

  * feat     (creating a new feature)
  * drop     (delete a capability e.g. feature, test, dependency)
  * fix      (Fix an issue e.g. bug, typo, accident, misstatement)
  * test     (adding or refactoring tests; no production code change)
  * bump     (increase the version of something e.g. a dependency)
  * make     (change the build process, or tools, or infrastructure)
  * start    (begin doing something; e.g. enable a toggle, feature flag, etc)
  * stop     (end doing something; e.g. disable a toggle, feature flag, etc)
  * perf     (a change that MUST be just about performance, e.g. speed up code)
  * doc      (a change that MUST be only in the documentation, e.g. help files)
  * refactor (a change that MUST be just refactoring)
  * reformat (a change that MUST be just format, e.g. indent line, trim space, etc)
  * WIP      (a Work In Progress; for intermediate commits to keep patches reasonably sized)

For the subject line:
  * Use 50 characters maximum.
  * Do not use a sentence-ending period.

For the body text:
  * Use as many lines as you like.
  * Use 72 characters maximum per line for typical word wrap text.


## Usage ##

Put the template file here:

    ~/.git_commit_template.txt

Configure git to use the template file by running:

  git config --global commit.template ~/.git_commit_template.txt

If you prefer other file locations or ways of working,
you can freely adjust the usage as you like.

Alternatively, you can run the commands below to auto the steps above.

    curl -L -o ~/.git_commit_template.txt https://raw.githubusercontent.com/shaunmclernon/git_commit_template/master/git_commit_template.txt
    git config --global commit.template ~/.git_commit_template.txt


## Credit

This repo has been based on the great work from Joel Parker Henderson, for reference see here https://github.com/joelparkerhenderson/git_commit_template
