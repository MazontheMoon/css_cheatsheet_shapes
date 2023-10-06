# Welcome!

## Guidelines

1. Submit a new issue for any feature you want to work on (If you want to work on this feature add this request in a comment)
2. Create a new  branch for each feature
3. Follow naming convention below for git commits

## Code Naming Conventions

[BEM](https://css-tricks.com/bem-101/)

/* Block component */<br>
.btn {}
.container {}

/* Element that depends upon the block */ <br>
.btn__price {}
.container__title

/* Modifier that changes the style of the block */<br>
.btn--dark {} <br>
.btn--big {}
.container__gallery--dark {}

## Git Commit Naming Conventions

Keyword: Description FILE

*Examples:*

new: Create README<br>
style: Add colour scheme values to STYLE

*Keywords:*

* new: creating a new document or file
* build: changes specific to the build or system
* update: adding content or changes to document
* fix: correcting a specific issue
* style: style specific changes
* docs: changes to documentation
* test: specific feature tested
* revert: reverting to a previous commit

## Reporting Bugs

Submit a new issue for every bug with the following information:

**Describe the bug**
A clear and concise description of what the bug is.

**To Reproduce**
Steps to reproduce the behavior:

    Go to '...'
    Click on '....'
    Scroll down to '....'
    See error

**Expected behavior**
A clear and concise description of what you expected to happen.

**Screenshots**
If applicable, add screenshots to help explain your problem.

**Device information**

    Type: [e.g. iPhone6]
    OS: [e.g. iOS]
    Browser [e.g. chrome, safari]
    Version [e.g. 22]

Additional context
Add any other context about the problem here.
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](code_of_conduct.md)
