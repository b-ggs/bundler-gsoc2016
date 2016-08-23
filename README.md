# [WIP] boggs × bundler × gsoc2016

This is a summary of the work I've done with [bundler](https://github.com/bundler/bundler) from April to September 2016.

This only enumerates the actual work I've done, but I've written a few blog posts detailing the experience I've had with the organization and its proponents. You can read more about my experience here (COMING SOON!).

## Feature Requests:
* Add `bundle add` command to add gems into the Gemfile (bundler/bundler#4632)
* [WIP] Ask for permission when using passwordless sudo (bundler/bundler#4905)

## Issues:
* Show executable's man page when --help or -h is present (bundler/bundler#4487)
* Add standalone flag to binstubs (bundler/bundler#4610)
* Print an outdated warning when a project is locked to an old version of Bundler (bundler/bundler#4720)
* Make `bundler` and `bundle` executables have the same functionality (bundler/bundler#4735)
* Add spec for only updating from pinned source (bundler/bundler#4793)
* Display message showing locked Bundler version is being installed (bundler/bundler#4804)
* Bundler version warning should not print when versions match (bundler/bundler#4820)
* Warn user that pre-release dependencies need to be explicitly listed in the Gemfile (bundler/bundler#4879)
* Remove "or available on this machine" from GemNotFound error in --path mode (bundler/bundler#4865)
* [WIP] `bundle outdated` with gem on multiple platforms will not show updates for both platforms (bundler/bundler#4734)
