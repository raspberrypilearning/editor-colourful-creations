<h2 class="c-project-heading--task">Write text</h2>
--- task ---
Add text in different colours
--- /task ---

--- task ---

Choose another hex colour code and use it to create coloured text:

--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 1
line_highlights: 7-10
---
from turtle import *

screen = Screen()
screen.setup(400, 400)
screen.bgcolor('#A7E30E')

color('#BF3F7F')
style = ('Arial', 40, 'bold')
write('HELLO', font=style, align='center')
hideturtle()
--- /code ---

You don't have to use the 'Arial' font, you could try 'Verdana', 'Times' or 'Courier'.
   
`40` is the font size, you can try changing that too.  

--- /task ---  

--- task ---

Try different colours until you get two that you really like that look good together. 

--- /task ---   





