# Example Discourse Thingy

An example workflow setup which runs workflows when monitored Discourse branches receive new commits.
This could be used to regulary run the test suite against those Discourse branches when they are updated.
Using badges in the readme users of this plugin/theme component could easily check if the tests passed with the recent changes of that branch.

It sort of assumes the plugin/theme component project has been set up to use the Discourse Github Actions templats: https://github.com/discourse/.github/tree/main/.github/workflows

# Compatibility Status

This plugin/theme component's test suite has been run against the following Discourse branches:

[![Discourse stable](https://github.com/elmuerte/wf-test/actions/workflows/stable.yml/badge.svg)](https://github.com/elmuerte/wf-test/actions/workflows/stable.yml)

[![Discourse tests-passed](https://github.com/elmuerte/wf-test/actions/workflows/tests-passed.yml/badge.svg)](https://github.com/elmuerte/wf-test/actions/workflows/tests-passed.yml)
