# repo2docker-subdir-support
A repository to test building from a subdirectory with repo2docker

This repository is used to test that the `--subdir` flag of repo2docker works
as expected. The `requirements.txt` in the root will lead to a build failure
as it contains a package name that doesn't exist.

The `requirements.txt` in `a directory/` will build.
