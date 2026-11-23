# Vornis Pro

Legfrissebb verzió: 0.6.6

- AI Stúdió: érti az új átmeneteket név szerint (whip pan, zoom-ütés, fényrobbanás, fénycsík…), a „mozgó cím: GG” kérésre Varázsmozgás-címet tesz, a „legyen profi a hang” csak a hangon dolgozik (nem nyúl a vágáshoz), és ugyanaz a lépés nem kerül kétszer a tervbe
- AI Stúdió – CS2: okos pontrendszer (fejlövés, füst, no-scope, pisztolyos fejlövés, sorozatok, clutch), a montázs dramaturgiája: erős nyitás, fokozás, a legjobb kill a dropon, csúcspont a végén
- AI Stúdió – CS2: lassítás a lövés után, fehér villanás és ostorcsapás az ütemen, minimális, a játékhoz illő színezés; a saját nézőpont felismerése, az asszisztok kiszűrése
- Kockapontos export automatikus szinkron-ellenőrzéssel (a lövés az ütemen marad a kész filmben is)
- Javítva: álló (9:16) videónál az Effektek oldal az átmeneteket (kör, törlés) is a kép valódi arányában mutatja, ugyanúgy, mint a kész film
- Javítva: a vágás mindig kockára kerül (lejátszás után megállítva is), a kész film nem csúszik el egy kockával
- Javítva: az AI felskálázás ráhagyással készül, így a felskálázott klipnél is a vágásra kerül az átmenet
- ✨ Egész film egy kattintással (Kezdő mód): a program megnézi az összes klipet, mindegyikre a tartalmához illő csomagot teszi, és a film jellegéhez illő átmenetet minden vágásra
- ✨ Átmenet minden vágásra egy kattintással (Átmenetek fül): Lágy, Pörgős vagy Filmes stílus – váltakozva, a klipek hosszához igazítva
- Követő Varázsmozgás: a betűk és rajzok egy mozgó tárgyhoz ragadhatnak – jelöld ki a tárgyat (Követ sor), ⌖ Követés, és a felirat vagy a nyíl vele együtt mozog (mint a sportközvetítésekben)
- Varázsmozgás: igazítás és elosztás a kijelölt tárgyakra – egy sorba, egy oszlopba, egyenletesen (vízszintesen, függőlegesen), középre
- Varázsmozgás: jelenetsáv a nézőn – a jelenetek ◆ jelei és a lejátszófej a kép tetején; kattintással ugrás, a ◆ húzásával a jelenet átidőzíthető
- ✨ Profi hang egy kattintással (Hang oldal): beszédtisztítás AI-jal → a zene halkul a beszéd alatt → normalizálás a kiválasztott kiadási célra, valódicsúcs-határral – egymás után, a háttérben
- Hang oldal – Gyors javítások egy kattintással: 🎙 Beszéd tisztítás (AI zajszűrés a gépen), 🎵 Zene halkul (a zene magától halkul, amikor valaki beszél), ♪ Ütemek (a zene ütemei jelölőként – a vágás és a dinamikus zoom ezekre pattan)
- Kiadási hangosság a Hang oldalon: YouTube −14 (Spotify is), Podcast −16 (Apple Music is), TV −23, Mozi −24, Netflix −27 LUFS – a Normalizálás a valódi csúcsot (true peak) is megméri, és a limitert a határ alá állítja (−1, a mozinál és a Netflixnél −2 dBTP)
- ✨ Javaslat a Kezdő módban: a program megnézi a klipet (akció, tánc, táj, beszéd, nyugodt, képernyő), és kiemeli a hozzá legjobban illő kész csomagot
- 🎉 4 új VFX-részecske az egész képen (CGI): Konfetti, Parázs, Fénypor, Csillogás – a sűrűség és a szél állítható; két új kész csomag a Kezdő módban: 🎉 Buli és 🔥 Tábortűz
- 6 mozgó cím-sablon a Varázsmozgásban egy kattintással: Összeáll, Nagy belépő, Pörgő, Hullám, Robbanás, Beúszás – a beírt szövegre vagy a kijelölt betűkre, utána minden jelenet szabadon húzható
- ✨ Fénycsík átmenet: egy ragyogó, ferde fénysáv söpör át a képen, mögötte már a következő jelenet
- ◎ Kör a célpontból: a következő jelenet egy világító peremű körben nyílik ki – a pontot a nézőn választod ki, vagy a bejövő klip kijelöléséből (például a dinamikus zoom célpontjából) jön
- Átmenetek könyvtára: vidd az egeret egy átmenet fölé, és a kis képe élőben lejátssza – így könnyebb választani
- 4 új filmes whip pan átmenet (balra, jobbra, fel, le): a kamera gyorsan elrántódik, erős irányított mozgáselmosással, a csúcson vált a következő jelenetre – mint a profi edit videókban
- Kezdő / Haladó / Profi mód az Effektek oldalon: Kezdőként 10 kész csomag egy kattintással (Mozis, 🏍 Motoros akció, Pörgős TikTok, Álomszerű, Nosztalgia, Neon éjszaka, Kristálytiszta, Fekete-fehér film); a választott szint megmarad
- 🎯 Dinamikus zoom (Élő mozgás): húzd a keretet a tárgyra, és a kamera filmesen ráközelít – ⌖ Követéssel a mozgó tárgyat (például a motorost) simán követi, a ♪ gombbal a zene ütemeire üt; a kép széle sosem látszik
- ↔ Oldalfogók a Varázsmozgásban: egy kijelölt tárgy kerete vele fordul, és az oldalak közepén lévő fogókkal csak szélességben vagy csak magasságban nyújtható – a nyújtás is simán átúszik a jelenetek között
- ✛ Igazítósegéd a Varázsmozgásban: húzáskor a tárgy a kép közepére, széleire és a többi tárgyhoz pattan, rózsaszín segédvonal mutatja; forgatáskor a derékszögek vonzanak (Alt: szabadon)
- ⤡ Fogantyúk a Varázsmozgásban: a kijelölt tárgyak körül keret – a sarkokat húzva méretezel, a felső kerek fogóval forgatsz (Shift: 15°-onként), a keretben húzva mozgatsz; több kijelölt tárgy együtt, a közös közepük körül
- ⇄ Alakzat-átalakulás a Varázsmozgásban: jelölj ki két tárgyat, és az első folyékonyan a második alakjába formálódik – betűből rajz (az „a”-ból bevásárlókocsi), rajzból betű, rajzból rajz; rétegek lista, több kijelölés, jelenetek másolása és tologatása
- ✦ Varázsmozgás (Animáció → Címek): írj szöveget vagy rajzolj egérrel – a betűk és a rajzok külön tárgyak, egérrel pakolhatók; jelenetenként rendezd át őket, a program simán átúsztatja (sima, rugós, lendületes mozgás; ami eltűnik, mozgáselmosással elúszik; a rajz megrajzolódik)
- 8 új, látványos átmenet: Zoom-ütés, Zoom-alagút, Fényrobbanás, Pörgés, Dőlő zoom, Becsapódás, Fekete ütés, Lágy zoom-áttűnés – a két klip kockánként mozog, nagyít, forog, villan
- Javítva: a Lélegző fókusz, az RGB lüktetés, a Délibáb és az Ultra 4K élesség most jól látszik (eddig alig vagy egyáltalán nem)
