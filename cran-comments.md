## Release summary

This patch release updates package links after the move to econdataverse and
includes a fix for API date parsing in `uis_get_indicators()`.

## Test environment

* macOS Tahoe 26.6 (aarch64), R 4.6.1
* `devtools::check(document = FALSE, remote = TRUE, manual = TRUE)`

## R CMD check results

0 errors | 0 warnings | 1 note

* HTML manual validation was skipped because the local HTML Tidy version is too
  old. PDF manual compilation passed.
* All 67 test expectations passed, with no failures, warnings, or skips.
* `urlchecker::url_check()` passed and the README was rebuilt successfully.

## Current CRAN results

On 2026-10-19, CRAN reported OK for uisapi 0.1.1 on all 13 listed platforms:
<https://cran.r-project.org/web/checks/check_results_uisapi.html>.

## Checks before submission

* Run win-devel checks. These were deferred at the maintainer's request.
* Review these comments and submit to CRAN.
