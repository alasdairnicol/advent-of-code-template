Advent of Code 20XX
===================

[![About](https://img.shields.io/badge/Advent%20of%20Code%20🎄-20XX-brightgreen)](https://adventofcode.com/20XX/)
[![Stars](https://img.shields.io/badge/stars%20⭐-0-yellow)](https://adventofcode.com/20XX/stats)
[![Python](https://img.shields.io/badge/python-3670A0?logo=python&logoColor=ffdd54)](https://www.python.org)

Solutions for Advent of Code 20XX, written in Python.

https://adventofcode.com/20XX

How to use this template
========================

1. Create new repository from template
2. Add repository secrets `AOC_SESSION` and `AOC_USER_ID`
3. Replace 20XX with correct year in README.md and workflow files

Every time a dayXX.py file is added/modified, the `aoc-badges.yml`
workflow will update the badges in the Readme. Once you have all 50
stars, remove the trigger so that it doesn't run unnecessarily.

This template previously had a aoc-download-input.yml action which
downloaded the input files. This has been removed because you're not
supposed to commit input files to a public repository. Instead, use
the download_inputs.sh to download the input files to the local
checkout.
