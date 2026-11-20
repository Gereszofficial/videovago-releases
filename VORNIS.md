# Vornis Pro

Legfrissebb verzió: 0.6.4

- AI Stúdió – CS2: a lövés pontosan az ütemen szól. A killfeed sora ~80 ms-mal a lövés után jelenik meg; a montázs most a lövést teszi az ütemre (a játék hangjából ezredmásodpercre, ahogy a profi editekben – 7 profi videón lemérve)
- Javítva: sok rövid snittes montázsnál a kész filmben a kép fokozatosan lemaradt a zenétől (3 perc alatt kb. 0,4 mp) – most a film végéig kockapontos (mérve: 132 snittes, 3 perces montázson a kép és a zene eltérése végig 1 kockán belül)
- „Tanulj a referenciákból”: az AI Stúdió lemér minden videót a Videók mappa „referencia” nevű mappáiban (vágások, ütemek, killek, a lövés helye), és megtanulja belőlük a stílust – a highlight-mappából a CS2 Highlightot, az edit-mappából a CS2 Frag montázst
- A csevegőben a tempó is állítható a kiválasztott stílushoz képest: „gyorsabb vágás”, „rövidebb snittek”, „pörgősebb” – vagy „hosszabb snittek”, „nyugodtabb”
- Több hangsávos játékfelvételek (SteelSeries Moments, NVIDIA): a program a játék hangját használja – az üres sávot, a csevegést és a mikrofont kihagyja
- Javítva: ha egy felvétel kör közben indul, a killfeedben már látszó régi killek nem számítanak új killnek (eddig hamis killek kerültek a klip elejére)
- CS2 Frag montázs: a profi editek mért snitthosszához igazítva (a legrövidebb snitt 0,85 mp)
