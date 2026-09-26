# Runnerz 1.0.13 release evidence

The canonical private Android source is on Runnerz 1.0.13 / versionCode 14. The two build flavours remain separate applications but share the same privacy-bounded UNIFIED receiver:

| Variant | Application ID | Version name | Version code |
| --- | --- | --- | ---: |
| Live debug | `com.runnerz.app` | `1.0.13` | `14` |
| Field Test debug | `com.runnerz.app.fieldtest` | `1.0.13-field-test` | `14` |

Both variants validate `runnerz://music-session` and return only aggregate completion data through `unified://runnerz-return`. Track identities, streaming credentials, listening history and exact GPS trails do not cross the app boundary. Field Test synthetic fixtures and local preview are flavour-scoped.

## Build evidence

The source checkout passed:

```text
./gradlew :app:testLiveDebugUnitTest :app:testFieldTestDebugUnitTest :app:assembleLiveDebug :app:assembleFieldTestDebug
BUILD SUCCESSFUL
```

| Artifact | SHA-256 |
| --- | --- |
| `app-live-debug.apk` | `0e97af0bf7ded5c538db15e5c75befa90e5271c065bd273809bcf5945a99ea04` |
| `app-fieldTest-debug.apk` | `bf246b0f749b9c363b3a83d56f3fbf250e5991a4f95507eb65813b54e9129171` |

These hashes identify the locally built debug artifacts; they are not a claim that either artifact is currently distributed through Firebase or an app store. Physical outdoor GPS completion and signed cross-app start/run/return acceptance remain separate release gates.
