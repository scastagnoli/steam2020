# Sorgente block

![Misuratore temperature minima e massima](../img/esercizi/temperaturaMinMax.png)

# Sorgente Python
```
def on_button_pressed_a():
    basic.show_number(max2)
input.on_button_pressed(Button.A, on_button_pressed_a)

def on_button_pressed_b():
    basic.show_number(min2)
input.on_button_pressed(Button.B, on_button_pressed_b)

"""

Esercizio 2:

Calcolatore di temperatura minima e massima: salvo la temperatura minima e massima e le visualizzo sul display

Vengono automaticamente usate le variavbili min2 e max2 perchè min e max sono parole riservate
"""
min2 = 0
max2 = 0
max2 = input.temperature()
min2 = input.temperature()

def on_forever():
    global max2, min2
    if max2 < input.temperature():
        max2 = input.temperature()
    if min2 > input.temperature():
        min2 = input.temperature()
    basic.show_number(input.temperature())
basic.forever(on_forever)


```

