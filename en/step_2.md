<h2 class="c-project-heading--task">Start your design</h2>
--- task ---

Set up a background for your design.

--- /task ---

Python has some built-in colour names, like **red** and **white**. You can also use hex codes to choose any colour you want.

Add the following code to set up a screen for your design.

<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 1
line_highlights: 1-4
---
from turtle import *

screen = Screen()
screen.setup(400, 400)
screen.bgcolor('blue')
--- /code ---
--- task ---

**Test:** Copy this code into main.py and run the code. This code uses a named colour, 'blue' for the background.

--- /task ---
</div>
