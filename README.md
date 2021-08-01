<!-- Badge for License -->
<div align="right">

  [![](https://img.shields.io/github/license/TeXtw/docker-lkmpg.svg?style=flat-square)](./LICENSE)

</div>

<div align="center">

# Docker Image for [LKMPG](https://github.com/sysprog21/lkmpg)

🐳 _Docker image supports full TeXLive with Gnuplot and Pandoc._

</div>

## Usage

```bash
# pull docker image from Docker Hub and run container
$ docker pull twtug/lkmpg
$ docker run --rm -it -v $(pwd):/workdir twtug/lkmpg

# run commands
$ pdflatex -shell-escap lkmpg.tex
$ make4ht --shell-escape --utf8 --format html5 --config html.cfg --output-dir html lkmpg.tex
```

## License

Licensed under the MIT License, Copyright © 2021-present Hsins.
