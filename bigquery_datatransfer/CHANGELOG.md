# Changelog

[PyPI History][1]

[1]: https://pypi.org/project/google-cloud-bigquery-datatransfer/#history

## 0.3.0

12-17-2018 17:59 PST


### Implementation Changes
- Pick up enum fixes in the GAPIC generator. ([#6608](https://github.com/googleapis/google-cloud-python/pull/6608))
- Pick up fixes in GAPIC generator. ([#6491](https://github.com/googleapis/google-cloud-python/pull/6491))
- Fix `client_info` bug, update docstrings. ([#6405](https://github.com/googleapis/google-cloud-python/pull/6405))
- Re-generate library using bigquery_datatransfer/synth.py ([#5973](https://github.com/googleapis/google-cloud-python/pull/5973))
- Fix stray, lint-breaking blank lines from autosynth. ([#5960](https://github.com/googleapis/google-cloud-python/pull/5960))
- Re-generate library using `bigquery_datatransfer/synth.py`. ([#5947](https://github.com/googleapis/google-cloud-python/pull/5947))

### Dependencies
- Bump minimum api_core version for all GAPIC libs to 1.4.1. ([#6391](https://github.com/googleapis/google-cloud-python/pull/6391))

### Documentation
- Document Python 2 deprecation ([#6910](https://github.com/googleapis/google-cloud-python/pull/6910))
- Fix GAX fossils ([#6264](https://github.com/googleapis/google-cloud-python/pull/6264))
- Normalize use of support level badges ([#6159](https://github.com/googleapis/google-cloud-python/pull/6159))
- Harmonize / DRY 'README.rst' / 'docs/index.rst'. ([#6013](https://github.com/googleapis/google-cloud-python/pull/6013))

### Internal / Testing Changes
- Update noxfile.
- Blacken all gen'd libs ([#6792](https://github.com/googleapis/google-cloud-python/pull/6792))
- Omit local deps ([#6701](https://github.com/googleapis/google-cloud-python/pull/6701))
- Run black at end of synth.py ([#6698](https://github.com/googleapis/google-cloud-python/pull/6698))
- Unblack bigquery gapic and protos.
- Run Black on Generated libraries ([#6666](https://github.com/googleapis/google-cloud-python/pull/6666))
- Add templates for flake8, coveragerc, noxfile, and black. ([#6642](https://github.com/googleapis/google-cloud-python/pull/6642))
- Add synth metadata. ([#6562](https://github.com/googleapis/google-cloud-python/pull/6562))
- Use new Nox ([#6175](https://github.com/googleapis/google-cloud-python/pull/6175))

## 0.2.0

### Implementation Changes
- Regenerate bigquery-datatransfer (#5793)

### Internal / Testing Changes
- Avoid overwriting '__module__' of messages from shared modules. (#5364)
- Modify system tests to use prerelease versions of grpcio (#5304)
- Add Test runs for Python 3.7 and remove 3.4 (#5295)
- Fix bad trove classifier
- Rename releases to changelog and include from CHANGELOG.md (#5191)

## 0.1.1

### Dependencies

- Update dependency range for api-core to include v1.0.0 releases (#4944)

### Documentation

- Fix package name in readme (#4670)
- BigQueryDataTransfer: update 404 link for API documentation (#4672)
- Replacing references to `stable/` docs with `latest/`. (#4638)

### Testing and internal changes

- Re-enable lint for tests, remove usage of pylint (#4921)
- Normalize all setup.py files (#4909)
- Update index.rst (#4816)
- nox unittest updates (#4646)

## 0.1.0

[![release level](https://img.shields.io/badge/release%20level-alpha-orange.svg?style&#x3D;flat)](https://cloud.google.com/terms/launch-stages)

The BigQuery Data Transfer Service automates data movement from SaaS
applications to Google BigQuery on a scheduled, managed basis. Your analytics
team can lay the foundation for a data warehouse without writing a single line
of code. BigQuery Data Transfer Service initially supports Google application
sources like Adwords, DoubleClick Campaign Manager, DoubleClick for Publishers
and YouTube.

PyPI: https://pypi.org/project/google-cloud-bigquery-datatransfer/0.1.0/
