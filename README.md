# [WIP] boggs × bundler × gsoc2016

### This is a work in progress. This will be updated with a blog post detailing my experience with bundler, and this will likely be modified to add a brief description of each PR.

This is a summary of the work I've done with [bundler](https://github.com/bundler/bundler) from April to September 2016.

This only enumerates the actual work I've done, but I've written a few blog posts detailing the experience I've had with the organization and its proponents. You can read more about my experience here (COMING SOON!).

## Feature Requests:
* Add `bundle add` command to add gems into the Gemfile (https://github.com/bundler/bundler/pull/4632)
* [WIP] Ask for permission when using passwordless sudo (https://github.com/bundler/bundler/pull/4905)

## Issues:
* Show executable's man page when --help or -h is present (https://github.com/bundler/bundler/pull/4487)
* Add standalone flag to binstubs (https://github.com/bundler/bundler/pull/4610)
* Print an outdated warning when a project is locked to an old version of Bundler (https://github.com/bundler/bundler/pull/4720)
* Make `bundler` and `bundle` executables have the same functionality (https://github.com/bundler/bundler/pull/4735)
* Add spec for only updating from pinned source (https://github.com/bundler/bundler/pull/4793)
* Display message showing locked Bundler version is being installed (https://github.com/bundler/bundler/pull/4804)
* Bundler version warning should not print when versions match (https://github.com/bundler/bundler/pull/4820)
* Warn user that pre-release dependencies need to be explicitly listed in the Gemfile (https://github.com/bundler/bundler/pull/4879)
* Remove "or available on this machine" from GemNotFound error in --path mode (https://github.com/bundler/bundler/pull/4865)
* [WIP] `bundle outdated` with gem on multiple platforms will not show updates for both platforms (https://github.com/bundler/bundler/pull/4734)
