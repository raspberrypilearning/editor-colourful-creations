<h2 class="c-project-heading--task">Name the colours</h2>
--- task ---
Add the code below to create **dictionary** that stores names for your own colours.
--- /task ---

<div class="c-project-callout c-project-callout--tip">

### Why use a dictionary?
Hex colour codes are flexible, but hard to remember.  
A dictionary lets you match easy-to-remember names to colour codes.
</div>

--- task ---
Give your hex code colours names in the dictionary. 

Then update the rest of the code to use the names inside square brackets `'[ ]'`.
--- /task ---
</div>

<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 1
line_highlights: 3-6, 10, 12
---
from turtle import *

colours = {  # Name of dictionary
  'verylime': '#A7E30E',  # colour name : hex code
  'reallyraspberry': '#BF3F7F'
}

screen = Screen()
screen.setup(400, 400)
screen.bgcolor(colours['verylime'])

color(colours['reallyraspberry'])
style = ('Arial', 40, 'bold')
write('HELLO', font=style, align='center')
hideturtle()
--- /code ---
</div>
--- task ---
**Test** the code. Check your design still displays correctly with your named colours.
--- /task ---

<div class="c-project-callout c-project-callout--tip">

### Tip
Put a comma`,` between each item in the dictionary.

</div>