<a name="5.0.0"></a>
# [5.0.0](https://github.com/greenkeeperio/greenkeeper/compare/v4.2.1...v5.0.0) (2017-05-02)


### Features

* Deprecate the old Greenkeeper ([35729f1](https://github.com/greenkeeperio/greenkeeper/commit/35729f1))


### BREAKING CHANGES

* Deprecate old Greenkeeper



<a name="4.2.1"></a>
## [4.2.1](https://github.com/greenkeeperio/greenkeeper/compare/v4.2.0...v4.2.1) (2017-02-07)


### Bug Fixes

* **package:** update js-yaml to version 3.8.0 ([41391bf](https://github.com/greenkeeperio/greenkeeper/commit/41391bf))



<a name="4.2.0"></a>
# [4.2.0](https://github.com/greenkeeperio/greenkeeper/compare/v4.1.2...v4.2.0) (2017-01-13)


### Bug Fixes

* use full url in integration banner, so it can be opened right from the terminal ([99363c3](https://github.com/greenkeeperio/greenkeeper/commit/99363c3))


### Features

* **signup:** open integration signup page ([ccf3a8a](https://github.com/greenkeeperio/greenkeeper/commit/ccf3a8a))
* handle disallowedSignups response from the server ([0da931d](https://github.com/greenkeeperio/greenkeeper/commit/0da931d))



<a name="4.1.2"></a>
## [4.1.2](https://github.com/greenkeeperio/greenkeeper/compare/v4.1.1...v4.1.2) (2016-12-08)


### Bug Fixes

* **package:** update inquirer to version 2.0.0 ([#353](https://github.com/greenkeeperio/greenkeeper/issues/353)) ([ad30025](https://github.com/greenkeeperio/greenkeeper/commit/ad30025))



<a name="4.1.1"></a>
## [4.1.1](https://github.com/greenkeeperio/greenkeeper/compare/v4.1.0...v4.1.1) (2016-11-12)


### Bug Fixes

* **package:** update js-yaml to version 3.7.0 ([#335](https://github.com/greenkeeperio/greenkeeper/issues/335)) ([d5f22b8](https://github.com/greenkeeperio/greenkeeper/commit/d5f22b8))



<a name="4.1.0"></a>
# [4.1.0](https://github.com/greenkeeperio/greenkeeper/compare/v4.0.0...v4.1.0) (2016-10-27)


### Bug Fixes

* **help:** add list of repository options ([2e4afb9](https://github.com/greenkeeperio/greenkeeper/commit/2e4afb9)), closes [#270](https://github.com/greenkeeperio/greenkeeper/issues/270)


### Chores

* drop support for node <4 ([1bdf040](https://github.com/greenkeeperio/greenkeeper/commit/1bdf040))


### Features

* **config:** add path subcommand for config file ([2b901e3](https://github.com/greenkeeperio/greenkeeper/commit/2b901e3))
* **info:** Show list of open PRs, closes [#150](https://github.com/greenkeeperio/greenkeeper/issues/150) ([df3f965](https://github.com/greenkeeperio/greenkeeper/commit/df3f965))
* **web-app:** add a banner to advertise web app and a command to open it ([33d91fd](https://github.com/greenkeeperio/greenkeeper/commit/33d91fd))
* add a banner that points to the new github integration ([b82d3b2](https://github.com/greenkeeperio/greenkeeper/commit/b82d3b2))
* Show a warning if the .travis.yml excludes greenkeeper branches, closes [#222](https://github.com/greenkeeperio/greenkeeper/issues/222) ([219ab4f](https://github.com/greenkeeperio/greenkeeper/commit/219ab4f))


### BREAKING CHANGES

* Requires node >=4



<a name="3.0.1"></a>
## [3.0.1](https://github.com/greenkeeperio/greenkeeper/compare/v3.0.0...v3.0.1) (2016-06-20)


### Bug Fixes

* let command line arguments take precedence over scoped config ([cd9688a](https://github.com/greenkeeperio/greenkeeper/commit/cd9688a))
* stop truncating output on newer node versions ([67abf16](https://github.com/greenkeeperio/greenkeeper/commit/67abf16)), closes [#190](https://github.com/greenkeeperio/greenkeeper/issues/190)
* **disable:** error message ([46b3d08](https://github.com/greenkeeperio/greenkeeper/commit/46b3d08))
* **enable:** correct error message when enabling a repo w/o admin access ([9ab3752](https://github.com/greenkeeperio/greenkeeper/commit/9ab3752))
* **login:** automatically persist the API endpoint that was used for login ([b377565](https://github.com/greenkeeperio/greenkeeper/commit/b377565))


### Features

* **manual_webhooks:** optionally removes need for admin scope ([2ddfae7](https://github.com/greenkeeperio/greenkeeper/commit/2ddfae7)), closes [#46](https://github.com/greenkeeperio/greenkeeper/issues/46)


### BREAKING CHANGES

* Before the scoped admin and token took precedence over command line flags.



<a name="2.12.0"></a>
# [2.12.0](https://github.com/greenkeeperio/greenkeeper/compare/v2.11.2...v2.12.0) (2016-05-26)


### Bug Fixes

* publish from node 4 again to work around `npm pack` regression ([37502df](https://github.com/greenkeeperio/greenkeeper/commit/37502df))
* **postpublish:** correctly detect scoped packages ([a26b6b4](https://github.com/greenkeeperio/greenkeeper/commit/a26b6b4))


### Features

* **list:** show all enabled packages ([#188](https://github.com/greenkeeperio/greenkeeper/issues/188)) ([83e8259](https://github.com/greenkeeperio/greenkeeper/commit/83e8259))



<a name="2.11.0"></a>
# [2.11.0](https://github.com/greenkeeperio/greenkeeper/compare/v2.10.0...v2.11.0) (2016-04-29)


### Bug Fixes

* use [@greenkeeper](https://github.com/greenkeeper)/flags package ([c47e3a0](https://github.com/greenkeeperio/greenkeeper/commit/c47e3a0))
* **enable:** improve error message ([dc4964f](https://github.com/greenkeeperio/greenkeeper/commit/dc4964f))


### Features

* **enable:** add postpublish hook on scoped modules ([864add7](https://github.com/greenkeeperio/greenkeeper/commit/864add7))
* **npm:** new commands for giving access to private scoped npm modules ([a7e0d31](https://github.com/greenkeeperio/greenkeeper/commit/a7e0d31))
* **postpublish:** add command that sets up "greenkeeper-postpublish" ([a406b90](https://github.com/greenkeeperio/greenkeeper/commit/a406b90))
* add FAQ command ([88d9a5b](https://github.com/greenkeeperio/greenkeeper/commit/88d9a5b))



<a name="2.10.0"></a>
# [2.10.0](https://github.com/greenkeeperio/greenkeeper/compare/v2.9.1...v2.10.0) (2016-04-13)


### Features

* **login:** include private repositories for enterprise instances, Closes [#167](https://github.com/greenkeeperio/greenkeeper/issues/167) ([b52147d](https://github.com/greenkeeperio/greenkeeper/commit/b52147d))



<a name="2.9.1"></a>
## [2.9.1](https://github.com/greenkeeperio/greenkeeper/compare/v2.9.0...v2.9.1) (2016-04-12)


### Bug Fixes

* **login:** show login URL if "opener" fails ([5a2467e](https://github.com/greenkeeperio/greenkeeper/commit/5a2467e)), closes [#69](https://github.com/greenkeeperio/greenkeeper/issues/69)


### Features

* **alias:** Alias status to info ([0d4c68f](https://github.com/greenkeeperio/greenkeeper/commit/0d4c68f))
* **enable:** Sync when enabling fails, Closes [#113](https://github.com/greenkeeperio/greenkeeper/issues/113) ([1692600](https://github.com/greenkeeperio/greenkeeper/commit/1692600))



<a name="2.7.1"></a>
## [2.7.1](https://github.com/greenkeeperio/greenkeeper/compare/v2.7.0...v2.7.1) (2016-03-01)


### Bug Fixes

* migrate open to opener ([765079c](https://github.com/greenkeeperio/greenkeeper/commit/765079c)), closes [#143](https://github.com/greenkeeperio/greenkeeper/issues/143)


### Features

* **config:** add get, set, delete & list commands ([50ad044](https://github.com/greenkeeperio/greenkeeper/commit/50ad044))
* fail early if api config is not a valid url ([5b3fc45](https://github.com/greenkeeperio/greenkeeper/commit/5b3fc45))



<a name="2.6.0"></a>
# [2.6.0](https://github.com/greenkeeperio/greenkeeper/compare/v2.5.1...v2.6.0) (2016-02-12)


### Bug Fixes

* **organization-access:** handle enterprise API endpoints ([2752ffa](https://github.com/greenkeeperio/greenkeeper/commit/2752ffa))
* consistently use `repository` wording ([c90be30](https://github.com/greenkeeperio/greenkeeper/commit/c90be30))
* enhance log formatting and add color ([3c4f9ad](https://github.com/greenkeeperio/greenkeeper/commit/3c4f9ad))
* log correct missing slug error ([7d18f14](https://github.com/greenkeeperio/greenkeeper/commit/7d18f14))
* only use update-notifier in production ([fe66da6](https://github.com/greenkeeperio/greenkeeper/commit/fe66da6))
* remove load message ([28259e6](https://github.com/greenkeeperio/greenkeeper/commit/28259e6))


### Features

* **alias:** Add init alias for enable ([b60ad24](https://github.com/greenkeeperio/greenkeeper/commit/b60ad24))
* **upgrade:** check if endpoint is greenkeeper enterprise API ([8292dbc](https://github.com/greenkeeperio/greenkeeper/commit/8292dbc))
* use prettier markdown based rendering for long-form log messages (--help/start) ([6129918](https://github.com/greenkeeperio/greenkeeper/commit/6129918))



<a name="2.3.2"></a>
## [2.3.2](https://github.com/greenkeeperio/greenkeeper/compare/v2.3.1...v2.3.2) (2016-01-09)


### Bug Fixes

* **support:** intercom chat is used for paid plans ([8a1e846](https://github.com/greenkeeperio/greenkeeper/commit/8a1e846))



<a name="2.3.1"></a>
## [2.3.1](https://github.com/greenkeeperio/greenkeeper/compare/v2.3.0...v2.3.1) (2015-12-21)


### Bug Fixes

* **enable:** clarify error message for one free private repo ([bb7fe58](https://github.com/greenkeeperio/greenkeeper/commit/bb7fe58))
* **logout:** use correct error message ([a644839](https://github.com/greenkeeperio/greenkeeper/commit/a644839))


### Features

* **organizations-access:** new command to manage access for individual orgs ([140ba30](https://github.com/greenkeeperio/greenkeeper/commit/140ba30))
* **token:** support being logged into multiple greenkeeper instances at the same time ([a497225](https://github.com/greenkeeperio/greenkeeper/commit/a497225))



<a name="2.1.4"></a>
## [2.1.4](https://github.com/greenkeeperio/greenkeeper/compare/v2.1.3...v2.1.4) (2015-10-16)


### Bug Fixes

* **enable:** allow forks ([f075673](https://github.com/greenkeeperio/greenkeeper/commit/f075673))
* **enable:** typo ([732d1d8](https://github.com/greenkeeperio/greenkeeper/commit/732d1d8))



<a name="2.1.3"></a>
## [2.1.3](https://github.com/greenkeeperio/greenkeeper/compare/v2.1.2...v2.1.3) (2015-10-08)


### Bug Fixes

* **travis:** correctly pack tarball ([09628f6](https://github.com/greenkeeperio/greenkeeper/commit/09628f6))



<a name="2.1.2"></a>
## [2.1.2](https://github.com/greenkeeperio/greenkeeper/compare/v2.1.1...v2.1.2) (2015-10-08)


### Bug Fixes

* open payment page deferred ([8000f69](https://github.com/greenkeeperio/greenkeeper/commit/8000f69))
* **enable:** add warning when enabling from repo w/o package.json ([3d16852](https://github.com/greenkeeperio/greenkeeper/commit/3d16852)), closes [#6](https://github.com/greenkeeperio/greenkeeper/issues/6)
* **enable:** clarify 400 error message ([88794ae](https://github.com/greenkeeperio/greenkeeper/commit/88794ae))
* **enable:** use slug if passed via cli ([211bbeb](https://github.com/greenkeeperio/greenkeeper/commit/211bbeb)), closes [#37](https://github.com/greenkeeperio/greenkeeper/issues/37)
* **enable,disable:** improve error message when no "origin" ([1af6094](https://github.com/greenkeeperio/greenkeeper/commit/1af6094))
* **help:** improve output ([6c67a4b](https://github.com/greenkeeperio/greenkeeper/commit/6c67a4b)), closes [#24](https://github.com/greenkeeperio/greenkeeper/issues/24)
* **package:** update github-slug to version 1.0.0 ([e20a79c](https://github.com/greenkeeperio/greenkeeper/commit/e20a79c))
* **start:** automation is not magic :) ([fb8e9ee](https://github.com/greenkeeperio/greenkeeper/commit/fb8e9ee))
* **start:** we update rather than pin dependencies now ([274afca](https://github.com/greenkeeperio/greenkeeper/commit/274afca))


### Features

* **list:** add command that lists enabled repos ([f7581f7](https://github.com/greenkeeperio/greenkeeper/commit/f7581f7)), closes [#25](https://github.com/greenkeeperio/greenkeeper/issues/25)
* **whoami:** add list of orgs and plans ([564af36](https://github.com/greenkeeperio/greenkeeper/commit/564af36))



<a name="2.0.0"></a>
# [2.0.0](https://github.com/greenkeeperio/greenkeeper/compare/v1.6.4...v2.0.0) (2015-09-28)


### Bug Fixes

* **enable, info:** better error message for 400 ([23a55b2](https://github.com/greenkeeperio/greenkeeper/commit/23a55b2))
* **help:** typo ([8dea98d](https://github.com/greenkeeperio/greenkeeper/commit/8dea98d))
* **login:** use public scope by default ([40e2ad4](https://github.com/greenkeeperio/greenkeeper/commit/40e2ad4))
* **login, upgrade:** use public scope by default ([91fd43d](https://github.com/greenkeeperio/greenkeeper/commit/91fd43d))
* **package:** add Apache-2.0 license ([541ee44](https://github.com/greenkeeperio/greenkeeper/commit/541ee44))
* **support:** use correct issue tracker ([935eed1](https://github.com/greenkeeperio/greenkeeper/commit/935eed1))
* **whitespace:** typo ([f5f9810](https://github.com/greenkeeperio/greenkeeper/commit/f5f9810))


### BREAKING CHANGES

* **login:** Before `login` requested access to private repositories by
default and switched to public-only using `--public-only`. This behavior is
now reversed. `login` requests access to public repos and can be upgraded to
private ones using `--private`. The upgrade command automatically sends you to
GitHub to upgrade the scopes before sending to the payment provider.
* **login, upgrade:** Before `login` requested access to private repositories by
default and switched to public-only using `--public-only`. This behavior is
now reversed. `login` requests access to public repos and can be upgraded to
private ones using `--private`. The upgrade command automatically sends you to
GitHub to upgrade the scopes before sending to the payment provider.



<a name="1.6.1"></a>
## [1.6.1](https://github.com/greenkeeperio/greenkeeper/compare/v1.6.0...v1.6.1) (2015-09-26)


### Bug Fixes

* Changed from quote to apostrophe. ([064c032](https://github.com/greenkeeperio/greenkeeper/commit/064c032))
* update whoami messaging ([13bb152](https://github.com/greenkeeperio/greenkeeper/commit/13bb152))



<a name="1.6.0"></a>
# [1.6.0](https://github.com/greenkeeperio/greenkeeper/compare/v1.5.3...v1.6.0) (2015-09-26)


### Bug Fixes

* Typo ([0dd6f40](https://github.com/greenkeeperio/greenkeeper/commit/0dd6f40))


### Features

* **upgrade:** add money-back policy to upgrade command ([079c232](https://github.com/greenkeeperio/greenkeeper/commit/079c232))



<a name="1.5.3"></a>
## [1.5.3](https://github.com/greenkeeperio/greenkeeper/compare/v1.5.2...v1.5.3) (2015-09-26)


### Bug Fixes

* typo ([259182e](https://github.com/greenkeeperio/greenkeeper/commit/259182e))



<a name="1.5.2"></a>
## [1.5.2](https://github.com/greenkeeperio/greenkeeper/compare/v1.5.1...v1.5.2) (2015-09-25)


### Bug Fixes

* add readme ([5cbbe29](https://github.com/greenkeeperio/greenkeeper/commit/5cbbe29))



<a name="1.5.1"></a>
## [1.5.1](https://github.com/greenkeeperio/greenkeeper/compare/v1.5.0...v1.5.1) (2015-09-25)


### Bug Fixes

* **upgrade:** better log ([85e21af](https://github.com/greenkeeperio/greenkeeper/commit/85e21af))



<a name="1.5.0"></a>
# [1.5.0](https://github.com/greenkeeperio/greenkeeper/compare/v1.4.0...v1.5.0) (2015-09-25)


### Bug Fixes

* **upgrade:** payment routes ([726fe31](https://github.com/greenkeeperio/greenkeeper/commit/726fe31))


### Features

* **fastspring:** send org in to upgrade route on webservice ([5daf351](https://github.com/greenkeeperio/greenkeeper/commit/5daf351))
* **login:** add "--public-only" flag ([21e5b97](https://github.com/greenkeeperio/greenkeeper/commit/21e5b97))
* **payments:** add `greenkeeper buy options` ([ad766cc](https://github.com/greenkeeperio/greenkeeper/commit/ad766cc))
* **payments:** add cli longpolling to fastspring dance ([5643873](https://github.com/greenkeeperio/greenkeeper/commit/5643873))
* **upgrade:** move upgrade redirect to webservice ([f3458f8](https://github.com/greenkeeperio/greenkeeper/commit/f3458f8))
* **upgrade:** send token, random id and orgs, rebase to master ([26887d4](https://github.com/greenkeeperio/greenkeeper/commit/26887d4))



<a name="1.3.3"></a>
## [1.3.3](https://github.com/greenkeeperio/greenkeeper/compare/v1.3.2...v1.3.3) (2015-09-24)


### Bug Fixes

* read slug from remote "origin" ([6f03254](https://github.com/greenkeeperio/greenkeeper/commit/6f03254))
* remove beta, add "too much load" warning on unexpected fails ([932a6ac](https://github.com/greenkeeperio/greenkeeper/commit/932a6ac))
* remove debug log ([703ff7e](https://github.com/greenkeeperio/greenkeeper/commit/703ff7e))



<a name="1.3.1"></a>
## [1.3.1](https://github.com/greenkeeperio/greenkeeper/compare/v1.3.0...v1.3.1) (2015-09-24)


### Bug Fixes

* **whitespace:** typo ([947860b](https://github.com/greenkeeperio/greenkeeper/commit/947860b))



<a name="1.3.0"></a>
# [1.3.0](https://github.com/greenkeeperio/greenkeeper/compare/v1.2.1...v1.3.0) (2015-09-24)


### Features

* **login:** retry longpoll request ([e4443ec](https://github.com/greenkeeperio/greenkeeper/commit/e4443ec))



<a name="1.2.1"></a>
## [1.2.1](https://github.com/greenkeeperio/greenkeeper/compare/v1.2.0...v1.2.1) (2015-09-24)


### Bug Fixes

* install all dependencies ([db4dd40](https://github.com/greenkeeperio/greenkeeper/commit/db4dd40))



<a name="1.2.0"></a>
# [1.2.0](https://github.com/greenkeeperio/greenkeeper/compare/v1.1.0...v1.2.0) (2015-09-24)


### Features

* **update:** add update notification ([ae1ead6](https://github.com/greenkeeperio/greenkeeper/commit/ae1ead6))



<a name="1.1.0"></a>
# [1.1.0](https://github.com/greenkeeperio/greenkeeper/compare/v1.0.2...v1.1.0) (2015-09-24)


### Bug Fixes

* **help:** typos ([1b238a3](https://github.com/greenkeeperio/greenkeeper/commit/1b238a3))


### Features

* **help:** detailed command help information ([e598943](https://github.com/greenkeeperio/greenkeeper/commit/e598943))
* **start:** add getting started docs, various help fixes ([c806606](https://github.com/greenkeeperio/greenkeeper/commit/c806606))



<a name="1.0.2"></a>
## [1.0.2](https://github.com/greenkeeperio/greenkeeper/compare/v1.0.1...v1.0.2) (2015-09-24)


### Bug Fixes

* improve experience as per roberts feedback ([9d904a9](https://github.com/greenkeeperio/greenkeeper/commit/9d904a9))



<a name="1.0.1"></a>
## [1.0.1](https://github.com/greenkeeperio/greenkeeper/compare/v1.0.0...v1.0.1) (2015-09-23)


### Bug Fixes

* **npmignore:** not ignoring the actual code ¯\_(ツ)_/¯ ([e3ec937](https://github.com/greenkeeperio/greenkeeper/commit/e3ec937))
* **package:** add correct metadata ([be9daaa](https://github.com/greenkeeperio/greenkeeper/commit/be9daaa))
* **package:** add repo for semantic-release ([3fafe17](https://github.com/greenkeeperio/greenkeeper/commit/3fafe17))



<a name="1.0.0"></a>
# [1.0.0](https://github.com/greenkeeperio/greenkeeper/compare/c1711e2...v1.0.0) (2015-09-23)


### Bug Fixes

* **cli:** correctly show help w/o command ([fdc9d7d](https://github.com/greenkeeperio/greenkeeper/commit/fdc9d7d))
* **cli:** not failing w/o command ([d8948b9](https://github.com/greenkeeperio/greenkeeper/commit/d8948b9))
* **disable,enable:** log if no change happened ([8f89f1b](https://github.com/greenkeeperio/greenkeeper/commit/8f89f1b))
* **login:** fix message ([bf6d8df](https://github.com/greenkeeperio/greenkeeper/commit/bf6d8df))
* **login:** no es6 string interpolation in client, fix typo ([56f23e0](https://github.com/greenkeeperio/greenkeeper/commit/56f23e0))
* **login:** use console.log instaed of log.info ([b80f976](https://github.com/greenkeeperio/greenkeeper/commit/b80f976))
* **package:** add bin ([0ccd198](https://github.com/greenkeeperio/greenkeeper/commit/0ccd198))
* **package:** add missing packages ([2691858](https://github.com/greenkeeperio/greenkeeper/commit/2691858))
* **whoami:** log error ([41989bd](https://github.com/greenkeeperio/greenkeeper/commit/41989bd))
* boennemann/greenkeeper-webservice[#23](https://github.com/greenkeeperio/greenkeeper/issues/23) ([85fdb11](https://github.com/greenkeeperio/greenkeeper/commit/85fdb11))
* use emojis only on mac ([5baa3f3](https://github.com/greenkeeperio/greenkeeper/commit/5baa3f3))
* various improvements/consistency around logs ([391ac83](https://github.com/greenkeeperio/greenkeeper/commit/391ac83))


### Features

* add enable/disable commands ([eb0ee23](https://github.com/greenkeeperio/greenkeeper/commit/eb0ee23))
* add info command ([ec51400](https://github.com/greenkeeperio/greenkeeper/commit/ec51400))
* add logout command ([c4f2e35](https://github.com/greenkeeperio/greenkeeper/commit/c4f2e35))
* add rc getter and setter ([6c6fac1](https://github.com/greenkeeperio/greenkeeper/commit/6c6fac1))
* add upgrade/downgrade dummies, fix help, better errors ([530f32e](https://github.com/greenkeeperio/greenkeeper/commit/530f32e))
* initial cli structure ([c1711e2](https://github.com/greenkeeperio/greenkeeper/commit/c1711e2))
* merge cli flags with rcfile ([c730e01](https://github.com/greenkeeperio/greenkeeper/commit/c730e01))
* top secret stuff ([b28f018](https://github.com/greenkeeperio/greenkeeper/commit/b28f018))
* **cli:** alias `gk` for `greenkeeper` on the cli ([abc9235](https://github.com/greenkeeperio/greenkeeper/commit/abc9235))
* **login:** better formatted error messages ([aa55283](https://github.com/greenkeeperio/greenkeeper/commit/aa55283))
* **login:** better formatted error messages ([160a009](https://github.com/greenkeeperio/greenkeeper/commit/160a009))
* **login:** implement login ([078226b](https://github.com/greenkeeperio/greenkeeper/commit/078226b))
* **login:** sync after login ([cee476b](https://github.com/greenkeeperio/greenkeeper/commit/cee476b))
* **login,sync:** add spinner ([898435d](https://github.com/greenkeeperio/greenkeeper/commit/898435d))
* **msg:** define messages and errors in separate module ([3fbca73](https://github.com/greenkeeperio/greenkeeper/commit/3fbca73))
* **support:** add support command ([fcc92d9](https://github.com/greenkeeperio/greenkeeper/commit/fcc92d9))
* **sync:** add command ([4653ec4](https://github.com/greenkeeperio/greenkeeper/commit/4653ec4))
* **whoami:** initial implementation ([5ba6066](https://github.com/greenkeeperio/greenkeeper/commit/5ba6066))
