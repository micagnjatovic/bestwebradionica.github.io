# ČAS 1 - subota
### HTML
- HTML tagovi, otvorena/zatvorena etiketa
- dom stablo (osnovna slika) -> validan html5 dokument
- vrste elemenata: linijski/blokovski
- elementi za grupisanje: header, nav, main, footer
- elementi za prikaz teksta: h1-h6
- ignorisanje belina, \<br>, \<hr>
- atributi
    - class
    - id
    - style
    - title
### CSS
- jezik za stilizivanje
- 3 načina uvođenja
    - style atribut
    - style element u head
    - odvojen faj \<link rel="stylesheet" type="text/css" href="putanja">
- prednosti mane
    - atribut - dosta specifično
    - style - nagurano sve u jedan fajl
    - poseban fajl - može više da koristi

```
selektor {
    svojstvo1: vrednost1;
    ...
}
```
- selektori
    - tag, npr p, div...
    - #domeID
    - .someClass
    - div p = p u divu
    - div.someClas = div sa klasom
    - div, p, span = na div, paragraf i span

- div ima id i class, id=plavo, class=crveno, div=zeleno. koje je boje?
    - id ima najveci prioritet, pa class, pa tag

- ključna reč !important
    - izbegavati
    - dva important se ponište

- imamo definisanu boju diva u css, style i atribut
    - biće koju poslednju pročita

- boje
    - name - red, green, blue
    - rgb
    - rgba
    - hex
    - hsl

- veličine
    - apsolutne - cm, mm, in, pt
    - relativne - em, %

- ulepšavanje teksta
    - font-size
    - font-style - italic, oblique
    - font-weight - bold, bolder
    - text-align 
    - letter-spacing
    - word.spacing
    - text-indent
    - text-shadow
    - font-family - serif, sans-sreif, monospace, cursice, fantasy

- uvoženje fontova - primer
```
@font-face {
    font-family: ...
    src: url("....")
}
```

### model kutije

- slika sa ramom za slike
- primena na linijski i blokovski
1. sadržaj
    - width/height
2. padding
    - padding, padding-left, padding-right...
3. border
    - border:...., border-style, border-color, border-width, border-radiui
    - nacrtati krug = border radius 50%
4. margina
    - margin, margin-left, margin-right...
    - margin auto za centriranje

- Inspect za prikaz pojaseva

### Vežba
- naprave stranicu o sebi, npr zašto su izabrali da učestvuju, čime se bave, hobiji...
- da ima naslov, da ima nekoliko paragrafa/divova, da se nešto oboji
- iskoristiti neki font sa https://fonts.google.com/ 


# ČAS 2 - nedelja

### Pozicioniranje
- koordinatni sistemi, pregledac/stranica
- z koordinata
- tip i pozicija

1. static - nema pomeranja
2. relative - static sa pomeranjem
3. abolsute - nestaticki roditelj
4. fixed - nalepljeno na stranici
5. sticky - proveriti

- svojstvo display
    - inline
    - block
    - inline-block
    - none

- visibility
    - hidden
    - nije kao display none

- slike
    - img element
    - alt obaveno
    - inline-block
    - \<figure>, \<figcaption>

- pozadine
    - background-image
    - background-size - %, px, cover, contain, auto
    - background-repeat
    - ignorise se background-image, vise kao backup
    - background-position
    - 

- gradijent
    - linear-gradient(color1, color2, ...)
        - color1 30%, color2 40%
        - to top/bottom left/right, color1, color2
    - radial-gradient(color1, color2...)
        - farthest-side/closest-side at 10% 10%, ...
        - circle at 10px 10px
        - at 10px 20px
    - repeat-gradient mozda

- liste
    - uređene
    - neuređene
    - deskriptivne, dt, dd
    - lista u listi
    - list-style-type: disc, circle, square, lower/upper-alpha, greek, armanian, roman
    - start za numerisnae
    - list-style-imgae: url(...)
    - list-style-position
    - li - staviti display inline block, primer

### Vežba
- slika kućice


# ČAS 3 - pondeljak

- tabele
- linkovi
- pseudoklase
- pseudoelemtni



### Vežba
- napraviti raspored, možda linkovi ka yt, slike, velika tabela a svaka ćelija je nešto drugo
- šahovska tabla


# ČAS 4 - utorak

- responsive



# ČAS 5 - sreda
- JS kvadrtat koji se pomera

# ČAS 6 - četvrtak
- ajax zahtevi
- naći API-eve pa da rade sta im je zanimljivo



Github page
- napraviti nalog
https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

- adresa mora da se zavrsava na .github.io