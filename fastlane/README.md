fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew install fastlane`

# Available Actions
## Mac
### mac generate_changelog
```
fastlane mac generate_changelog
```
Creates new branch changelog, generates changelog, creates a PR.
### mac generate_changelog_locally
```
fastlane mac generate_changelog_locally
```
Generates changelog only.
### mac increment_build
```
fastlane mac increment_build
```
Increase build number
### mac update_strings
```
fastlane mac update_strings
```
Builds Sequel Ace strings target, uploads strings to Crowdin, builds them, downloads them and commits to git

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
