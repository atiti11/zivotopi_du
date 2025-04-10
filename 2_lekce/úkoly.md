# 1. úkol: přidávání css stylů

- pro podnadpis "Frontend developer" přidej vlastnost `color:green;` těmito způsoby:
  - zápis stylu přímo u prvku
  - pravidlo v tagu `<style>` (selektor je `header p`)
  - pravidlo v externím souboru
- do souboru styles.css zkopíruj vlastnosti ze souboru `styles_extra.css` - jedná se o vlastnosti, které si ještě nebudeme ukazovat, ale celý dokument díky nim bude vypadat lépe

# 2. úkol: selektory

Napiš css selektor pro následující elementy v index.html:

- pro všechny nadpisy 2. úrovně
- pro sekci "About me"
- pro odkaz na engeto.cz
- pro všechny odstavce a divy
- pro nadpis h2 v sekci Personal information

# 3. úkol: barvy

- na pozadí celé stránky dej barvu nějakou světle šedivou barvu pomocí rgb() funkce (můžeš využít online kalkulačku: https://www.w3schools.com/colors/colors_rgb.asp, nebo vestavěnou kalkulačku ve VS Code)
- divu se třídou "container" přidej bílou barvu na pozadí pomocí hexadecimálního zápisu (můžeš využít třeba tuto stránku: https://www.w3schools.com/colors/colors_picker.asp?color=00bfff)
- barvu všech nadpisů (h1 a h2) změň na černou (rgb(0,0,0)) s koeficientem alfa = 80%

# BONUS: barvy a pseudo-třídy

- nastav různé barvy textu pro různé stavy odkazu:
  - klasický: barva `blue`
  - aktivní: barva `green`
  - navštívený: barva `purple`
  - při najetí myší: barva `red`

# 4. úkol: proměnné

- všechny přidané barvy ulož do proměnných a použij proměnné

# 5. úkol: délkové jednotky

- upravíme obrázek:
  - výšku (`height`) a šířku obrázku (`width`) obrázku nastav na 150px
- divu se třídou `container` nastav vlastnost `padding` na 20px
- uprav výšku divu se třídou `container` tak, aby zabíral výšku celé obrazovky, ale nahoře a dole měl 10px místo

# 6. úkol: typografie

- do souboru naimportuj rodinu Ubuntu a nastav ji jako font pro celou stránku (jako záložní nastav sans-serif)
- text v celém elementu `header` zarovnej na střed
- text v sekci `about-me` zarovnej na `justify`
- nadpisům h2 nastav tučnost na 500
- velikost písma v podnadpisu změň na 18px
- nadpis h1 transformuj, ať je celý velkými písmeny

# 7. úkol: border-radius

- obrázku přidej vlastnost border-radius a hodnotu 50%
- třídě container přidej vlastnost border-radius a hodnotu 5px
