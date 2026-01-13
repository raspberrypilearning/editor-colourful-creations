<h2 class="c-project-heading--task">Name the colours</h2>
--- task ---
Give your colours names using a dictionary.
--- /task ---

<div class="c-project-callout c-project-callout--tip">

### Why use a dictionary?
Hex colour codes are flexible, but hard to remember.  
A dictionary lets you match easy-to-remember names to colour codes.
</div>

Add the code below to create a dictionary for your colours.

<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 1
line_highlights: 3-6
---
colours = {  # Name of dictionary
  'verylime': '#A7E30E',  # colour name : hex code
  'reallyraspberry': '#BF3F7F'
}
--- /code ---
</div>
--- task ---
Add your own colours.  
Create new names and match them to hex colour codes.
--- /task ---

<div class="c-project-callout c-project-callout--tip">

### Tip
Put a comma`,` between each item in the dictionary.
</div>
--- task ---
Test with your own colours. Your colour name goes inside square brackets '[]' after the name of the dictionary.
--- /task ---

Now update the rest of the code to use colours from the dictionary.

<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 1
line_highlights: 10, 12
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
**Test** the code. Check that the text still displays correctly with your named colours.
--- /task ---

