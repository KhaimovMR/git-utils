# git-utils

## branched commit messages hook
#### Installation:
````
curl https://raw.githubusercontent.com/KhaimovMR/git-utils/master/install-branched-commit-message | bash
````
It will create two scripts:
- hook itself `~/bin/prepare-commit-msg` that will be linked in your repositories in `.git/hooks` directory as the `prepare-commit-msg` hook
- installation script `~/bin/install-branched-commit-message` that should be run in tha repository root where you want to install the hook

#### Usage:
In the root of repository, that you want to have the branch prefixed messages run:
````
~/bin/install-branched-commit-message
````
