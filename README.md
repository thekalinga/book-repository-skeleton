# Book repo

`repo ` directory consists of all books in markdown format which can be converted into `pdf`/`epub` on demand

## Generating pdf

Run `pdf`

## Generating epub

Run `epub`

## Generating html

Run `html`

## Debug pdf generation

1. Generate tex file by running `tex` which generates `book-gen.tex`
2. Review/Edit `book-gen.tex`
3. Run `pdf-from-tex` to generate pdf from `book-gen.tex` instead

## One time setup

1. Ensure [docker](https://www.docker.com/) is installed
2. From `system/docker` directory, run `build.sh`which generates builds required docker image

## Experiment with docker image

For experimenting with docker image on small files, look at the files in `system/experiment`
