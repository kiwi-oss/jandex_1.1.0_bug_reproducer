# Jandex Gradle plugin 1.1.0 bug reproducer

A minimal Gradle project to reproduce [issue #25 in the Jandex Gradle plugin project](https://github.com/kordamp/jandex-gradle-plugin/issues/25).

Run `./gradlew assemble` and the build will fail with the reported error.

Switch to the branch `passing_build_with_1.0.0` to see that the build passes when version 1.0.0 of the plugin is used.
