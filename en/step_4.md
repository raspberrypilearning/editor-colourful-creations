<h2 class="c-project-heading--task">Name the colours</h2>
--- task ---
Choose names for your colours add entries to the dictionary for them. 
--- /task ---
## A Colour Dictionary

Using hex colour codes is really flexible but they are hard to remember. 

As you probably already know, a dictionary allows you to look up a word, and see it’s meaning. In Python, a dictionary is even more flexible that that - it allows you to look up a value for any 'key' in the dictionary.

Let's create a dictionary to map from human-friendly colour names (keys) to computer-friendly hex codes (values).

--- task ---

A dictionary is contained in curly brackets. 

Create an empty dictionary called `colours`:

--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 3
line_highlights: 5-7
---
screen = Screen()
screen.setup(400, 400)

colours = {}

screen.bgcolor('#A7E30E')
--- /code ---

--- /task ---

--- task ---

Choose cool names for your colours and edit the `colours = ` line to add entries to the dictionary for them. 

Here's an example colour dictionary:

--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 6
line_highlights: 7-9
---
colours = {
  'verylime': '#A7E30E',
  'reallyraspberry': '#BF3F7F'
}
--- /code ---
   
A colon `:` separates the key (colour name) from the value (hex code.) You need a comma `,` between each key:value pair in the dictionary. 

--- /task ---   

