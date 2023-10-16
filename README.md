Vanderbilt's Machine Learning Training Facility is housed at the ACCRE computing cluster and operates under R&D funds from Vanderbilt Univeristy and USCMS.
Primary contact: Andrew Melo
Email: Andrew.Melo@gmail.com

## Getting Started

Upon accessing your main terminal at ACCRE, the best approach to begin training is to create a Python 3.10 virtual environment.
First, the necessary modules must be loaded:

```
module load GCCcore/.11.3.0
module load Python/3.10.4
```
Then create a virtual environment, upgraded *pip*, and install needed packages:
```
python3.10 -m venv <my_venv>
source <my_venv>/bin/activate # this puts you "inside" the virtual environment
# anything you install now will be inside the virtual environment
pip install --upgrade pip wheel
pip install <packages you want>
```

Any text with no empty lines between will become a paragraph.
Leave an blank line between headings and paragraphs.
Font can be *Italic* or **Bold**.
Code can be highlighted with `backticks`.

Hyperlinks look like this [GitHub Help](https://help.github.com/).

A bullet list is created using `*`, `+`, or `-`, like:

- dog
- cat
- muffin

A numbered list is created using a number + `.`, like:

1. one
2. two
6. three
2. four
