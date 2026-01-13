

--- task ---

Now you don't need to remember the hex codes, you can just look them up in the dictionary. 

Adapt the following code to use your colour names:
  
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 6
line_highlights: 11-12
---
colours = {
  'verylime': '#A7E30E',
  'reallyraspberry': '#BF3F7F'
}

print(colours['verylime'])
print(colours['reallyraspberry'])
--- /code ---
  
The key goes inside square brackets '[]' after the name of the dictionary.

--- /task ---

--- task ---

Now you can update your code to look up colours in the dictionary:

--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 14
line_highlights: 14, 16
---
screen.bgcolor(colours['verylime'])

color(colours['reallyraspberry'])
style = ('Arial', 40, 'bold')
write('HELLO', font=style, align='center')
hideturtle()
--- /code ---

--- /task ---

Test your code to make sure your text still displays correctly.
  




