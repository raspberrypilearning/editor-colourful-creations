<h2 class="c-project-heading--task">Challenge: Create a poster</h2>
--- task ---

Create a colour palette for a new poster.

--- /task ---

<div class="c-project-callout c-project-callout--tip">

### Colour pallette

A palette is a set of colours that work well together for one poster design.

Choose a theme such as space, forest, sea, autumn, a sports team, or your own idea.
</div>
  
--- task ---

This is a new, longer program. Delete your old code in <code>main.py</code> and replace it with the code below.

--- /task ---

Adapt this example for your own design.

<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 1
line_highlights: 
---
from turtle import *

colours = {
  'space': '#060608',
  'moongrey': '#BCBDEF',
  'verylime': '#A7E30E',
  'reallyraspberry': '#FA057F',
  'deepsea': '#226363',
  'awesomeorange': '#F37C06',
  'coolcyan': '#4FEEF6',
  'lovelylemon': '#FBF312',
  'gloomygrey': '#363332',
}

screen = Screen()
screen.setup(400, 400)
screen.bgcolor(colours['space'])

goto(0,0)
color(colours['moongrey'])
dot(350)

setheading(-90)
penup()
hideturtle()
goto(0, 135)

color(colours['verylime'])
write('A typical', font=('Verdana', 20, 'bold'), align='center')
forward(40)

color(colours['reallyraspberry'])
write('smart phone', font=('Verdana', 25, 'bold'), align='center')
forward(40)

color(colours['deepsea'])
write('has more', font=('Verdana', 18, 'bold'), align='center')
forward(40)

color(colours['awesomeorange'])
write('computing power', font=('Verdana', 25, 'bold'), align='center')
forward(40)

color(colours['coolcyan'])
write('Apollo 11', font=('Verdana', 30, 'bold'), align='center')
forward(40)

color(colours['lovelylemon'])
write('when it landed on', font=('Verdana', 20, 'bold'), align='center')
forward(50)

color(colours['gloomygrey'])
write('the moon', font=('Verdana', 35, 'bold'), align='center')
--- /code ---
</div>

<div class="c-project-callout c-project-callout--tip">

### Tips
- You can also use other turtle commands that you know such as `forward`, `right`, `left`, `penup` and `pendown`. 
- Maybe you could add a border to your poster?
- Use `circle(50)` to draw a circle outline with radius 50.
- `dot(100)` draws a filled in circle with diameter 100. 
</div>