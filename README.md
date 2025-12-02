# Readme

Attempts to reproduce an issue where Measure SDK and NewRelic SDK are added to a Flutter project.
The following versions were used:

* Measure SDK version (Native): 0.15.0
* Measure Flutter version: 0.2.1
* NewRelic Flutter version: 1.11.1
* Measure Gradle Plugin version: 0.11.0
* NewRelic Gradle Plugin version: 7.5.1

The following settings are added to `gradle.properties`:
* `android.useAndroidX=true`
* `android.enableJetifier=true`

### Result

The build succeeds.