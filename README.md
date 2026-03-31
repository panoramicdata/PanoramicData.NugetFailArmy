# PanoramicData.NugetFailArmy

PanoramicData.NugetFailArmy is an intentionally non-conformant repository used as a negative integration fixture for PanoramicData.NugetManagement.

It exists to answer a simple question: when the assessment engine scans a genuinely poor repository, does it detect the problems we expect it to detect?

## Why This Repository Is Deliberately Bad

This repository is designed to violate a broad set of repository standards on purpose, including:

- missing or broken CI/CD conventions
- weak package and project metadata
- outdated target framework and SDK settings
- missing community health files
- poor build and documentation settings
- inadequate testing setup
- poor repository hygiene and dependency management

The goal is not to model realistic engineering practice. The goal is to provide a stable, repeatable failure case that proves the rules catch bad inputs.

## Intended Use

Use this repository only for assessment and integration testing.

If PanoramicData.NugetManagement starts passing this repo too easily, the rules are probably too weak.

If the assessment produces unexpected failures or passes, the fixture may need to be adjusted so that it better represents the failure mode being tested.

## Important Note

Although this repository is MIT licensed, that does not mean it is a good template for new projects. It is intentionally broken in multiple ways and should not be copied as a starting point.
