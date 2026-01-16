<h2 class="c-project-heading--task">Choose a colour code</h2>
--- task ---
Choose your own hex colour code.
--- /task ---

To choose a different colour, open <a href="http://jumpto.cc/colour-picker" target="_blank">jumpto.cc/colour-picker</a>.

Copy the hex code that starts with '#', for example '#A7E30E'. 

Replace `'blue'` with your hex code.

<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 1
line_highlights: 5
---
from turtle import *

screen = Screen()
screen.setup(400, 400)
screen.bgcolor('#A7E30E')
--- /code ---

--- task ---   
**Test:** Run the code. Check that the background colour has changed to your chosen colour.
--- /task ---

</div>    