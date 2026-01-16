<h2 class="c-project-heading--task">Challenge: More colours</h2>
--- task ---
Add more colours to your dictionary and test them.
--- /task ---

Use <a href="http://jumpto.cc/colour-picker" target="_blank">jumpto.cc/colour-picker</a> to find more colours.

Here is some example code that animates the text using the turtle.

<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 15
line_highlights: 17-26
---
hideturtle()

penup()
goto(0, 100)
color(colours['reallyraspberry'])
style = ('Arial', 40, 'bold')
write('HELLO', font=style, align='center')
right(90)
forward(60)
color(colours['awesomeorange'])
write('WORLD', font=style, align='center')
hideturtle()
--- /code ---

--- task ---
Add this to your project and change the code to use the new colours from your dictionary.
--- /task ---
</div>

<div class="c-project-callout c-project-callout--tip">
<h3>Tip</h3>
The turtle starts in the centre of the screen. `goto()` moves it to a new position, and `write()` shows text where the turtle is.
</div>