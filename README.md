# texlive-poppler

[Docker Hub](https://registry.hub.docker.com/u/passy/texlive-poppler/)

A Docker container extending
[ontouchstart/texlive-full](https://github.com/ontouchstart/texlive-full)
with `poppler-utils`.

## Get it

`docker pull passy/texlive-poppler`

## Run it

`docker run --rm -v $PWD:/test/ -w=/test -t passy/texlive-poppler pdftocairo -png myfile.pdf`
