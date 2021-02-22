# Git Branches Documentation  

## Permanent Branches  
* dev - New features and bug fixes are moved into development branch. Resolve merge conflicts  
* test - QA/testing
* staging - (optional) Propose/decide features that should be moved to production  
* master - Production

Code flow: dev -> test -> staging -> master  

## Temporary Branches
* feature - New feature  
* bugfix - Fix bugs in feature branch after release  
* hotfix - Critical changes that must be handled inmmediately  
* experimental - New ideas that are not required to be released  
* build - Create build artifacts for code coverage: distribution packages, WAR files, reports, log files, etc.  
* release - Tagging specific release version  
* merge - Resolve merge conflicts  

Temporary branches are merged into dev branch (if needed) and then follow the work flow into production  

## Examples
* feature/JIRA-123_password-reset  
* feature/password-reset  
* bugfix/password-reset-spellcheck  
* hotfix/increase-password-length  
* experimental/dark-mode  
* build/password-reset-artifacts  
* release/AppName-2.0  
* merge/combined-shopping-cart  

More info: https://dev.to/couchcamote/git-branching-name-convention-cch  