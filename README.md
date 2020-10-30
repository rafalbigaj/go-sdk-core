[![Build Status](https://travis-ci.com/IBM/go-sdk-core.svg?branch=master)](https://travis-ci.com/IBM/go-sdk-core)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)[![CLA assistant](https://cla-assistant.io/readme/badge/ibm/go-sdk-core)](https://cla-assistant.io/ibm/go-sdk-core)

# IBM Go SDK Core Version 4.8.1
This project contains core functionality required by Go code generated by the IBM Cloud OpenAPI SDK Generator
(openapi-sdkgen).

## Installation

Get SDK package:
```bash
go get -u github.com/IBM/go-sdk-core/...
```

## Prerequisites
- Go version 1.12 or newer

## Authentication
The go-sdk-core project supports the following types of authentication:
- Basic Authentication
- Bearer Token 
- Identity and Access Management (IAM)
- Cloud Pak for Data
- No Authentication

For more information about the various authentication types and how to use them with your services, click [here](Authentication.md)

## Issues

If you encounter an issue with this project, you are welcome to submit a [bug report](https://github.com/IBM/go-sdk-core/issues).
Before opening a new issue, please search for similar issues. It's possible that someone has already reported it.

## Tests

To build, test and lint-check the project:
```bash
make all
```

Get code coverage for each test suite:
```bash
go test -coverprofile=coverage.out ./...
go tool cover -html=coverage.out
```

## Contributing

See [CONTRIBUTING](CONTRIBUTING.md).

## License

This library is licensed under Apache 2.0. Full license text is
available in [LICENSE](LICENSE.md).
