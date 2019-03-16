# Docker-SourceServers [![pipeline-build-image][]][pipeline-build-site] [![pipeline-update-image][]][pipeline-update-site]

[pipeline-build-image]: https://img.shields.io/azure-devops/build/joeltimothyoh/docker-sourceservers/11/build.svg?label=Build&logo=azure-devops&style=for-the-badge&color=navy
[pipeline-build-site]: https://dev.azure.com/joeltimothyoh/docker-sourceservers/_build?definitionId=11
[pipeline-update-image]: https://img.shields.io/azure-devops/build/joeltimothyoh/docker-sourceservers/12/update.svg?label=Update&logo=azure-devops&style=for-the-badge&color=brightgreen
[pipeline-update-site]: https://dev.azure.com/joeltimothyoh/docker-sourceservers/_update?definitionId=12

Builds up-to-date **Source** / **Goldsource** dedicated server images through use of [`steamcmd`](https://github.com/theohbrothers/docker-steamcmd).

## Supported Tags

* `latest` [(*/build/Dockerfile*)](https://github.com/theohbrothers/docker-sourceservers/blob/github/build/Dockerfile), [(*/update/Dockerfile*)](https://github.com/theohbrothers/docker-sourceservers/blob/github/update/Dockerfile)
* `<version>` [(*/build/Dockerfile*)](https://github.com/theohbrothers/docker-sourceservers/blob/github/build/Dockerfile)

## Games and Versions

Dedicated servers hosted on Steam are usually required to be running the *latest version* of the game in order for clients to connect to them. Simply pull a game image by the `latest` tag for the latest version.

* [**sourceservers**](https://hub.docker.com/u/sourceservers/) (Docker Hub)
* [**goldsourceservers**](https://hub.docker.com/u/goldsourceservers/) (Docker Hub)
