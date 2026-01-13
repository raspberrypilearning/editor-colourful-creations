<h2 class="c-project-heading--task">Colourful text</h2>
--- task ---
Choose another hex colour code and use it to create coloured text
--- /task ---

Add the code below to add some text.

<div class="c-project-code">
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

color('pink')
style = ('Arial', 40, 'bold')
write('HELLO', font=style, align='center')
hideturtle()
--- /code ---
</div>
--- task ---

**Test:** run the code and see the text. 

--- /task ---   

Choose another colour from <a href="http://jumpto.cc/colour-picker" target="_blank">jumpto.cc/colour-picker</a>, copy the hex colour code and paste into the editor instead of `'pink'`.

 <div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 1
line_highlights: 7
---
from turtle import *

screen = Screen()
screen.setup(400, 400)
screen.bgcolor('#A7E30E')

color('pink')
style = ('Arial', 40, 'bold')
write('HELLO', font=style, align='center')
hideturtle()
--- /code ---
</div>
--- task ---

**Test:** run the code and see the text change to your chosen colour.

--- /task ---  

--- task ---

Try different colours until you get two that you really like that look good together. 

--- /task ---   

<div class="c-project-callout c-project-callout--tip">

### Tip
Try playing with the design of the text. 

You don't have to use the 'Arial' font, you could try 'Verdana', 'Times' or 'Courier'.
   
`40` is the font size, you can try changing that too.  
</div>

