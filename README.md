# Test Advisory Board [![Build Status](https://app.bitrise.io/app/d528939eac6fe1db/status.svg?token=r7omaK8c9XTuCFxeNeP86A)](https://app.bitrise.io/app/d528939eac6fe1db)

A collection of proofs of concept that demonstrate technology used throughout
Instructure.

Primary focus is on testing.

## Proofs of concept

- [Pact](pact) - Contract testing approach used by various Instructure apps

## Continuous Integration

We use [bitrise.io][bitrise] to run our continuous integration (CI) builds for
this repo. See [`bitrise.yml`](bitrise.yml) for details.

To run the same CI steps on your computer:

1. Install the [Bitrise CLI][cli] (`brew install bitrise` for you homebrewers)
2. Run this inside your terminal in this repo:

```sh
bitrise run --workflow ci
```

[bitrise]: https://app.bitrise.io/app/d528939eac6fe1db#/builds
[cli]: https://app.bitrise.io/cli
