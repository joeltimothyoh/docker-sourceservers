# Docker-SourceServers

[![pipeline-build-image][]][pipeline-build-site] [![pipeline-update-image][]][pipeline-update-site]

[pipeline-build-image]: https://img.shields.io/azure-devops/build/joeltimothyoh/docker-sourceservers/11/build.svg?label=Build&logo=azure-devops&style=for-the-badge&color=blue
[pipeline-build-site]: https://dev.azure.com/joeltimothyoh/docker-sourceservers/_build?definitionId=11
[pipeline-update-image]: https://img.shields.io/azure-devops/build/joeltimothyoh/docker-sourceservers/12/update.svg?label=Update&logo=azure-devops&style=for-the-badge&color=brightgreen
[pipeline-update-site]: https://dev.azure.com/joeltimothyoh/docker-sourceservers/_update?definitionId=12

Builds up-to-date **Source** / **Goldsource** dedicated server images through use of [`steamcmd`](https://github.com/theohbrothers/docker-steamcmd).

## Supported Tags

* `latest` [(*/build/Dockerfile*)](https://github.com/theohbrothers/docker-sourceservers/blob/github/build/Dockerfile), [(*/update/Dockerfile*)](https://github.com/theohbrothers/docker-sourceservers/blob/github/update/Dockerfile)
* `<version>` [(*/build/Dockerfile*)](https://github.com/theohbrothers/docker-sourceservers/blob/github/build/Dockerfile)

## Games and Versions

Dedicated servers hosted on Steam are usually required to be running the *latest version* of the game in order for clients to connect to them. Simply pull a game image by the `latest` tag for the latest version.


* [`sourceservers`](https://hub.docker.com/u/sourceservers/) (Docker Hub)
* [`goldsourceservers`](https://hub.docker.com/u/goldsourceservers/) (Docker Hub)

### Source

|Game|Version|Size / Layers|
|:-:|:-:|:-:|
| `csgo` | [![srcds-csgo-version][]][srcds-csgo-link] | [![srcds-csgo-image][]][srcds-csgo-link]
| `cstrike` | [![srcds-cstrike-version][]][srcds-cstrike-link] | [![srcds-cstrike-image][]][srcds-cstrike-link]
| `dod` | [![srcds-dod-version][]][srcds-dod-link] | [![srcds-dod-image][]][srcds-dod-link]
| `hl2mp` | [![srcds-hl2mp-version][]][srcds-hl2mp-link] | [![srcds-hl2mp-image][]][srcds-hl2mp-link]
| `left4dead` | [![srcds-left4dead-version][]][srcds-left4dead-link] | [![srcds-left4dead-image][]][srcds-left4dead-link]
| `left4dead2` | [![srcds-left4dead2-version][]][srcds-left4dead2-link] | [![srcds-left4dead2-image][]][srcds-left4dead2-link]
| `tf` | [![srcds-tf-version][]][srcds-tf-link] | [![srcds-tf-image][]][srcds-tf-link]

[srcds-csgo-version]: https://images.microbadger.com/badges/version/sourceservers/csgo.svg
[srcds-csgo-image]: https://images.microbadger.com/badges/image/sourceservers/csgo.svg
[srcds-csgo-link]: https://microbadger.com/images/sourceservers/csgo
[srcds-cstrike-version]: https://images.microbadger.com/badges/version/sourceservers/cstrike.svg
[srcds-cstrike-image]: https://images.microbadger.com/badges/image/sourceservers/cstrike.svg
[srcds-cstrike-link]: https://microbadger.com/images/sourceservers/cstrike
[srcds-dod-version]: https://images.microbadger.com/badges/version/sourceservers/dod.svg
[srcds-dod-image]: https://images.microbadger.com/badges/image/sourceservers/dod.svg
[srcds-dod-link]: https://microbadger.com/images/sourceservers/dod
[srcds-hl2mp-version]: https://images.microbadger.com/badges/version/sourceservers/hl2mp.svg
[srcds-hl2mp-image]: https://images.microbadger.com/badges/image/sourceservers/hl2mp.svg
[srcds-hl2mp-link]: https://microbadger.com/images/sourceservers/hl2mp
[srcds-left4dead-version]: https://images.microbadger.com/badges/version/sourceservers/left4dead.svg
[srcds-left4dead-image]: https://images.microbadger.com/badges/image/sourceservers/left4dead.svg
[srcds-left4dead-link]: https://microbadger.com/images/sourceservers/left4dead
[srcds-left4dead2-version]: https://images.microbadger.com/badges/version/sourceservers/left4dead2.svg
[srcds-left4dead2-image]: https://images.microbadger.com/badges/image/sourceservers/left4dead2.svg
[srcds-left4dead2-link]: https://microbadger.com/images/sourceservers/left4dead2
[srcds-tf-version]: https://images.microbadger.com/badges/version/sourceservers/tf.svg
[srcds-tf-image]: https://images.microbadger.com/badges/image/sourceservers/tf.svg
[srcds-tf-link]: https://microbadger.com/images/sourceservers/tf

### GoldSource

|Game|Version|Size / Layers|
|:-:|:-:|:-:|
| `cstrike` | [![hlds-cstrike-version][]][hlds-cstrike-link] | [![hlds-cstrike-image][]][hlds-cstrike-link]
| `czero` | [![hlds-czero-version][]][hlds-czero-link] | [![hlds-czero-image][]][hlds-czero-link]
| `dmc` | [![hlds-dmc-version][]][hlds-dmc-link] | [![hlds-dmc-image][]][hlds-dmc-link]
| `dod` | [![hlds-dod-version][]][hlds-dod-link] | [![hlds-dod-image][]][hlds-dod-link]
| `gearbox` | [![hlds-gearbox-version][]][hlds-gearbox-link] | [![hlds-gearbox-image][]][hlds-gearbox-link]
| `ricochet` | [![hlds-ricochet-version][]][hlds-ricochet-link] | [![hlds-ricochet-image][]][hlds-ricochet-link]
| `tfc` | [![hlds-tfc-version][]][hlds-tfc-link] | [![hlds-tfc-image][]][hlds-tfc-link]
| `valve` | [![hlds-valve-version][]][hlds-valve-link] | [![hlds-valve-image][]][hlds-valve-link]

[hlds-cstrike-version]: https://images.microbadger.com/badges/version/goldsourceservers/cstrike.svg
[hlds-cstrike-image]: https://images.microbadger.com/badges/image/goldsourceservers/cstrike.svg
[hlds-cstrike-link]: https://microbadger.com/images/goldsourceservers/cstrike
[hlds-czero-version]: https://images.microbadger.com/badges/version/goldsourceservers/czero.svg
[hlds-czero-image]: https://images.microbadger.com/badges/image/goldsourceservers/czero.svg
[hlds-czero-link]: https://microbadger.com/images/goldsourceservers/czero
[hlds-dmc-version]: https://images.microbadger.com/badges/version/goldsourceservers/dmc.svg
[hlds-dmc-image]: https://images.microbadger.com/badges/image/goldsourceservers/dmc.svg
[hlds-dmc-link]: https://microbadger.com/images/goldsourceservers/dmc
[hlds-dod-version]: https://images.microbadger.com/badges/version/goldsourceservers/dod.svg
[hlds-dod-image]: https://images.microbadger.com/badges/image/goldsourceservers/dod.svg
[hlds-dod-link]: https://microbadger.com/images/goldsourceservers/dod
[hlds-gearbox-version]: https://images.microbadger.com/badges/version/goldsourceservers/gearbox.svg
[hlds-gearbox-image]: https://images.microbadger.com/badges/image/goldsourceservers/gearbox.svg
[hlds-gearbox-link]: https://microbadger.com/images/goldsourceservers/gearbox
[hlds-ricochet-version]: https://images.microbadger.com/badges/version/goldsourceservers/ricochet.svg
[hlds-ricochet-image]: https://images.microbadger.com/badges/image/goldsourceservers/ricochet.svg
[hlds-ricochet-link]: https://microbadger.com/images/goldsourceservers/ricochet
[hlds-tfc-version]: https://images.microbadger.com/badges/version/goldsourceservers/tfc.svg
[hlds-tfc-image]: https://images.microbadger.com/badges/image/goldsourceservers/tfc.svg
[hlds-tfc-link]: https://microbadger.com/images/goldsourceservers/tfc
[hlds-valve-version]: https://images.microbadger.com/badges/version/goldsourceservers/valve.svg
[hlds-valve-image]: https://images.microbadger.com/badges/image/goldsourceservers/valve.svg
[hlds-valve-link]: https://microbadger.com/images/goldsourceservers/valve