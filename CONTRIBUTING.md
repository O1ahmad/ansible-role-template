# Contributing Guidelines

:heavy_check_mark::tada: Let's make code better together - Thanks for taking the time to contribute! :tada::heavy_check_mark:

The following is a set of guidelines for contributing to *0x0I Ansible roles*, which are hosted under the [0x0I](https://github.com/0x0I?tab=repositories) developer account on GitHub. These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

For general information and guidelines for contributing to these roles and the Ansible community, see the [community page](https://docs.ansible.com/ansible/latest/community/).

**Table of Contents**
  - [Pull Requests](#pull-requests)
      - [CI Pipeline](#ci-pipeline)
  - [Issues](#issues)
      - [Issue Types](#issue-types)
  - [Workflow and backlog](#workflow-and-backlog)
  - [Code of Conduct](#code-of-conduct)

## Pull Requests

This repository encourages [PRs](https://github.com/0x0I/ansible-role-template/pulls) and provides the following guidelines and CI pipeline for validating role functionality and avoiding regressions:

#### CI Pipeline

| Test | Description |
| --- | --- |
| :zap: `yamllint` | Validates `yaml` adheres to coding standards and best practices as [configured](https://github.com/0x0I/ansible-role-template/blob/master/test/lint/yaml-lint.yml). |
| :zap: `ansible-lint` | Validates ansible module and construct usage adheres to Ansible standards and practices as [configured](https://github.com/0x0I/ansible-role-template/blob/master/test/lint/.ansible-lint). |
| :wrench: `integration testing` | utilizing Chef's [test-kitchen](https://docs.chef.io/kitchen.html) framework and the [kitchen-ansible](https://github.com/neillturner/kitchen-ansible) provisioner, integration testing of this role is organized according to the various provisioning phases and should be executed prior to PR submission to validate new modifications and identify/prevent regressions. |
| :traffic_light: `Continuous Integration (CI)` | Automatic E2E testing of this role is accomplished leveraging the [Travis-CI](https://travis-ci.com/0x0I/ansible-role-template) test infrastructure platform and is executed on each pull request. Requests should not be merged unless all tests pass or the community approves otherwise. |

## Issues

New GitHub issues can be [opened](https://github.com/0x0I/ansible-role-template/issues/new) and [tracked](https://github.com/0x0I/ansible-role-template/issues) in a similar fashion as with most Github repositories by making use of the standard Github issue management facilities.

Reference the following issue reporting guide for more details:

#### Issue Types

| Issue Type | Description |
| --- | --- |
| :arrow_up: `:enhancement:` | Feature requests. |
| :bug: `:bug:` | Confirmed bugs or reports that are very likely to be bugs. |
| :question: `:question:` | Questions more than bug reports or feature requests (e.g. how do I do X). |
| :eyeglasses: :heartpulse:`:feedback:` | General feedback more than bug reports or feature requests. |

## Workflow and backlog

Reference this repository's [wiki](https://github.com/0x0I/ansible-role-template/wiki) to visualize the project roadmap, workflow and backlog to stay up to speed with development  plans and work in progress.

## Code of Conduct

See the [Ansible Code of Conduct](https://docs.ansible.com/ansible/latest/community/code_of_conduct.html).
