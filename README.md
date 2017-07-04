# docker-sphinx-doc

[![License](https://img.shields.io/github/license/uchida/docker-sphinx-doc.svg?maxAge=2592000)](https://tldrlegal.com/license/creative-commons-cc0-1.0-universal)
[![MicroBadger](https://images.microbadger.com/badges/image/auchida/sphinx-doc.svg)](http://microbadger.com/images/auchida/sphinx-doc)

Sphinx installed docker image, including minimal texlive + texlive-language-japanese, dvipng and graphviz.

Docker image is available as [auchida/sphinx-doc](https://hub.docker.com/r/auchida/sphinx-doc/) in Docker Hub.

## Image tags

- `latest`

## Usage

```console
$ docker run -v $PWD:/opt/docs auchida/sphinx-doc make html
```

About Sphinx, consult [Sphinx documentation](http://www.sphinx-doc.org/en/stable/) for more information.

## License

Contents on this repository are dedicated to [![CC0 public domain](http://i.creativecommons.org/p/zero/1.0/80x15.png "CC0 public domain")](https://creativecommons.org/publicdomain/zero/1.0/).
No rights reserved.

License for distributed Docker images follows one of [Debian Project](https://www.debian.org/legal/licenses/), [Graphviz](http://www.graphviz.org/License.php), [dvipng](https://www.ctan.org/pkg/dvipng), [TeXLive](https://www.tug.org/texlive/copying.html), [Sphinx](https://github.com/sphinx-doc/sphinx/blob/master/LICENSE) and its dependencies.
