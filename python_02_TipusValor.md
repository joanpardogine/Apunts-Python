## Python

#  Tipus de dades i operadors

Una de les característiques que fa tan popular Python és la seva simplicitat. Aquesta simplicitat es trasllada a la poca varietat que té de tipus de dades. La llista de tipus de dades d'altres llenguatges de programació és molt extensa.

Els tipus de variables es divideixen en tres tipus.

1. Nombres
1. Text i
1. Booleans

## Nombres

**Els nombres** ***enters*** són aquells que **no tenen decimals**, tant **positius** com a **negatius** (a més del **zero**).

Els **nombres** a la vegada es divideixen en tres tipus.
Com deia aquests es divideixen en:

* **enters** (**```int```**), és a dir nommbres sencers, que no tenen part decimal.

* **decimals** (**```float```**), és a dir nommbres que tenen una part decimal. També coneguts com amb **coma flotant**.

* **especials**, aquest tipus de nombres no crec que els veiem, però cal dir que també existeixen.

## Text


![Tipus de dades](./imatges/05_python/TDD_01_TipusDeDades.png)

![Tipus d'operadors](./imatges/05_python/TDD_02_Operadors.png)

![Tipus d'operadors](./imatges/05_python/TDD_Operadors.png)

![Tipus d'operadors](./imatges/05_python/TDD_Operadors.png)

![Tipus d'operadors](./imatges/05_python/TDD_Operadors.png)

![Tipus d'operadors](./imatges/05_python/TDD_Operadors.png)

### Nombres

```python
    print(3) # => 3
```
### Operadors matemàtics.
> Les matemàtiques són el que tothom s'espera.

```python
print( 1 + 1)   # => 2
print( 8 - 1)   # => 7
print(10 * 2)   # => 20
print(35 / 5)   # => 7.0
```
### La divisió és una mica complicada. És una divisió entera i arrrodoneix el resultat automàticament.

```python
    5 / 2  # => 2
```

### Per veure la divisió no sencera cal aprendre que existeixen els valor decimals (***```float```***).

```python
    2.0  # Aquest és un decimal
    5.0 / 2.0  # => 2.5 Ara molt millor
```

### El resultat de la divisió sencera truncada tant per a positius com per a negatius.

```python
    5 // 3       #   5 / 3   =  1.66 => 1  => 1
    5.0 // 3.0   # 5.0 / 3.0 =  1.66 => 1.0 # també funciona pels decimals
    -5 // 3      #  -5 / 3   = -1.66 => 1  => 1
    -5.0 // 3.0  # => -2.0
```

> **NOTA**: per veure el tipus del que sigui, existeix la comanda **```type()```**.


