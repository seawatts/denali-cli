# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

<a name="0.0.13"></a>
## [0.0.13](https://github.com/denali-js/denali-cli/compare/v0.0.11...v0.0.13) (2017-08-30)


### Bug Fixes

* **blueprint:** loosen restriction on denali version in blueprints ([#26](https://github.com/denali-js/denali-cli/issues/26)) ([88c554a](https://github.com/denali-js/denali-cli/commit/88c554a))
* **build:** copy yarn.lock into dist on build ([#13](https://github.com/denali-js/denali-cli/issues/13)) ([ec736dd](https://github.com/denali-js/denali-cli/commit/ec736dd))
* **lint:** add tslint dependency and fix existing lint issues ([#23](https://github.com/denali-js/denali-cli/issues/23)) ([6c5e76e](https://github.com/denali-js/denali-cli/commit/6c5e76e))
* **project:** queue spinner promises on watch ([#20](https://github.com/denali-js/denali-cli/issues/20)) ([8ab9102](https://github.com/denali-js/denali-cli/commit/8ab9102)), closes [#19](https://github.com/denali-js/denali-cli/issues/19)
* allow install/uninstall package methods to accept non-existent packages and still complete as many as possible ([7d07bf3](https://github.com/denali-js/denali-cli/commit/7d07bf3))
* augment plugin summaries with dist dirs ([3a49e93](https://github.com/denali-js/denali-cli/commit/3a49e93))
* clean dist before building ([65844d8](https://github.com/denali-js/denali-cli/commit/65844d8))
* clean up some redundant/unused code ([4103429](https://github.com/denali-js/denali-cli/commit/4103429))
* fix spacing for version announcment ([c44ad9b](https://github.com/denali-js/denali-cli/commit/c44ad9b))
* print version output on single line ([b64814b](https://github.com/denali-js/denali-cli/commit/b64814b))


### Features

* add install/uninstall package methods to blueprint ([a71440d](https://github.com/denali-js/denali-cli/commit/a71440d))
* add main-dir support to find-addons invocation ([7652197](https://github.com/denali-js/denali-cli/commit/7652197))
* remove prepublish step from blueprints since no longer needed with main-dir ([11588b4](https://github.com/denali-js/denali-cli/commit/11588b4))
* show if the CLI or denali installation in use is linked ([9f494f6](https://github.com/denali-js/denali-cli/commit/9f494f6))
* support abbreviated commands; fixes [#17](https://github.com/denali-js/denali-cli/issues/17) ([b8b2d01](https://github.com/denali-js/denali-cli/commit/b8b2d01))