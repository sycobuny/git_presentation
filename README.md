Using Git
---------

Part 1 (of ...?)
================

This is a presentation designed for the August 16, 2012 meeting of the Baltimore
Perl Mongers. It is not quite an introduction to the idea of git (as many of the
members are already aquainted with it to some degree), but a discussion of some
of the more interesting features that can be folded into a workflow quickly and
easily.

It may be part 1 of a series, depending on how well-received it is.

Outline
=======

  1. Important Files
    1. `.gitignore` / `$GIT_DIR/info/exclude`
    2. `.git/config` / `~/.gitconfig` / `/etc/gitconfig`
  2. The Staging Area and Your Working Copy
    1. Bypassing Staging (`git commit -a`)
    2. Adding Files (`git add`)
    3. Adding Patches (`git add -p`)
    4. Interactive Mode (`git add -i`)
    5. Reverting Changes (`git checkout` / `git reset`)
  3. Branching/Tagging
    1. Creating/Deleting Local Branches
    2. Pushing/Deleting Remote Branches
    3. Tracking Remote Branches
    4. Tagging
    5. Annotating Commits/Tags
    6. Annotating Branches
  4. Forking/Patching/Pull Requests
    1. Forking a Copy
    2. Creating Patches
    3. Sending Pull Requests
  5. Aliases
    1. Simplifying Git Commands
    2. Calling External Commands
