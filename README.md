# Prettify GitHub Log
Actually this will work on all Git Logs but...

## Aims

Make git logs easier for use in scenerioas when communicating the progress of a project to none experts.

## Note
-
This isn't great but it does the job (a bit).

## Installation

```bash
python -m pip install pydriller Pygments Jinja2
```

## Usage

```bash
python main.py -i <repo> -o <outputfile>
```

repo is the local repository folder

outputfile is the full file path to a file to save the html into.