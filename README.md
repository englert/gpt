# Pong – Python Turtle

Kétjátékos Pong játék a Python beépített `turtle` moduljával. A projekt tanórai példának készült: a kód változókat, függvényeket, feltételeket, billentyűzetkezelést és időzített frissítést használ.

## Követelmények

- Python 3
- Grafikus felület, amelyen a Turtle ablak meg tud jelenni

A `turtle` modul általában a Python része, külön telepítést nem igényel.

## Indítás

```bash
python3 pong.py
```

## Irányítás

- **Bal ütő:** W és S
- **Jobb ütő:** fel és le nyíl
- **Új játék:** R
- **Kilépés:** Esc

Az a játékos nyer, aki először eléri az 5 pontot.

## A játék működése

- A labda folyamatosan mozog.
- A labda visszapattan a felső és alsó falról, valamint az ütőkről.
- Ha a labda elhagyja a pályát valamelyik oldalon, a másik játékos pontot kap.
- A pontszám a képernyő tetején látható.
- Az R billentyűvel új mérkőzés indítható.

## Tanórai felhasználás

A diákok a `feladatok.md` fájlban található feladatok segítségével fokozatosan továbbfejleszthetik a játékot. Első lépésként olvassák át a kódot, indítsák el a programot, majd változtassanak meg egy-egy jól körülhatárolt részt.
