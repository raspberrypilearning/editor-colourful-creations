<h2 class="c-project-heading--task">Name the colours</h2>

Add the code below to create **dictionary** that stores names for your own colours.

<h2 class="c-project-heading--explainer">Follow these instructions</h2>

## Step 1

### Why use a dictionary?
<div class="c-project-callout c-project-callout--tip">

Hex colour codes are flexible, but hard to remember.  
A dictionary lets you match easy-to-remember names to colour codes.
</div>

## Step 2

Give your hex code colours names in the dictionary. 

Then update the rest of the code to use the names inside square brackets `'[ ]'`.

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

## Step 3

**Test** the code. Check your design still displays correctly with your named colours.

### Tip
<div class="c-project-callout c-project-callout--tip">

Put a comma`,` between each item in the dictionary.

</div>

## Now run your code

Test the code and check that your design still appears using your named colours.
