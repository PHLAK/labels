Labels
======

An opinionated set of labels to replace the GitHub's default labels.

| Name         | Color     | Description                                          |
| ------------ | --------- | ---------------------------------------------------- |
| Bug          | `#CC1F1A` | Something isn't working as intended                  |
| Dependencies | `#805ad5` | Pertain to or update a dependencies                  |
| Documentaton | `#38A89D` | Improvements or additions to documentation           |
| Duplicate    | `#CBD5E0` | This issue or pull request already exists            |
| Enhancement  | `#2779BD` | New feature or improvement to existing functionality |
| Help Wanted  | `#1F9D55` | Extra attention or outside assistance is needed      |
| Question     | `#EB5286` | Further information is requested                     |
| Security     | `#4A5568` | Pull requests that address a security vulnerability  |
| Wont Fix     | `#CBD5E0` | Will not be addressed or fixed                       |

Installation
------------

Installation requires GitHub CLI (`gh`) 

    gh label clone --force --repo phlak/labels --force <destination-repository>
