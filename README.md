# Dot Counter

Counts number of colored circles/dots in images and breaks down the number of 
dots by their color (red, blue, green)

## Documentation/Examples

You may run the `dotcounter.py` program from the terminal/command line.
Here is an example using an image that exists in this repository.

```sh
python dotcounter.py images/dots.jpg
# No. of red      circles detected = 10
# No. of green    circles detected = 39
# No. of yellow   circles detected = 31
```

## Dependencies

This software was tested on Python 3.12.4- no other versions are guaranteed
to work.

To run this software you need to have  the following pacakges installed
numpy, scipy, opencv-python, matplotlib

## Installation

```sh

```

Once you have the source code, install the dependencies

```sh
pip install -r requirements.txt
```

If you prefer to work from a virual environment:

```sh
python -m venv <path to virtual environment>
source <path to virtual environment>/bin/activate
python -m pip install -r requirements.txt
```

