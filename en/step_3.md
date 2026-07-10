## Colourful text

Choose a hex colour code for text.

Choose a colour from [jumpto.cc/colour-picker](http://jumpto.cc/colour-picker) and copy the hex code that starts with `#`.

In the code below swap `'pink'` for your hex code.

```python filename="main.py" line_numbers="true" line_number_start="1" line_highlights="7-10"
from turtle import *

screen = Screen()
screen.setup(400, 400)
screen.bgcolor('#A7E30E')

color('pink')
style = ('Arial', 40, 'bold')
write('HELLO', font=style, align='center')
hideturtle()
```

## Now run your code

Check that the text appears.

Try different colours until you find text and background that look good together.

> [!TIP]
>
> You can change the font and size.
>
> Try using `'Verdana'`, `'Times'` or `'Courier'`.
>
> `40` is the font size, try changing that too.
