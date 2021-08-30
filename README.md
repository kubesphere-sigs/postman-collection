<img src="https://kubesphere.io/images/logo.svg" alt="logo" width="300" height="auto"/>

# ks-devops API Postman collection

Postman Collection demonstrating how to use the [ks-devops](https://github.com/kubesphere/ks-devops) REST API.
More information about the API can be found on [https://kubesphere.io/api/kubesphere/#tag/DevOps-Pipeline](https://kubesphere.io/api/kubesphere/#tag/DevOps-Pipeline).

## Installation

To use the latest published version, click the following button to import the ks-devops API as a collection:

[![Run in Postman](https://s3.amazonaws.com/postman-static/run-button.png)](https://app.getpostman.com/run-collection/2027193-fe0a5d67-8247-491b-b1e4-f4d60f8e3364)

You can also download the collection file from this repo, then import directly into Postman.

### Prerequisites

- *Postman* The collection is for use by the Postman app. Postman is a utility that allows you to quickly test and use REST APIs. More information can be found at [getpostman.com](https://www.getpostman.com/).
- *ks-devops API Token* To use the API, you must have an API Token Please get a token from Kubernetes cluster .

## Usage

The collection is arranged in folders according to the API endpoints.

Almost all requests require a valid ks-devops API Token.  The collection requests have a placeholder variable called `token` for this.
This should be set in your [Postman environment](https://www.getpostman.com/docs/v6/postman/environments_and_globals/manage_environments) i.e. outside the collection itself. This should help avoid accidental commits of API token to repos.

A collection-scope variable `base_url` points to the usual host `http://localhost:9090`.

ks-devops Postman environments and variables can be found [here](environment/ks-devops.postman_environment.json).

More information on managing Postman environments and variables can be found [here](https://www.getpostman.com/docs/v6/postman/environments_and_globals/variables).

|Variable     |Default value               |Set in         |May override in  |Example|
|-------------|----------------------------|---------------|-----------------|-------|
|`token`      |-                           |Environment    |-                |-      |
|`base_url`   |`http://localhost:9090`     |Environment    |Environment      |`      `|
|`devops`     |                            |Environment    |Environment      |`      `|
|`credential` |                            |Environment    |Environment      |`      `|

### Contribute

We welcome your contributions!  See [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to help out.

### Change Log

[See ChangeLog here](CHANGELOG.md)

## See Also

[ks-devops API documentation](https://kubesphere.io/api/kubesphere/#tag/DevOps-Pipeline)

[Postman API development tool](https://www.getpostman.com/)