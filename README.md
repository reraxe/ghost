# Docker Official Image packaging for Ghost with Docker Secrets - reraxe version

Only available on https://github.com/reraxe/ghost/tree/master/5/debian
* Dockerfile: Add `COPY`, `RUN`, `ENTRYPOINT`
* ghostenv.php: Add secrets: `ENV`
* ghostenv-entrypoint: `file_env`
* Docker build
```sh
docker build -t yourimage:latest .
docker push yourimage:latest
```

# https://github.com/docker-library/ghost

## Maintained by: [the Docker Community](https://github.com/docker-library/ghost)

This is the Git repo of the [Docker "Official Image"](https://github.com/docker-library/official-images#what-are-official-images) for [`ghost`](https://hub.docker.com/_/ghost/) (not to be confused with any official `ghost` image provided by `ghost` upstream). See [the Docker Hub page](https://hub.docker.com/_/ghost/) for the full readme on how to use this Docker image and for information regarding contributing and issues.

The [full image description on Docker Hub](https://hub.docker.com/_/ghost/) is generated/maintained over in [the docker-library/docs repository](https://github.com/docker-library/docs), specifically in [the `ghost` directory](https://github.com/docker-library/docs/tree/master/ghost).

## See a change merged here that doesn't show up on Docker Hub yet?

For more information about the full official images change lifecycle, see [the "An image's source changed in Git, now what?" FAQ entry](https://github.com/docker-library/faq#an-images-source-changed-in-git-now-what).

For outstanding `ghost` image PRs, check [PRs with the "library/ghost" label on the official-images repository](https://github.com/docker-library/official-images/labels/library%2Fghost). For the current "source of truth" for [`ghost`](https://hub.docker.com/_/ghost/), see [the `library/ghost` file in the official-images repository](https://github.com/docker-library/official-images/blob/master/library/ghost).

---

-	[![build status badge](https://img.shields.io/github/workflow/status/docker-library/ghost/GitHub%20CI/master?label=GitHub%20CI)](https://github.com/docker-library/ghost/actions?query=workflow%3A%22GitHub+CI%22+branch%3Amaster)
-	[![build status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/update.sh/job/ghost.svg?label=Automated%20update.sh)](https://doi-janky.infosiftr.net/job/update.sh/job/ghost/)

| Build | Status | Badges | (per-arch) |
|:-:|:-:|:-:|:-:|
| [![amd64 build status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/multiarch/job/amd64/job/ghost.svg?label=amd64)](https://doi-janky.infosiftr.net/job/multiarch/job/amd64/job/ghost/) | [![arm32v6 build status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/multiarch/job/arm32v6/job/ghost.svg?label=arm32v6)](https://doi-janky.infosiftr.net/job/multiarch/job/arm32v6/job/ghost/) | [![arm32v7 build status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/multiarch/job/arm32v7/job/ghost.svg?label=arm32v7)](https://doi-janky.infosiftr.net/job/multiarch/job/arm32v7/job/ghost/) | [![arm64v8 build status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/multiarch/job/arm64v8/job/ghost.svg?label=arm64v8)](https://doi-janky.infosiftr.net/job/multiarch/job/arm64v8/job/ghost/) |
| [![ppc64le build status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/multiarch/job/ppc64le/job/ghost.svg?label=ppc64le)](https://doi-janky.infosiftr.net/job/multiarch/job/ppc64le/job/ghost/) | [![s390x build status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/multiarch/job/s390x/job/ghost.svg?label=s390x)](https://doi-janky.infosiftr.net/job/multiarch/job/s390x/job/ghost/) | [![put-shared build status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/put-shared/job/light/job/ghost.svg?label=put-shared)](https://doi-janky.infosiftr.net/job/put-shared/job/light/job/ghost/) |

<!-- THIS FILE IS GENERATED BY https://github.com/docker-library/docs/blob/master/generate-repo-stub-readme.sh -->
