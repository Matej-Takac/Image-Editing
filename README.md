# Image Editor

Image Editor je webová aplikácia na jednoduchú úpravu obrázkov priamo v prehliadači. Používateľ môže nahrať obrázok, upraviť ho pomocou filtrov a nástrojov, porovnať pôvodnú a upravenú verziu a následne výsledok uložiť alebo exportovať.

## Ako spustiť projekt

Projekt sa spúšťa otvorením súboru `index.html` v prehliadači.

Aplikácia funguje lokálne a nevyžaduje databázu ani server.

## Základné používanie

Po otvorení stránky sa zobrazí editor obrázkov. V strede stránky je pracovná plocha, naľavo sa nachádza panel nástrojov, napravo panel úprav a v spodnej časti sú filtre.

Používateľ najskôr klikne na tlačidlo **Open** alebo presunie obrázok do pracovnej plochy. Po načítaní obrázka môže použiť jednotlivé nástroje a následne obrázok uložiť.

## Tlačidlá v hornej časti

### Späť

Tlačidlo **Späť** slúži na návrat na hlavný portál.

### Open

Tlačidlo **Open** otvorí výber súboru z počítača. Používateľ si vyberie obrázok, ktorý sa následne zobrazí v editore.

### Save

Tlačidlo **Save** uloží aktuálne upravený obrázok ako PNG súbor s názvom `image-save.png`.

### Export

Tlačidlo **Export** exportuje aktuálne upravený obrázok ako PNG súbor s názvom `image-export.png`.

## Nástroje na ľavej strane

### Adjust

Nástroj **Adjust** slúži na základné úpravy obrázka pomocou posuvníkov v pravom paneli.

### Filters

Nástroj **Filters** slúži na výber prednastavených filtrov v spodnej časti stránky.

### Crop

Nástroj **Crop** oreže obrázok na štvorec podľa kratšej strany obrázka.

### Transform

Nástroj **Transform** otočí obrázok o 90 stupňov.

### Draw

Nástroj **Draw** umožňuje kresliť priamo do obrázka myšou.

### Text

Nástroj **Text** umožňuje vložiť vlastný text do obrázka.

### Stickers

Nástroj **Stickers** vloží do obrázka náhodnú dekoratívnu nálepku.

### Blur

Nástroj **Blur** rozmaže aktuálny obrázok.

### Remove BG

Nástroj **Remove BG** sa pokúsi odstrániť pozadie obrázka. Funguje najlepšie pri jednoduchom jednofarebnom pozadí.

## AI Enhance

Tlačidlo **AI Enhance** automaticky nastaví viacero úprav naraz. Zvýši jas, kontrast, sýtosť, tiene a ostrosť obrázka.

V tejto verzii nejde o skutočnú umelú inteligenciu, ale o prednastavené automatické vylepšenie obrázka jedným kliknutím.

## Pracovná plocha

V strede stránky sa nachádza hlavné plátno, na ktorom sa zobrazuje obrázok. Pred nahratím obrázka sa zobrazí výzva na vloženie obrázka.

Po nahratí sa zobrazí aj rozlíšenie obrázka.

## Zoom

Tlačidlo **+** obrázok priblíži.

Tlačidlo **−** obrázok oddiali.

Tlačidlo **Fit** vráti priblíženie späť na 100 %.

## Before / After

Tlačidlo **Before / After** zapne porovnanie pôvodnej a upravenej verzie obrázka. Po zapnutí sa zobrazí deliaca čiara, ktorú je možné posúvať.

## Pravý panel úprav

### Brightness

Mení jas obrázka.

### Contrast

Mení kontrast obrázka.

### Saturation

Mení sýtosť farieb.

### Highlights

Upravuje svetlé časti obrázka.

### Shadows

Upravuje tmavé časti obrázka.

### Sharpness

Upravuje ostrosť obrázka.

### Reset

Tlačidlo **Reset** vráti všetky hodnoty úprav na pôvodné nastavenie.

## Histogram

Histogram zobrazuje rozloženie farieb v obrázku podľa kanálov:

- R – červená
- G – zelená
- B – modrá

Histogram sa mení podľa aktuálnych úprav obrázka.

## Info panel

Panel **Info** zobrazuje základné informácie o nahratom obrázku:

- rozlíšenie,
- veľkosť súboru,
- formát,
- čas vloženia obrázka do editora.

## Filtre

V spodnej časti stránky sa nachádzajú prednastavené filtre. Po kliknutí na filter sa automaticky upravia hodnoty jasu, kontrastu, sýtosti, tieňov, svetiel a ostrosti.

Dostupné kategórie filtrov sú napríklad:

- All Filters
- Popular
- Cinematic
- Nature
- Black & White
- Portrait
- Vintage
- Moody

## Technológie

Projekt je vytvorený pomocou:

- HTML
- CSS
- JavaScript
- Canvas API

Všetky úpravy obrázka prebiehajú lokálne v prehliadači.

## Zhrnutie

Image Editor umožňuje nahrať obrázok, upraviť ho pomocou filtrov a nástrojov, porovnať pôvodnú a upravenú verziu a výsledok uložiť ako PNG súbor.
