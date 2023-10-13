# Test data for copr-backend

This project is used as an additional `SourceX` for copr-backend.


## Development

When running `./run_tests.sh` for the Copr `backend` package, it
creates `backend/test-data-copr-backend-*` directory. It is
recommended to try your changes there and then move them to this
project.


## New release

After making changes, tag a new release in this repository:

```
git tag v4
git push origin v4
```

In the Copr repository, increment tests version in
`copr-backend.spec`, for example:

```
%global tests_version 4
```
