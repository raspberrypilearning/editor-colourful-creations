## Challenge: More colours

Add more colours to your dictionary and test them.

## Step 1

Use [jumpto.cc/colour-picker](http://jumpto.cc/colour-picker) to find more colours.

Here is some example code that animates the text using the turtle.

```python filename="main.py" line_numbers="true" line_number_start="15" line_highlights="17-26"
hideturtle()

penup()
goto(0, 100)
color(colours['reallyraspberry'])
style = ('Arial', 40, 'bold')
write('HELLO', font=style, align='center')
right(90)
forward(60)
color(colours['verylime'])
write('WORLD', font=style, align='center')
hideturtle()
```

## Step 2

Add this to your project and change the code to use the new colours from your dictionary.

> [!TIP]
>
> The turtle starts in the centre of the screen. `goto()` moves it to a new position, and `write()` shows text where the turtle is.

## Now run your code

Run your code and check that `HELLO` and `WORLD` appear in different colours.
