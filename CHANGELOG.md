# Changelog 

Earlier changes were not versioned. Therefore dates of change are used instead there.

For new releases see [Github Release page](https://github.com/AuHau/toggl-cli)

## [2.4.4](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/compare/v4.0.1...v2.4.4) (2026-04-05)


### ⚠ BREAKING CHANGES

* python 3.13 support and dropping python 3.8 ([#340](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/issues/340))
* migration to v9 api version ([#303](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/issues/303))

### Features

* add limit option to ls ([#314](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/issues/314)) ([c1d5ede](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/c1d5edef5c8dbc94c5d55d11bcb863a6af29b237))
* allow overriding API URLs via environment variables ([0a0111e](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/0a0111ef2a6aa0fdc7b0204333c1e8448e93014a))
* date-format config support ([176c8cf](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/176c8cf7d157915cdc8ab1fb0c73e09c7eb4af95))
* exponential backoff retry mechanism ([#341](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/issues/341)) ([14f0f0a](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/14f0f0a28fc81d9873efe0b57626095e7baf0e7a))
* migration to v9 api version ([#303](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/issues/303)) ([b9aff61](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/b9aff6190217e886d166f6036262c82e2114a6a9))
* print description for toggl start ([#316](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/issues/316)) ([6693dfe](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/6693dfe2af72fed7af481cabd0d7527307c2a841))
* python 3.13 support and dropping python 3.8 ([#340](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/issues/340)) ([4181a73](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/4181a731f8fdf31e2ea685af623a2835377aa0f9))
* python 3.8 support ([d7bb33e](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/d7bb33e6ade596bfca328d517bc2e6c9104aeb55))
* respect XDG spec for configuration files ([#300](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/issues/300)) ([5086039](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/5086039e6392523fad5ef3de2326eca7bf8b6832))
* rework of goal and sum commands ([72f10d7](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/72f10d780f6828292afadbc68d95f17cee0506d1))
* sum and day command functions ([#136](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/issues/136)) ([8e874bf](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/8e874bf586392045cf5458d97d57c1a811dfcbce))
* support for billable ([2cf0861](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/2cf08617f2da722821d4134ed94687421c17105b))
* support TOGGL_DEFAULT_WID env var, remove debug step ([f2230a3](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/f2230a35005b9c3da8f7b9ff3f6309071e589736))
* task for start command ([#211](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/issues/211)) ([6bff185](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/6bff185291c72a1c38101579531b3b3bf700f9f2))
* theme support ([8fcf165](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/8fcf165c4a6e50d65c72f753a22ea004531598cd))
* use new api url ([#185](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/issues/185)) ([9f659f8](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/9f659f81dafa385d799cd3f95de58e980817d70f))


### Bug Fixes

* bootstrap timezone ([#325](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/issues/325)) ([cd81170](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/cd81170fb4281c1ea7afb52736808bc5d99071d6))
* circular import ([#141](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/issues/141)) ([2b9a634](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/2b9a6343767da116738dacf0cc903a43b4bd61cb))
* handling of zero duration time entries ([#231](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/issues/231)) ([d2bd9cb](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/d2bd9cb360233a3f22f31d97d3661677e0d7829c))
* make name group optional in parse_detail regex ([49c0c10](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/49c0c10b194a30478b511638ea8987dcb5a7478f))
* parse_detail regex to handle dots/punctuation in names ([5c84736](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/5c8473606b8420164df4084fc2d204d55a23fe84))
* Set default color to toggl's default 1 ([#302](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/issues/302)) ([7ee7aa8](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/7ee7aa8ace000a88035c00a0de7842dbbf83d293))
* set permissions only on config creation ([#339](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/issues/339)) ([b698a4d](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/b698a4db9f67ce33deab2aa31833b8e993cb47c5))
* set restrictive permissions each time config file is persisted ([#337](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/issues/337)) ([d952f1e](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/d952f1eaa06129ed903db7b88e8a78e91500f7b6))
* start cmd and billable in non-premium workspace ([c714ea2](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/c714ea234fa767ecbbfb8084e888a20560b40050))
* sum command respects configured timezone ([#205](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/issues/205)) ([c2b4875](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/c2b48756bce1be6a9e21fed52170ae33a5cbe21a))
* tests ([ad0b6da](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/ad0b6da1f58ba078c92ef2d51e02bf09a4e9ee5a))
* treat empty env vars as unset in config resolution ([eb200f6](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/eb200f6d80899c0763f54152c6b809ab9c51869f))
* update expected TimeEntry Project mapping field ([#328](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/issues/328)) ([089162e](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/089162e059777436107e7c7666d491705aeee5b4))
* update persist method for Config Class ([#347](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/issues/347)) ([80a3801](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/80a3801c2e2d4a54db7e3dc96f501cdc46daaded))
* where default workspace was always set, and uid was never set ([#156](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/issues/156)) ([988f461](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/988f46101adeca1082b0e37209d7f57947ec25d2))
* wrong config mapping of values ([#163](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/issues/163)) ([12b48bf](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/12b48bf8ed5a9308193fa6901e4beed05ee74b71))


### Reverts

* pbr removal ([4829a62](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/4829a629e11d77975a8cf1fe3c3638c1a73c0765))


### Documentation

* cleanup badges ([#290](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/issues/290)) ([fe99cc0](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/fe99cc0d1ca4801e8043a1e72a66d19a1fb53519))
* fix typo ([#162](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/issues/162)) ([d5f697f](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/d5f697f5d097bf70131ebb649b24c79562002760))
* update ([cbdd2d2](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/cbdd2d23d119a2a1b69fcb8d1e8fdd4bd7a8d036))


### Miscellaneous Chores

* release trigger commit ([#287](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/issues/287)) ([6b4b8fa](https://github.com/CorrectRoadH/toggl-cli-for-unit-test/commit/6b4b8fae50195d398b5a7241dc2bb0fa432dcdc6))

## [4.0.1](https://github.com/AuHau/toggl-cli/compare/v4.0.0...v4.0.1) (2025-11-02)


### Bug Fixes

* update persist method for Config Class ([#347](https://github.com/AuHau/toggl-cli/issues/347)) ([80a3801](https://github.com/AuHau/toggl-cli/commit/80a3801c2e2d4a54db7e3dc96f501cdc46daaded))

## [4.0.0](https://github.com/AuHau/toggl-cli/compare/v3.0.3...v4.0.0) (2025-05-20)


### ⚠ BREAKING CHANGES

* python 3.13 support and dropping python 3.8 ([#340](https://github.com/AuHau/toggl-cli/issues/340))

### Features

* exponential backoff retry mechanism ([#341](https://github.com/AuHau/toggl-cli/issues/341)) ([14f0f0a](https://github.com/AuHau/toggl-cli/commit/14f0f0a28fc81d9873efe0b57626095e7baf0e7a))
* python 3.13 support and dropping python 3.8 ([#340](https://github.com/AuHau/toggl-cli/issues/340)) ([4181a73](https://github.com/AuHau/toggl-cli/commit/4181a731f8fdf31e2ea685af623a2835377aa0f9))

## [3.0.3](https://github.com/AuHau/toggl-cli/compare/v3.0.2...v3.0.3) (2025-03-05)


### Bug Fixes

* set permissions only on config creation ([#339](https://github.com/AuHau/toggl-cli/issues/339)) ([b698a4d](https://github.com/AuHau/toggl-cli/commit/b698a4db9f67ce33deab2aa31833b8e993cb47c5))
* set restrictive permissions each time config file is persisted ([#337](https://github.com/AuHau/toggl-cli/issues/337)) ([d952f1e](https://github.com/AuHau/toggl-cli/commit/d952f1eaa06129ed903db7b88e8a78e91500f7b6))

## [3.0.2](https://github.com/AuHau/toggl-cli/compare/v3.0.1...v3.0.2) (2024-07-17)


### Bug Fixes

* update expected TimeEntry Project mapping field ([#328](https://github.com/AuHau/toggl-cli/issues/328)) ([089162e](https://github.com/AuHau/toggl-cli/commit/089162e059777436107e7c7666d491705aeee5b4))

## [3.0.1](https://github.com/AuHau/toggl-cli/compare/v3.0.0...v3.0.1) (2024-06-16)


### Bug Fixes

* bootstrap timezone ([#325](https://github.com/AuHau/toggl-cli/issues/325)) ([cd81170](https://github.com/AuHau/toggl-cli/commit/cd81170fb4281c1ea7afb52736808bc5d99071d6))

## [3.0.0](https://github.com/AuHau/toggl-cli/compare/v2.4.4...v3.0.0) (2024-06-03)


### ⚠ BREAKING CHANGES

* migration to v9 api version ([#303](https://github.com/AuHau/toggl-cli/issues/303))

### Features

* add limit option to ls ([#314](https://github.com/AuHau/toggl-cli/issues/314)) ([c1d5ede](https://github.com/AuHau/toggl-cli/commit/c1d5edef5c8dbc94c5d55d11bcb863a6af29b237))
* migration to v9 api version ([#303](https://github.com/AuHau/toggl-cli/issues/303)) ([b9aff61](https://github.com/AuHau/toggl-cli/commit/b9aff6190217e886d166f6036262c82e2114a6a9))
* print description for toggl start ([#316](https://github.com/AuHau/toggl-cli/issues/316)) ([6693dfe](https://github.com/AuHau/toggl-cli/commit/6693dfe2af72fed7af481cabd0d7527307c2a841))
* respect XDG spec for configuration files ([#300](https://github.com/AuHau/toggl-cli/issues/300)) ([5086039](https://github.com/AuHau/toggl-cli/commit/5086039e6392523fad5ef3de2326eca7bf8b6832))


### Bug Fixes

* Set default color to toggl's default 1 ([#302](https://github.com/AuHau/toggl-cli/issues/302)) ([7ee7aa8](https://github.com/AuHau/toggl-cli/commit/7ee7aa8ace000a88035c00a0de7842dbbf83d293))

## [2.4.4](https://github.com/AuHau/toggl-cli/compare/v2.4.3...v2.4.4) (2023-02-14)


### Reverts

* pbr removal ([4829a62](https://github.com/AuHau/toggl-cli/commit/4829a629e11d77975a8cf1fe3c3638c1a73c0765))


### Miscellaneous Chores

* release trigger commit ([#287](https://github.com/AuHau/toggl-cli/issues/287)) ([6b4b8fa](https://github.com/AuHau/toggl-cli/commit/6b4b8fae50195d398b5a7241dc2bb0fa432dcdc6))


### Documentation

* cleanup badges ([#290](https://github.com/AuHau/toggl-cli/issues/290)) ([fe99cc0](https://github.com/AuHau/toggl-cli/commit/fe99cc0d1ca4801e8043a1e72a66d19a1fb53519))

## v2.2.0

Features:
 * Python 3.8 support
 * new `toggl sum` command that displays sums of time grouped by days
 * new `toggl goal` command that waits until you reach your defined goal for the day and the send notification
 * new theming support
 * `--today` flag for `ls` and `sum` command  

## v2.1.0

Features:
 * New Tag model with CLI commands
 * 'me' command to display current user's info
 
Fixes:
 * Correct retrieval of package's version 
 * Properly working Premium/Non-premium tests

## v2.0.2

Fixes for python_required and calculation of duration

## v2.0.1

Fix for required python version

## v2.0.0

Full rewrite of the tool by [AuHau](https://github.com/AuHau), which implements most of the toggl's API capabilities. 
Entities which is now possible to fully manage (eq. CRUD operations):
 *  Time entries
 *  Clients
 *  Projects
 *  Project users
 *  Tasks (only for premium workspaces)
 *  Workspaces
 *  Workspace users
 
Main new features of the tool:
 *  Possibility to use environment variables to specify some of the input parameters
 *  Possibility to specify different config to be used for the command's execution
 *  Django ORM's like API Classes

## v2.0.0.0b3

 * Fixing bootstrap failures
 * Dropping relative imports
 * Minor improvements

## v2.0.0.0b2

 * Adding support for Time entries Report API which enables fetching all time entries ( `api.TimeEntry.objects.all_from_reports()` / `toggl ls --use-reports`)
 * Adding support to register specific Config object as default one

## v2.0.0.0b1

First Beta release of full rewrite

## 15 Dec 2014 
Thanks to [FedericoVaga](https://github.com/FedericoVaga)
`.togglrc` now supports API token authentication. You will need to add
`api_token` to the `auth` section, and `prefer_token` to the `options` section.

## 11 Nov 2014
Major refactoring into a more MVC OO structure.

## 30 Oct 2014
Added a feature that starting, stopping, and continuing an
entry prints out the time it started or stopped. This requires a new option in
~/.togglrc: `time_format = %I:%M%p` is the default.  See
[strftime()](https://docs.python.org/2/library/datetime.html#strftime-and-strptime-behavior)
for more options.
