# Sorgente block

![Temperatura media](../img/esercizi/temparaturaMedia.png)

# Sorgente Python
```
temperatura = 0
somma = 0
contatore = 0

def on_forever():
    global temperatura, contatore, somma
    temperatura = input.temperature()
    if contatore < 5:
        contatore += 1
        somma = somma + temperatura
        basic.pause(1000)
    else:
        serial.write_line("" + str((somma / contatore)))
        contatore = 0
        somma = 0
basic.forever(on_forever)
```
