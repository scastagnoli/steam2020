# Sorgente block

![Contatore testa/croce](../img/contatoreTestaCroce.png)

# Sorgente Python
```
def resetContatori():
    global teste, croci
    teste = 0
    croci = 0
    visualizzaDati()
def visualizzaDati():
    basic.show_string("C=" + convert_to_text(croci))
    basic.show_string("T=" + convert_to_text(teste))

def on_button_pressed_a():
    global teste, croci
    if Math.random_boolean():
        basic.show_icon(IconNames.YES)
        teste += 1
    else:
        basic.show_icon(IconNames.NO)
        croci += 1
    basic.clear_screen()
    visualizzaDati()
input.on_button_pressed(Button.A, on_button_pressed_a)

def on_button_pressed_b():
    resetContatori()
input.on_button_pressed(Button.B, on_button_pressed_b)

croci = 0
teste = 0
resetContatori()
```
