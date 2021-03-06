# Contributing to this project

Transparency is one of our core values, and we encourage developers to contribute and become part of the developer community.

The following is a set of guidelines for contributing,

These are just guidelines, not rules, use your best judgment and feel free to

propose changes to this document in a pull request.

## Submitting Issues

* Before logging an issue, please [search existing issues](https://github.com/AbdelouahabMbarki/postman-collection/issues?q=is%3Aissue+is%3Aopen+n) first.

* You can create an issue [here](https://github.com/AbdelouahabMbarki/postman-collection/issues/new).  Please include the version number, as per [the changeLog](CHANGELOG.md) and as much detail as possible in your report.

## Local Development and Testing

1. Fork this repo
1. Clone your fork
1. Import the JSON file into Postman, choosing to "replace" any existing collection of the same name
1. Make and test your changes
1. When you are ready, export your changes from Postman back to the repo JSON file, selecting file version 2.1
1. Compare the differences using a file-compare utility, to ensure no unexpected changes and no private API key info present
1. Please follow the pull request submission steps in the next section

## Contribution Steps

To contribute to ks-devops-api-postman-collection:

1. Create a new branch named after the issue you’ll be fixing, and include the issue number as the branch name, example: Issue in GH is #6 then the branch name should be ISSUE-6
1. Submit a new Pull Request applying your feature/fix branch to the `master` branch

### Releasing

To publish a new release:

1. Update the [ChangeLog](CHANGELOG.md)
1. The Internal team releases and publishes