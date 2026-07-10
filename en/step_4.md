## Name the colours

Add the code below to create a **dictionary** that stores names for your own colours.

> [!INFO]
> ## Why use a dictionary?
>
> Hex colour codes are flexible, but hard to remember.
> A dictionary lets you match easy-to-remember names to colour codes.

Give your hex code colours names in the dictionary.

Then update the rest of the code to use the names inside square brackets `'[ ]'`.

```python filename="main.py" line_numbers="true" line_number_start="1" line_highlights="3-6,10,12"
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
```

> [!TIP]
>
> Put a comma `,` between each item in the dictionary.

## Now run your code

Test the code and check that your design still appears using your named colours.
