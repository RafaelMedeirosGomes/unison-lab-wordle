# Unison Learning Lab Wordle

## Description

[Unison](https://www.unison-lang.org/) is a programming language that treats code as data. <br>
In Unison your codebase is a sqlite database. <br>
This project is a guided project from the official documentation made for learning the Unison toolkit.

## Running

1. Follow the [installation guide](https://www.unison-lang.org/learn/quickstart/) in the website
2. [Clone](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) this repository
3. Download the possible words dictionary [here](https://gist.github.com/rlmark/fef2a315cba90522cc1dd81461070109) and save it inside the repository folder with the name `dictionary.txt`
4. Run `ucm run.compiled wordle.uc` inside the repository folder

## Source Code

You can browse the source code in Unison Share clicking in [this](https://share.unison-lang.org/@rafaelmedeirosgomes/code/latest/namespaces/public/wordle) link

## Technical Details

The code is written in Model-View-Controller architecture, <br>
The View uses [ANSI CSI sequences](https://en.wikipedia.org/wiki/ANSI_escape_code) to format the characters to be displayed in the terminal <br>
The Controller reads a file with possible words, you can get one from Unison team [here](https://gist.github.com/rlmark/fef2a315cba90522cc1dd81461070109)
