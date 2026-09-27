# personal-site

The source of [vasar.dev](https://vasar.dev), Vasily Vasilyev's calling card: a name and a set of links. It started as a fork of [valery-kirichenko/personal-site](https://github.com/valery-kirichenko/personal-site), with the page, the styling and the favicon rewritten.

## Preview locally

There is no build step. Open `src/index.html` in a browser.

## Deployment

The site is served by nginx straight from a checkout of this repository on the host; `git pull` in that checkout publishes a change. The `Dockerfile`, `nginx.conf` and `.github/workflows/deploy.yml` are kept for a later move into a container; the workflow is disabled until then.

## Shared content

Parts of this content can also appear on the projects site ([Vasar007.github.io](https://github.com/Vasar007/Vasar007.github.io)) and the GitHub profile README ([Vasar007](https://github.com/Vasar007/Vasar007)). When changing content here, check those two as well.

## Licence

The code is under the MIT licence (see `LICENSE`). The texts are under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
