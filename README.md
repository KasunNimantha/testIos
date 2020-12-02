# Soho-iOS
![](https://app.bitrise.io/app/11b74e5ddc088d99/status.svg?token=vIZ_woi0Fm_YPW1Vm46ZZA&branch=develop "Bitrise status")


## Ordering of a class:
1. Constants
2. Outlets
3. Other variables
4. VC Lifecycle methods
5. Binding
6. General methods
7. Implementations
8. Actions 

## Naming
**Variable**: 
Camel cased
``` swift 	
var sampleVariable: String = ""
```
**Constant**: 
Uppercased and underscored
``` swift 	
let SAMPLE_CONSTANT: String = ""
```

## Git
* Create new branch for features, hotfixes, bugs etc.
* Branch naming should follow {Your Initials}/{feature, bug, hotfix letter}{ticket number}/{branch name}
```
e.g. js/f123/descriptive_name
```
* Commits should follow {ticket number} - {description} (No 'WIP' or 'I did things' commits please). There are obviously exceptions like merges or ReadMe updates, but if applicable please follow this naming and always provide a meaningful comment
```
e.g. 151 - Removed payments module done by SH
```
* Once branch development is complete, submit a PR to develop and assign the appropriate member of the team to review. This is a team effort, we are looking to maintain code quality, catch bugs, and of course improve as a team!

## Recommended Tools
* [GitFlow](https://github.com/nvie/gitflow) for branching, releasing etc.
* [Dash](https://kapeli.com/dash)
