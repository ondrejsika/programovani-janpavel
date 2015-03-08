# Lekce 1 (6. 7. 2015)

* zakladni aritmeticke operace
* standartni vstup, vystup

### Bash prikazy

* cd - prepne se do adresare
* mkdir - vytvori novy adresar
* ls - vypise soubory z adresare
* touch - vytvori prazny soubor

### Editor

* sublimetext (windows/linux)

### Instalace

* virtualbox
* ubuntu - <http://ubuntu.com>

### IPython

* interaktivni shell pro Python
* viz kniha, kapitola ipython [tex](https://github.com/ondrejsika/python-kniha/blob/master/shell.tex#L2), [pdf](https://drive.ondrejsika.com/pdf/python-kniha/_build/Ondrej_Sika__Python_kniha.pdf#page=12)

### Vstup ze souboru


```
python3 program.py < vstupni_data
```

## Priklady

### Kvadraticka rovnice

``` python
import math

a = int(input('a: '))
b = int(input('b: '))
c = int(input('c: '))

d = (b**2)-4*a*c

if d < 0:
    print('Rovnice ma komplexni koreny')

if d == 0:
    x = (b**2)/(2*a)
    print('Vysledek = ', x)

if d > 0:
    x1 = ((b**2)-math.sqrt(d))/(2*a)
    x2 = ((b**2)+math.sqrt(d))/(2*a)
    print(x1, x2)
```

### Ohmuv zakon

``` python
i = input('i: ')
u = input('u: ')
r = input('r: ')

if not i:
    x = int(u) / int(r)
    unit = 'I'

if not r:
    x = int(u) / int(i)
    unit = 'R'

if not u:
    x = int(i) * int(r)
    unit = 'U'

print(unit, '=', x)
```
