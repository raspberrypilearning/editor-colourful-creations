<h2 class="c-project-heading--task">Choose a colour code</h2>
--- task ---
Choose your own hex colour codes
--- /task ---

Python has named colours like red and white. You can also use colour codes, which let you choose any colour you want.

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
screen.bgcolor('white')
--- /code ---
</div>    

Notice that you used a named colour: `'white'`.

To pick your own colour, open <a href="http://jumpto.cc/colour-picker" target="_blank">jumpto.cc/colour-picker</a> and choose a colour you like. 

Copy the hex code beginning with a '#', such as '#A7E30E'. 

Now paste your hex code into the editor instead of `'white'`.

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
**Test:** run the code and see the backgorund colour is the one you picked.
--- /task ---

</div>    