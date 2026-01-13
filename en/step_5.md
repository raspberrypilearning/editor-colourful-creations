<h2 class="c-project-heading--task">Use the colours</h2>
--- task ---
You don't need to remember the hex codes, you can just use the dictionary. 
--- /task ---

Adapt the following code to use your colour names:
<div class="c-project-code">  
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
</div>
--- task ---
Test with your own colours. Your colour name goes inside square brackets '[]' after the name of the dictionary.
--- /task ---

Now you can update the rest of the code to use colours from the dictionary
<div class="c-project-code">
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
</div>
--- task ---
Test your code to make sure your text still displays correctly.
--- /task ---


  




