# Scotland Yard Helper in Python (Updated)
<a target="_blank" href="https://colab.research.google.com/github/ptsgrn/ScotlandYard-py/blob/master/colab.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

This program is (or will be) a Scotland Yard helper that calculates the possible positions of Mr. X given a starting position and a list of tickets.

networkx is required.

## Installation:
Clone the repository and install dependencies:

    git clone https://github.com/ptsgrn/ScotlandYard-py.git
    pip install -r requirements.txt

## Usage:

At the command promt enter

    cd path/to/scotlandyard
    python(3) scotlandyard.py startnode ticketlist

with `startnode` being a number between 1 and 199 and `ticketlist` being a combination of `taxi`, `bus`, `subway` or `black`. For example:

    python scotlandyard.py 27 taxi taxi bus subway

yields the result `46, 67, 79, 89, 111`.
