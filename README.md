# Docker docker-postgres

[![Build Status](https://travis-ci.org/dgnest/docker-postgres.svg)](https://travis-ci.org/dgnest/docker-postgres)
[![GitHub issues](https://img.shields.io/github/issues/dgnest/docker-postgres.svg)](https://github.com/dgnest/docker-postgres/issues)
[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](LICENSE)


Requirements
------------

None


## Dependencies

none

## License

MIT

## Environment Variables

This is a list of the available environment variables which can be set at runtime using -e KEY=value.
For example, to change the default password you can issue `docker run -P --name postgresql -e POSTGRES_PASSWORD=mysecretpassword dgnest/postgres`

* `POSTGRES_USER`: A superuser role. default: `postgres`
* `POSTGRES_PASSWORD`: The password for the user. default: `postgres`
* `POSTGRES_DB`: Name of schema to create. default: `postgres`
* `POSTGRES_TEST_USER`: A test superuser role. default: `postgres`
* `POSTGRES_TEST_PASSWORD`: The password for the user. default: `postgres`
* `POSTGRES_TEST_DB`: Name of schema to create. default: `postgres_test`

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Credits

Made with :heart: :coffee: and :pizza: by [dgnest][link-company]

- [All Contributors][link-contributors]

[link-company]: https://github.com/dgnest
[link-author]: https://github.com/luismayta
[link-contributors]: AUTHORS