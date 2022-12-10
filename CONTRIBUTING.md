# Contributing

Thanks for considering contributing and making our planet easier to explore!

We're excited you would like to contribute to Cumulus! Whether you're finding bugs, adding new features, fixing anything broken, or improving documentation, get started by submitting an issue or pull request!

## Submitting an Issue

If you have any questions or ideas, or notice any problems or bugs, first [search open issues](https://github.com/nasa/cumulus-message-adapter-js/issues) to see if the issue has already been submitted. We may already be working on the issue. If you think your issue is new, you're welcome to [create a new issue](https://github.com/nasa/cumulus-message-adapter-js/issues/new).

## Development

### CMA binary

Tests of this package require a binary distribution of the cumulus-message-adapter

If your test environment is similar to the AWS Linux 2 runtime environment, then
the test will pull the latest distribution of the [Cumulus Message
Adapter](https://github.com/nasa/cumulus-message-adapter) with a pre-compiled
binary built in for testing.

If you're developing on a different platform/environment, you'll need to
download the CMA and build a local `cumulus-message-adapter.zip`, then specify
it's location in your `LOCAL_CMA_ZIP_FILE` environment variable:

```bash
export LOCAL_CMA_ZIP_FILE='/my/workspace/cma/cumulus-message-adapter.zip`
```

## Pull Requests

If you want to submit your own contributions, follow these steps;

* Fork the cumulus-message-adapter-js repo
* Create a new branch from the branch you'd like to contribute to
* If an issue does't already exist, submit one (see above)
* [Create a pull request](https://help.github.com/articles/creating-a-pull-request/) from your fork into the target branch of the nasa/cumulus-message-adapter-js repo
* Be sure to [mention the corresponding issue number](https://help.github.com/articles/closing-issues-using-keywords/) in the PR description, i.e. "Fixes Issue #10"
* Upon submission of a pull request, the Cumulus development team will review the code
* The request will then either be merged, declined, or an adjustment to the code will be requested

## Guidelines

We ask that you follow these guidelines with your contributions;

### Tests

All of the automated tests for this project need to pass before your submission will be accepted. You can run `npm test` in the command line after making changes to verify that the tests pass. If you add new functionality, please consider adding tests for that functionality as well.

### Commits

* Make small commits that show the individual changes you are making
* Write descriptive commit messages that explain your changes

Example of a good commit message:

```text
Improve contributing guidelines. Fixes #10

Improve contributing docs and consolidate them in the standard location https://help.github.com/articles/setting-guidelines-for-repository-contributors/
```

### For more information on Cumulus governance, see the [Cumulus Code Contribution Guidelines](https://docs.google.com/document/d/14J_DS6nyQ32BpeVjdR-YKfzHAzFB299tKghPGshXUTU/edit) and the [Cumulus Wiki](https://wiki.earthdata.nasa.gov/display/CUMULUS/Cumulus).
