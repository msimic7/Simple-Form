# Review Branch

## Review 1
***(13.02.2019)***

---

` Nema puno koda pa nema pun toga za review, jedina stvar na koju mogu da ti skrenem paznju je **indentacija** koda.

Dakle ili koristis **space** ili **tab**, ja licno koristim **tab (tab size = 4 spaces)**; Miksovanje indentacije postane preterano ruzno na vecim projektima i sto je najgore necitljivo.

---

### Why should I Care?

Neregularna indentacija moze da "zagadi" / "isprlja" git history kada radis na projektima sa vise ljudi. Ukoliko ne usaglasite stil kucanja koda, svaki tvoj i njihov commit ce biti "dirty".

Npr: Promenis jednu liniju koda, i formatiras dokument na svoj nacin. Umesto da git pokaze kako je promenjena jedna linija i da u diff-u moze jasno da se vidi sta i na cemu je radjeno, moze da se desi da ceo dokument bude prepoznat kao diff a to niko ne zeli.

---

### How do I solve this?

Instaliras linter ili code formater i podesis ga kako si se dogovorio sa timom ili ako radis sam, podesis ga kako tebi odgovara, stavis conf za linter i formater u repo kako bi u svakom trenutku na bilo kom racunaru da povuces kod imao podesena pravila formatiranja.
