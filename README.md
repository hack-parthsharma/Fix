<h1 align="center">🤖 Fix!</h1>

<p align="center">
    AI fixing your issues.
</p>

</p>

## What is it?

A program that suggests solutions for errors in the command line using OpenAI's Codex AI to produce suggestions.


## Installation

1. Get access to OpenAI's [Codex API](https://openai.com/blog/openai-codex/).
2. Clone the repository
3. Add `main.py` to your path, e.g. by running `cp $PWD/main.py ~/.local/bin/fix` or similar.


## How to use it
```
$ fix <program>
```
To fix the last command:
```
$ fix !!
```


## How it works

This script executes your program and generates potential solutions using OpenAI's [Codex AI](https://openai.com/blog/openai-codex/).


-------------------------------------------------------------------
