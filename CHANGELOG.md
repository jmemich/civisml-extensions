# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [0.1.1] - 2017-09-13

### Fixed
- Fixed version requirements for scikit-learn to properly import `MaskedArray` (#4).
- In the stacking estimators, get_params no longer throws index error
  when `estimator_list` is an empty list (#6).

## [0.1.0] - 2017-09-12

### Added
- initial commit
