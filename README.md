# Advent of Code Python Template

This template provides an easy and quick way to start with [Advent of Code](https://adventofcode.com/) problems in Python with [Cloud Dev Environment in Gitpod](https://www.gitpod.io/cde)

## Quick Start

### Create your repository 📝

- Click [`Use this template`](https://github.com/Gitpod-Samples/aoc-python-template/generate) and create your repository.

### Start Working ⚡💻

- Open a [Cloud Dev Environment in Gitpod](https://www.gitpod.io/cde) by clicking the following button:

  [![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/from-referrer)

This will ask you about which **year** and **day** you want to template. You can also provide a puzzle name which will be used as part of the directory name and the comments within your files.

The files are copied into a subdirectory of the `advent_of_code/` directory on your computer. You can change `advent_of_code/` to any other name you want.

## Scripting

You can also use Copier as part of a script. The [documentation](https://copier.readthedocs.io/en/stable/api/) shows how to call Copier as part of a Python script.

On the command line, you can use `-d` to provide answers to questions instead of answering them interactively. On Bash (and possibly other shells), the following will set up all directories for the 2022 event inside of your `aoc/` directory:

```sh
$ for day in {01..25}; do
>     copier gh:gahjelle/template-aoc-python -d year=2022 -d day=$day -d puzzle_name="" -d puzzle_dir=$day aoc/
> done
```

After running this, you'll have 25 subdirectories within `aoc/2022/` with templates for solving each day of Advent of Code with Python.

## Examples

See https://github.com/gahjelle/advent_of_code/tree/main/python for examples using the template. This tutorial, [Advent of Code: Solving Your Puzzles With Python](https://realpython.com/python-advent-of-code/), explains the reasoning behind the template and shows a few examples of using it to solve puzzles.

## Credits

Thanks to [Matt Gregory](https://github.com/grovduck) for helping to [debug](https://github.com/gahjelle/template-aoc-python/issues/1) this recipe for Windows and creating the Powershell script to create a full year of templates.

And a huge thanks to [Eric Wastl](https://twitter.com/ericwastl/) for creating the wonderful [Advent of Code](https://adventofcode.com/).
