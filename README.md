# SQA Integration Tester

SQA Integration Tester deploys OpenStack clouds in the SQA lab by translating
between zuul and weebl (solutions.qa.canonical.com).

### Running tests
Tests are run using the foundations cloud engine (FCE), which is configured using project branches. The project branches that are maintained by SQA are keps in [solutions-qa-deployments](https://code.launchpad.net/solutions-qa-deployments). Custom projects can be made by pointing the tests to a different repository.

### Debugging tests
Completed test runs are documented in weebl. Go to `https://solutions.qa.canonical.com/v2/testruns/{testrun-uuid}` to find details about the test runs as well as logs which can be used for debugging failures.
