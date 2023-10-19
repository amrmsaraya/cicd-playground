fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## Android

### android test

```sh
[bundle exec] fastlane android test
```

Runs all the tests

### android beta

```sh
[bundle exec] fastlane android beta
```

Submit a new Beta Build to Crashlytics Beta

### android firebase

```sh
[bundle exec] fastlane android firebase
```

Submit a new version to Firebase App Distribution

### android deploy

```sh
[bundle exec] fastlane android deploy
```

Deploy a new version to the Google Play

### android fetch_and_increment_googleplay_build_number

```sh
[bundle exec] fastlane android fetch_and_increment_googleplay_build_number
```

Fetches the latest version code from the Play Console and increments it by 1

### android fetch_and_increment_firebase_build_number

```sh
[bundle exec] fastlane android fetch_and_increment_firebase_build_number
```

Fetches the latest version code from the Firebase App Distribution and increments it by 1

### android increment_version_code_x

```sh
[bundle exec] fastlane android increment_version_code_x
```



----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
