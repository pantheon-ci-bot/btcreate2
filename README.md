# btcreate2

[![CircleCI](https://circleci.com/gh/pantheon-systems/example-drops-8-composer.svg?style=svg)](https://circleci.com/gh/pantheon-ci-bot/btcreate2) [![Pantheon btcreate2](https://img.shields.io/badge/pantheon-btcreate2-yellow.svg)](https://dashboard.pantheon.io/sites/3e9c8bc1-011f-4db8-bfb4-10dba5ea3b19#dev/code) [![Dev Site btcreate2](https://img.shields.io/badge/site-btcreate2-blue.svg)](http://dev-btcreate2.pantheonsite.io/)

## IMPORTANT NOTE

At the time of creation, the Pantheon site being used for testing did not have multidev capability. The test suites were therefore configured to run all tests against the dev environment. If the test site is later given multidev capabilities, you must [visit the CircleCI environment variable configuration page](https://circleci.com/gh/pantheon-ci-bot/btcreate2) and delete the environment variable `TERMINUS_ENV`. If you do this, then the test suite will create a new multidev environment for every pull request that is tested.