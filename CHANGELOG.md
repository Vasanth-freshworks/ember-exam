
v3.0.0 / 2019-04-08
===================

* [Feature - Breaking] Introduce TestLoadBalancing <@choheekim> & <step2yeung>

You will need to **replace** the use of `start()` from `Ember-Qunit` or `Ember-Mocha` in `test-helper.js` with `start()` from `ember-exam`:

```js
// test-helper.js
import start from 'ember-exam/test-support/start';

// Options passed to `start` will be passed-through to ember-qunit or ember-mocha
start();
```

This breaking change was motivated by wanting to remove the monkey-patching, of ember-qunit and ember-mocha's test-loader, ember exam was doing.

* [Bugfix] Ensure serialized test-execution browserId's are always treated as a string https://github.com/ember-cli/ember-exam/pull/233
* [Bugfix] fix breaking change: https://github.com/ember-cli/ember-exam/pull/242 (@step2yeung)
* [Enhancement] Prettify test-execution.json (@step2yeung)
* Bump ember-qunit from 4.4.0 to 4.4.1 (4 weeks ago) <dependabot[bot]>
* Bump ember-resolver from 5.1.2 to 5.1.3 (4 weeks ago) <dependabot[bot]>
* Bump testdouble from 3.10.0 to 3.11.0 (4 weeks ago) <dependabot[bot]>
* Bump ember-cli-babel from 7.4.3 to 7.5.0 (4 weeks ago) <dependabot[bot]>
* Bump ember-resolver from 5.1.1 to 5.1.2 (5 weeks ago) <dependabot[bot]>
* Bump mocha from 6.0.0 to 6.0.1 (5 weeks ago) <dependabot[bot]>
* Bump ember-cli-babel from 7.4.2 to 7.4.3 (5 weeks ago) <dependabot[bot]>
* Bump ember-qunit from 4.3.0 to 4.4.0 (5 weeks ago) <dependabot[bot]>
* Bump mocha from 5.2.0 to 6.0.0 (5 weeks ago) <dependabot[bot]>
* Bump ember-source from 3.7.3 to 3.8.0 (5 weeks ago) <dependabot[bot]>
* Bump sinon from 7.2.3 to 7.2.4 (5 weeks ago) <dependabot[bot]>
* Bump nyc from 13.2.0 to 13.3.0 (6 weeks ago) <dependabot[bot]>
* [Security] Bump handlebars from 4.0.12 to 4.1.0 (6 weeks ago) <dependabot[bot]>
* Bump ember-cli-babel from 7.4.1 to 7.4.2 (6 weeks ago) <dependabot[bot]>
* Bump ember-source from 3.7.2 to 3.7.3 (7 weeks ago) <dependabot[bot]>
* Bump ember-qunit from 4.2.0 to 4.3.0 (7 weeks ago) <dependabot[bot]>
* Bump nyc from 13.1.0 to 13.2.0 (7 weeks ago) <dependabot[bot]>
* Bump testdouble from 3.9.3 to 3.10.0 (7 weeks ago) <dependabot[bot]>
* Bump ember-cli-babel from 7.4.0 to 7.4.1 (8 weeks ago) <dependabot[bot]>
* Bump eslint-plugin-ember from 6.1.0 to 6.2.0 (8 weeks ago) <dependabot[bot]>


v2.1.5 / 2019-04-08
===================

* re-release 2.0.3 as 2.1.5, as 2.0.4...2.1.4 introduced a worth-while but unexpected breaking change. 2.0.4...2.1.4 will be re-released as 3.x


v2.1.4 / 2019-03-27
===================

* [Bugfix] Ensure serialized test-execution browserId's are always treated as a string https://github.com/ember-cli/ember-exam/pull/233

v2.1.3 / 2019-03-27
===================

* [Bugfix] fix breaking change: https://github.com/ember-cli/ember-exam/pull/242 (@step2yeung)
* [Enhancement] Prettify test-execution.json (@step2yeung)

v2.1.0 / 2019-03-27
===================

* [Feature] Introduce TestLoadBalancing <@choheekim> & <step2yeung>
* Bump ember-qunit from 4.4.0 to 4.4.1 (4 weeks ago) <dependabot[bot]>
* Bump ember-resolver from 5.1.2 to 5.1.3 (4 weeks ago) <dependabot[bot]>
* Bump testdouble from 3.10.0 to 3.11.0 (4 weeks ago) <dependabot[bot]>
* Bump ember-cli-babel from 7.4.3 to 7.5.0 (4 weeks ago) <dependabot[bot]>
* Bump ember-resolver from 5.1.1 to 5.1.2 (5 weeks ago) <dependabot[bot]>
* Bump mocha from 6.0.0 to 6.0.1 (5 weeks ago) <dependabot[bot]>
* Bump ember-cli-babel from 7.4.2 to 7.4.3 (5 weeks ago) <dependabot[bot]>
* Bump ember-qunit from 4.3.0 to 4.4.0 (5 weeks ago) <dependabot[bot]>
* Bump mocha from 5.2.0 to 6.0.0 (5 weeks ago) <dependabot[bot]>
* Bump ember-source from 3.7.3 to 3.8.0 (5 weeks ago) <dependabot[bot]>
* Bump sinon from 7.2.3 to 7.2.4 (5 weeks ago) <dependabot[bot]>
* Bump nyc from 13.2.0 to 13.3.0 (6 weeks ago) <dependabot[bot]>
* [Security] Bump handlebars from 4.0.12 to 4.1.0 (6 weeks ago) <dependabot[bot]>
* Bump ember-cli-babel from 7.4.1 to 7.4.2 (6 weeks ago) <dependabot[bot]>
* Bump ember-source from 3.7.2 to 3.7.3 (7 weeks ago) <dependabot[bot]>
* Bump ember-qunit from 4.2.0 to 4.3.0 (7 weeks ago) <dependabot[bot]>
* Bump nyc from 13.1.0 to 13.2.0 (7 weeks ago) <dependabot[bot]>
* Bump testdouble from 3.9.3 to 3.10.0 (7 weeks ago) <dependabot[bot]>
* Bump ember-cli-babel from 7.4.0 to 7.4.1 (8 weeks ago) <dependabot[bot]>
* Bump eslint-plugin-ember from 6.1.0 to 6.2.0 (8 weeks ago) <dependabot[bot]>

v2.0.3 / 2019-01-22
===================

* ignore .nyc_output

v2.0.2 / 2019-01-22
===================

* Bump chalk from 2.4.1 to 2.4.2
* Bump debug from 4.1.0 to 4.1.1
* Bump ember-cli from 3.5.1 to 3.7.1
* Bump ember-cli-babel from 7.1.4 to 7.4.0
* Bump ember-cli-dependency-checker from 3.0.0 to 3.1.0
* Bump ember-cli-htmlbars-inline-precompile from 2.0.0 to 2.1.0
* Bump ember-qunit from 4.1.2 to 4.2.0
* Bump ember-source from 3.6.0 to 3.7.2
* Bump ember-template-lint from 0.8.23 to 1.1.0
* Bump eslint-plugin-ember from 6.0.1 to 6.1.0
* Bump eslint-plugin-node from 8.0.0 to 8.0.1
* Bump rimraf from 2.6.2 to 2.6.3
* Bump sinon from 7.1.1 to 7.2.3
* Bump testdouble from 3.9.1 to 3.9.3
* Run test:all to trigger ember & node test in ci, add missing single quote, and change number of tests running
* `setResolver()` from `@ember/test-helpers`

v2.0.1 / 2018-12-07
===================

  * ember-exam now sets `process.env.EMBER_EXAM_SPLIT_COUNT`, this allows testem scripts to pick up this configuration via `parallel: process.env.EMBER_EXAM_SPLIT_COUNT`

v2.0.0 / 2018-12-04
===================

  * Bump Node support to: ^6.14.0 || ^8.10.0 || >= 10.*
  * Update/Modernize all dependencies
  * Update/Modernize codebase
  * tranisition from ember-cli-qunit to ember-qunit

v1.0.0 / 2017-11-02
==================

==================

  * Remove auto-loading functionality
  * Update readme to better emphasize explicit loading

v0.8.1 / 2017-10-08
==================

  * Warn when auto-loading (deprecation)
  * Remove `#` from test output.

v0.8.0 / 2017-10-04
==================

  * Removed EMBER_TRY_SCENARIO's from .travis.yml file
  * Fix ESLint warning
  * Fix mocha integration
  * Revert `npm install` command in .travis.yml
  * Upgrade all dependencies version
  * Upgrade Ember CLI to version 2.15 and align with default blueprint

v0.7.2 / 2017-10-01
==================

  * fixes #109 - use local ember

v0.7.1 / 2017-09-14
==================

  * Make notes about turning on parallelization more visible
  * Move note on >= 0.7.0 into installation section
  * Add installation instructions
  * Remove jQuery usage
  * Specify when to call loadEmberExam when using ember-cli-qunit@4
  * fix version range
  * Add release process notes

v0.7.0 / 2017-06-01
==================

  * Document load API for version 0.7.0
  * Fix eslint errors for node-land code
  * Refactor core functionality
  * Extract TestLoader mods into utility function
  * Simplify and revamp code coverage
  * Fix tests from ESLint migration
  * Replace JSHint with ESLint
  * Tweak CI configs
  * Change ember try:one -> ember try:each
  * Remove Node 0.12 from Travis
  * Add Node LTS versions 4.x, 6.x, and stable to Travis

v0.6.2 / 2017-04-09
==================

  * Downgrade split < 2 error to warning
  * Fix mocha test commands


v0.6.1 / 2017-03-25
===================

  * Ensure iterate exits with proper code
  * Add Ember Exam video link to Readme
  * Add note about using random with a seed
  * Fix seed logging message for random option

v0.6.0 / 2016-11-27
===================

  * Close code coverage gap
  * Update README to include Mocha info
  * Add framework-specific logic
  * Run both Mocha and QUnit tests in CI
  * Add tests for ember-cli-mocha
  * Remove moduleForAcceptance
  * Move QUnit-based tests to sub-directory
  * Remove reliance on QUnit for handling url params

v0.5.3 / 2016-11-19
===================

  * Fixed issue with using a single partition with a double digit

v0.5.2 / 2016-11-15
===================

  * Support specifying multiple partitions (#63)

v0.5.1 / 2016-11-14
===================

  * move rimraf to dependencies from devDependencies
  * Add note about test splitting balancing

v0.5.0 / 2016-08-14
===================

  * Document randomization-iterator
  * Add tests for randomization-iterator
  * Rename main acceptance test to be semantic
  * Introduce exam:iterate command
  * Tighten up npmignore
  * Clarify README typos
  * Increase mass threshold for code climate
  * Improve acceptance test coverage
  * Improve advanced configuration section of readme

v0.4.6 / 2016-08-07
===================

  * Don't run Travis on non-master branches
  * Read in testem config for constructing test page urls

v0.4.5 / 2016-08-03
===================

  * Fix node tests after core-object changes
  * Fix tests of ember-exam in 2.7
  * Upgrade all deps to align with Ember 2.7.0.
  * Temporarily undocument `--weighted`.
  * Setup and document ember-try integration

v0.4.4 / 2016-06-21
===================

  * Remove unused dependencies
  * Make codeclimate and eslint configs local
  * Make requires lazy where possible
  * Remove unused Array utilities
  * Add CodeClimate badges to README
  * Setup Istanbul code coverage for node code
  * Fix issues found via CodeClimate
  * Fix Travis badge to point to master
  * Add additional badges to README

v0.4.3 / 2016-06-05
===================

  * Add Acceptance test for Testem output
  * Add partition number to Testem output only when applicable
  * Handle _split and _partition params as strings
  * Fix typo, partition -> _partition

v0.4.2 / 2016-06-02
===================

  * Introduce tests for TestLoader
  * Add useful errors to TestLoader
  * Don't fail when lint tests are disabled

v0.4.1 / 2016-05-24
===================

  * Fix super callbacks context

v0.4.0 / 2016-05-24
===================

  * Remove AST manipulations and refine API
