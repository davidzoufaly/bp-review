# Meta-meta-analýza bakalářské práce

> Finální syntéza tří metaanalýz bakalářské práce „Protivirová imunitní odpověď u flavivirů a její možné úskalí: zaměření na NS1 protein" (Lucie Novotná, PřF JU 2026)

> Metodická poznámka: Vstupem jsou tři metaanalýzy (M1, M2, M3), z nichž každá už syntetizovala sedm externích review. Text práce (`input/bp.txt`) byl otevírán pouze cíleně při rozporech. Finální syntéza váží důkazní oporu jednotlivých tvrzení, nerovná jejich průměr. Závažnost: **[KRITICKÁ]**, **[VYSOKÁ]**, **[STŘEDNÍ]**, **[NÍZKÁ]**. Epistemický status: *prokázaná chyba* / *pravděpodobný problém* / *podezření k ověření*.

---

## Executive summary

Tři metaanalýzy se sbíhají k podobnému jádru, ale výrazně se liší v šíři záběru, v přesnosti fact-checkingu a v ochotě nekriticky přebírat tvrzení slabších externích review.

**Stabilní konsenzus napříč všemi třemi syntézami:**

- Práce má reálné experimentální jádro, obhajitelný biologický smysl a transparentně přiznanou AI-asistenci pro jazykovou korekturu.
- Bibliografie obsahuje prokazatelné duplicitní páry se stejným DOI (`Conde`, `Lindqvist`, `Muller & Young`, `Rastogi`) — nejzávažnější formální vada práce.
- V textu je prokázaná terminologická chyba `NK-κB` místo `NF-κB`, reprodukovaná v seznamu zkratek.
- `CCR5` je v textu uveden jako chemokin, ačkoli jde o chemokinový receptor; práce si tím protiřečí, protože seznam zkratek jej definuje správně.
- Položka `Apoorva et al.` v bibliografii nese `(b.r.)`, zatímco in-text odkaz má `(2024)` — přímá vnitřní nekonzistence.
- Jazyk metodiky sklouzává do laboratorního slangu a překladových kalků.
- Statistická část je limitována `n = 4`; autorka to v textu převážně přiznává.
- Žádná z metaanalýz nepředložila oporu pro kategorické obvinění z plagiátorství ani AI-generování obsahu.

**Meta-meta-analýza ale zjistila i tři jevy, které nelze jen sumarizovat:**

1. **M1 identifikuje dvě unikátní zjištění, která M2 a M3 přehlédly.** Numerická neshoda `0,56 mg/ml` vs `0,58 μg/ml` ve standardech NS1 (řádový rozdíl × 1 000) a kauzální chyba v textu o fagocytóze mikroglií zvyšující titr. Obojí podle M1 ověřené v bp.txt.
2. **M2 a M3 korigují tři chybné fact-checky, které M1 převzala z externích analýz.** Položka `Sabir & Jan (2026)` není po ověření NCBI Bookshelf „anachronismem"; StatPearls používá `2026 Jan-` s aktualizací v prosinci 2025. Opatření P5 nevyžaduje klíčová slova na bibliografickém listu ani studijní program na titulním listu v podobě, jak tvrdila M1 (resp. jedna z jí převzatých externích analýz). Online-first vs issue-year rok u `Wahaab et al.` není „jediný správný rok", nýbrž legitimní citační nuance.
3. **M3 jako jediná systematicky diagnostikuje slepé místo seznamu zkratek** — nejen chybné `NK-κB`, ale i chybějící (`IFNAR1`, `TYK2`, `HMC3`, `HBVP`, `SK-N-SH`) a přebytečné položky.

Po vážení důkazů je finální obraz tento: **práce je obsahově obhajitelná, ale textově a formálně nedotažená způsobem, který zbytečně poskytuje oponentovi snadné terče.** Kumulace několika středně závažných vad (bibliografie, terminologie, metodická transparentnost, jazyk) je nebezpečnější než kterákoli z nich izolovaně.

---

## Finální verdikt

**Práce je podmíněně připravena k odevzdání po nezbytných opravách.** Vědecké jádro experimentu obstojí — data jsou reálná, metodika je v zásadě reprodukovatelná a závěry jsou v textu převážně formulovány opatrně, s uznáním statistické neprůkaznosti při `n = 4`.

Práce však trpí čtyřmi typy selhání, které musí být adresovány před odevzdáním:

1. **Věcné terminologické chyby** (`NK-κB`/`NF-κB`, `CCR5` jako chemokin, `G-protein`/`Protein G`, `astroglykóza`/`astroglióza`) — každý z nich je samostatně opravitelný v řádu minut, jejich kumulativní dopad na důvěryhodnost textu je však vysoký.
2. **Systémové bibliografické vady** (4 duplicitní páry se stejným DOI, `Apoorva (b.r.)` vs `Apoorva 2024`) — viditelné na první pohled a signalizují nevyčištěný export z citačního manažeru.
3. **Metodická neprůhlednost** (statistické spojení sérií s odlišným promývacím protokolem, výměna poloviny média bez korekce ředění, poměrová Two-way ANOVA jako hlavní inferenční konstrukce, neostré oddělení vlastních dat a dat Mgr. Kotounové).
4. **Jazyková nedotaženost** (laboratorní slang v metodice, kalky, stylová heterogenita mezi uhlazenými a syrovějšími částmi).

Jazyková revize samostatně by práci nepoložila. Kombinace věcných a bibliografických chyb ano — ne jako odborná diskvalifikace, ale jako snadno napadnutelný povrch při obhajobě. Obhajoba je reálná, pokud autorka přizná vady přesně a ukáže, že navzdory nim experimentální jádro stojí.

---

## Vyhodnocení kvality jednotlivých metaanalýz

### Metaanalýza 1

**Silné stránky.** Nejforenzněji formulovaná syntéza. Jako jediná identifikuje a potvrzuje v bp.txt dvě zjištění přehlédnutá M2 i M3:

- **Numerická neshoda** zásobní vs pracovní koncentrace standardu NS1 (`0,56 mg/ml` vs `0,58 μg/ml`) s řádovým rozdílem × 1 000, bez vysvětlení v textu.
- **Kauzální chyba** v teoretické části: tvrzení, že „rychlé a efektivní pohlcení viru [mikrogliemi] ... může mít za následek vysoké virové titry" — fagocytóza by titr biologicky snižovala, ne zvyšovala.

Dále forenzní annex systematicky a přesvědčivě pojmenovává oponenturní scénáře a přesně lokalizuje slabiny metodiky (změna promývacího protokolu, diluce po výměně média, poměr `titr/NS1`).

**Slabiny.** Nekriticky přebírá z některých externích analýz tři sporné závěry:

- Tvrdí, že `Sabir & Jan (2026)` je anachronický záznam, aniž by provedla aktuální ověření NCBI Bookshelf.
- Implicitně přejímá požadavek klíčových slov z P5 (ač M2 a M3 ukazují, že P5 to nepožaduje).
- Bibliografickou diagnózu u online-first článků formuluje kategoričtěji, než dovoluje evidence.

M1 nejvíce přeceňuje závažnost `G-protein/Protein G`: označuje ji jako `[KRITICKÁ]` na úrovni `NK-κB`. Tato rovina je přehnaná — chyba je reálná a `[VYSOKÁ]`, ale nepatří do stejné kategorie jako duplicitní bibliografie nebo terminologická chyba reprodukovaná v seznamu zkratek.

**Verdikt.** Diagnosticky nejtvrdší a unikátně přínosná metaanalýza, která ale místy přebírá bez filtru některé slabší závěry z externích review.

### Metaanalýza 2

**Silné stránky.** Nejlépe odfiltrovaný balanced syntézní postoj. Systematicky označuje, co je *prokázaná chyba* vs *podezření k ověření*. Správně koriguje tři rozšířené mýty:

- Rok `2026` u Sabir & Jan není budoucnost; NCBI Bookshelf to potvrzuje.
- AI-deklarace práce uvádí nástroj i účel a není „příliš vágní".
- Stylistická heterogenita je signál AI-korektury, ne důkaz AI-generování.

Velmi disciplinovaně oddělí „prokázanou chybu práce" od „chybného fact-checku externí analýzy" — tato meta-úroveň je v M2 nejčistší.

**Slabiny.** Menší pokrytí v detailech než M1 a M3. Chybí explicitní diagnostika seznamu zkratek a kauzální chyba fagocytózy. Numerická neshoda `0,56/0,58` přehlédnuta. Forenzní annex je nejslabší z trojice — méně konkrétních oponenturních scénářů.

**Verdikt.** Nejvyváženější a nejdisciplinovanější metaanalýza z hlediska epistemické čistoty. Pro finální verdikt je nejspolehlivější vrstvou.

### Metaanalýza 3

**Silné stránky.** Nejširší pokrytí a nejjemnější odstupňování jistoty. Jako jediná systematicky diagnostikuje problém seznamu zkratek (`IFNAR1`, `TYK2`, `HMC3`, `HBVP`, `SK-N-SH` chybí; některé položky přebývají). Rozpoznává vlastní věcnou chybu externí analýzy 3 (tvrzení „10 strukturálních proteinů" — flaviviry mají 3 strukturální a 7 nestrukturálních). Správně upozorňuje, že údaj „více než 70 flavivirů" nelze bez kontextu zdroje hodnotit jako chybu (ICTV nomenklatura se v posledních letech měnila). Nejlépe rozlišuje online-first a issue-year u `Wahaab et al.` a `Apoorva et al.`.

**Slabiny.** Stejně jako M2 přehlíží numerickou neshodu `0,56/0,58 mg/ml` a kauzální chybu fagocytózy. Místy mírnější verdikt u jednotlivých chyb (`CD8+ cytokiny` jako „zjednodušující tvrzení" vs M1 jako „prokázaná nepřesnost") — v tomto bodě je M1 přesvědčivější.

**Verdikt.** Nejkomplexnější a metodicky nejpoctivější metaanalýza. V kombinaci s M1 (forenzní zjištění) a M2 (epistemická disciplína) tvoří nejsilnější vstup pro finální syntézu.

**Relativní kvalita:**

| Dimenze | M1 | M2 | M3 |
|---------|----|----|----|
| Forenzní hloubka | **Nejsilnější** | Střední | Silná |
| Epistemická disciplína | Střední | **Nejsilnější** | Silná |
| Pokrytí | Silné | Střední | **Nejsilnější** |
| Fact-check spolehlivost | Střední | **Nejsilnější** | Silná |
| Unikátní přínos | Numerická neshoda, kauzální chyba fagocytózy | Korekce falešných premis (Sabir, P5) | Audit seznamu zkratek, taxonomická nuance |

---

## Shody napříč metaanalýzami

Následující závěry jsou potvrzené všemi třemi syntézami a mají status **prokázaná chyba / pravděpodobný problém** s vysokou důkazní oporou:

### Věcné chyby

- **[KRITICKÁ]** `NK-κB` místo `NF-κB` v textu i v seznamu zkratek. Chyba je vnitřně nekonzistentní — na jiném místě textu je `NF-κB` uvedeno správně.
- **[VYSOKÁ]** `CCR5` označen v textu jako „chemokin", ač v seznamu zkratek je definován správně jako „Receptor pro chemokiny typu C-C (typ 5)". Vnitřní rozpor v jednom dokumentu.
- **[VYSOKÁ]** `G-protein` použit v sekci 7.4 o purifikaci protilátek, vzápětí správně komerční název „Protein G Sepharose 4 fast flow" — signální G-protein a imunoglobulin-vázající Protein G jsou rozdílné entity.

### Bibliografie

- **[KRITICKÁ]** Čtyři duplicitní páry se stejným DOI: `Conde et al. (2017a/b)`, `Lindqvist et al. (2016a/b)`, `Muller & Young (2013a/b)`, `Rastogi et al. (2016a/b)`. Harvard sufix `a/b` označuje různé práce téhož kolektivu v témže roce; zde jsou to duplikáty téže práce.
- **[VYSOKÁ]** `Apoorva et al. (b.r.)` v bibliografii vs `(Apoorva et al., 2024)` v textu; DOI `10.1080/21688370.2024.2424628` obsahuje rok 2024.

### Metodika a statistika

- **[VYSOKÁ]** Statistické spojení biologických replikací s odlišným promývacím protokolem (2 vs 4 cykly) do jediné ANOVA bez citlivostní analýzy; autorčino hodnocení „drobná změna" je hodnotový soud bez metodické opory.
- **[STŘEDNÍ]** Spearmanovy korelace při `n = 4` mají omezenou vypovídací sílu; koeficient ρ ≈ 1,000 u endotelů je artefakt monotónního trendu ve čtyřech bodech.
- **[STŘEDNÍ]** Poměr `virový titr / NS1` jako hlavní proměnná pro Two-way ANOVA je metodicky slabší než samostatná analýza čitatele a jmenovatele.
- **[STŘEDNÍ]** Smíšení vlastních dat autorky a dat Mgr. Eliška Kotounové je přiznáno, ale nedostatečně ostře vymezeno.

### Jazyk a styl

- **[VYSOKÁ]** Laboratorní slang v metodice (`dodělané post-hoc testy`, `stáčený na centrifuze`, `oživení buněk`, `Mili Q`).
- **[STŘEDNÍ]** Stylistická heterogenita — uhlazenější front matter a teoretické pasáže kontrastují se syrovější metodikou. Konzistentní s deklarovanou AI-korekturou, nikoli s AI-generováním obsahu.

### AI a etika

- **[NÍZKÁ]** Deklarace použití `ChatGPT` je transparentní, obsahuje nástroj i účel. Žádná metaanalýza nepředložila oporu pro tvrzení o AI-generování experimentálního obsahu nebo plagiátorství.

---

## Rozpory mezi metaanalýzami a jejich řešení

### Rozpor 1: `Sabir & Jan (2026)` — anachronismus, nebo slabý zdroj?

- **M1**: „prokázaná chyba" (rok 2026 anachronický, chybní autoři, špatný formát).
- **M2 a M3**: ověřily aktuální stav NCBI Bookshelf — StatPearls uvádí `2026 Jan-` s aktualizací prosinec 2025. Rok není chyba. Výhrada je jinde: StatPearls je encyklopedický zdroj metodicky slabší než oborová učebnice či review pro tvrzení o adaptivní imunitě.

**Řešení.** Převažuje M2/M3. Aktivní ověření autoritativního zdroje přebíjí rétorickou jistotu M1. V syntéze je tato položka klasifikována jako **[STŘEDNÍ]** bibliograficky-metodická výhrada (volba zdroje), nikoli jako **[VYSOKÁ]** anachronismus.

### Rozpor 2: Opatření P5 — klíčová slova a studijní program povinné?

- **M1**: mezi doporučenými opravami má „doplnit klíčová slova (cs/en) na bibliografický list dle P5".
- **M2 a M3**: ověřily aktuální znění P5 ze dne 1. 11. 2024 a konstatují, že tyto požadavky P5 neukládá.

**Řešení.** Převažuje M2/M3. M1 převzala premisu z externí analýzy bez ověření normativního pramene. V syntéze se tyto body z top priority fixes odstraňují.

### Rozpor 3: Závažnost `G-protein/Protein G`

- **M1**: `[KRITICKÁ]`, na úrovni `NK-κB`, samostatně dostatečná pro záporné stanovisko oponenta.
- **M2**: `[VYSOKÁ]`, v biochemickém kontextu věcně nebezpečná.
- **M3**: reálný terminologický problém, ale ne „kritický bod celé práce", symptom nepečlivosti.

**Řešení.** Kompromis M2/M3. Záměna signálního G-proteinu a streptokokového Proteinu G je věcná, ne stylistická chyba, a biochemicky vzdělaný oponent si ji všimne. Ale na rozdíl od `NK-κB` není reprodukovaná v seznamu zkratek a text vzápětí uvádí správný komerční název „Protein G Sepharose 4 fast flow", což naznačuje, že jde o jazykovou nepečlivost, ne o pojmové nepochopení. Klasifikace **[VYSOKÁ]**.

### Rozpor 4: `Wahaab et al.` rok publikace

- **M1**: nezmiňuje explicitně.
- Některé externí analýzy v M2 a M3: „2024 je chyba, mělo by být jinak".
- **M2 a M3**: rozlišují online-first (`2024 Dec 24`) a issue-year (2025). Není to chyba, ale nekonzistentní citační režim.

**Řešení.** M2 a M3 poskytují přesnější diagnózu. Bod se z „prokázaná chyba" degraduje na **[STŘEDNÍ]** nekonzistentní citační praxi u online-first záznamů v celém seznamu.

### Rozpor 5: Numerická neshoda `0,56 mg/ml` vs `0,58 μg/ml`

- **M1**: prokázaný nesoulad, potvrzeno v bp.txt, vyžaduje vysvětlení autorky.
- **M2 a M3**: nezmiňují.

**Řešení.** Zde M1 sama zjišťuje unikátní nález. Není kontraevidence. V syntéze se zachovává jako **[STŘEDNÍ]** *pravděpodobný problém* s epistemickým statusem „ověřený nesoulad v textu; příčina (zásobní vs pracovní koncentrace?) vyžaduje doplnění autorkou". Technicky ověření v bp.txt nelze nyní z technických důvodů grepem přímo replikovat, ale M1 tvrdí ověřenost explicitně a nebyla zpochybněna jinou evidencí.

### Rozpor 6: Kauzální chyba fagocytóza → virový titr

- **M1**: identifikována; tvrzení, že „rychlé a efektivní pohlcení viru [mikrogliemi] ... může mít za následek vysoké virové titry" je biologicky vadné.
- **M2 a M3**: nezmiňují.

**Řešení.** Unikátní nález M1 bez protievidence. Status **[STŘEDNÍ]** *pravděpodobná logická chyba v teoretické části*, vyžaduje přeformulování.

### Rozpor 7: Astroglykóza vs astroglióza

- **M1**: `[VYSOKÁ]`, prokázaná terminologická chyba.
- **M3**: zmiňuje jako „nestandardní `astroglykóze`".
- **M2**: explicitně nezmiňuje.

**Řešení.** Konsenzus M1/M3. Standardní termín je *astroglióza* (reaktivní astrocytární odpověď). Klasifikace **[STŘEDNÍ]** — chyba je reálná, ale rozsah výskytu v textu je omezený.

---

## Společně přehlédnuté oblasti

Následující body buď nebyly pokryty žádnou metaanalýzou, nebo byly pokryty nedostatečně. Jsou to zbytkové slepé skvrny syntézního procesu:

### 1. Úplný bibliografický audit po DOI

Všechny tři metaanalýzy pracují s několika highlights (duplicity, `Apoorva`, `Sabir`, `Wahaab`, `Liang & Dai`, `Fares`). Žádná neprovedla systematickou kontrolu každé položky seznamu literatury proti autoritativním databázím. To zůstává otevřené — s vysokou pravděpodobností existují další nekonzistence u online-first publikací a u záznamů s neúplnými metadaty.

### 2. Plagiátorství a textová podobnost

Všechny tři metaanalýzy se shodují, že bez similarity reportu (Turnitin, iThenticate) nelze plagiátorství posoudit. Shodně se tedy *nevyjadřují* — což je epistemicky správné, ale prakticky to znamená, že tato dimenze kvality práce zůstává neověřená. Pro vedoucího práce to je otevřený bod před odevzdáním.

### 3. Technická kompatibilita PDF/A, podpis, datum, layout

Z textového extraktu `bp.txt` nelze rozhodnout soulad s P5 v technické rovině. Všechny tři metaanalýzy to přiznávají. Bod zůstává otevřený a musí být ověřen na finálním PDF.

### 4. Výměna poloviny média jako analytický faktor

M1 a M3 zmiňují — výměna 125 μl média ve 3. a 6. dni způsobuje ředění, a efekt na interpretaci časových trendů koncentrací NS1 a virového titru není v diskuzi explicitně ošetřen. M2 tento bod nepokrývá systematicky. Jde o **[STŘEDNÍ]** *pravděpodobný metodický problém* vyžadující explicitní větu v diskuzi.

### 5. Tematická eklektičnost ADE u TBEV

Pouze M1 forenzní annex okrajově zmiňuje, že kapitola 4.4 o ADE (antibody-dependent enhancement) je klinicky relevantní primárně u DENV/ZIKV, nikoli u TBEV. Pro experimentální práci zaměřenou na TBEV je to tematické oslabení, které by mělo být buď odůvodněno, nebo kapitola zúžena. Žádná z metaanalýz to plně nerozvedla.

### 6. Kontrola tvrzení o NS1 proteinu

Formulace „Geny NS1 proteinu kódují 352-aminový polypeptid" je v M3 zmíněna jako „nehotová". Žádná z metaanalýz neověřila literárně správnou délku NS1 (literaturně ~352 aa pro dospělý flavivirový NS1 je správný řád; formulace je terminologicky nedotažená, ne faktograficky chybná). Zůstává otevřené, zda v celém textu chybí kritické faktografické údaje.

### 7. CD8⁺ cytotoxické T-lymfocyty a „protizánětlivé cytokiny"

M1 tvrdě jako **[VYSOKÁ]** *prokázaná nepřesnost* (CD8+ produkují IFN-γ a TNF-α, prozánětlivé). M3 měkčí („zjednodušující tvrzení"). M2 explicitně nezmiňuje. Síla důkazu zůstává nejasná bez přímé citace kontextu v bp.txt; pravděpodobně **[STŘEDNÍ]** nepřesnost.

### 8. Obhajobová strategie

Všechny tři metaanalýzy identifikují rizika, ale žádná neformuluje explicitní doporučenou obhajobovou strategii pro autorku (jak přiznat jednotlivé vady, jaké formulace použít pro obranu poměrové ANOVA, jak rámovat limity n = 4). Pro vedoucího práce to je chybějící praktická vrstva.

---

## Finální syntéza zjištění

### A. Věcné terminologické chyby (všechny ověřitelné v textu)

**[KRITICKÁ] NK-κB místo NF-κB.** *Prokázaná chyba* v těle textu i v seznamu zkratek. Vnitřně nekonzistentní, protože `NF-κB` se v jiné pasáži vyskytuje správně. Tři různé metaanalýzy potvrzují.

**[VYSOKÁ] CCR5 jako „chemokin".** *Prokázaná chyba* v kapitole 4.3. Vnitřní rozpor s vlastním seznamem zkratek, který definuje CCR5 správně jako receptor.

**[VYSOKÁ] G-protein v sekci 7.4 purifikace.** *Prokázaná terminologická chyba*. Text v těsném sousedství uvádí správný „Protein G Sepharose 4 fast flow", což signalizuje jazykovou nepečlivost, ne pojmový omyl.

**[STŘEDNÍ] Astroglykóza místo astroglióza.** *Prokázaná terminologická chyba* (M1, M3).

**[STŘEDNÍ] CD8⁺ T-lymfocyty a „protizánětlivé cytokiny".** *Pravděpodobná nepřesnost*; zasluhuje přeformulování.

### B. Bibliografické vady

**[KRITICKÁ] Čtyři duplicitní páry bibliografických záznamů** se stejným DOI. Nejsnáze viditelná vada pro oponenta.

**[VYSOKÁ] `Apoorva et al. (b.r.)` vs `(Apoorva et al., 2024)`.** Vnitřní nekonzistence. DOI obsahuje rok 2024.

**[STŘEDNÍ] Online-first vs issue-year** nekonzistence u `Wahaab et al.` a dalších — citační režim není sjednocen.

**[STŘEDNÍ] StatPearls (`Sabir & Jan 2026`) jako zdroj pro adaptivní imunitu.** *Legitimní volba slabšího zdroje*, ne chyba existence. Doporučení: nahradit standardní oborovou referencí.

### C. Metodická a statistická rovina

**[VYSOKÁ] Statistické spojení sérií s odlišným promývacím protokolem.** Text změnu charakterizuje jako „drobnou" bez citlivostní analýzy. Přímo ovlivňuje reziduální virové inokulum v intervalu +0. Chybí diskusní pojednání.

**[STŘEDNÍ] Výměna 125 μl média ve 3. a 6. dni.** Diluce není korigována v interpretaci koncentrací — jen M1 a částečně M3 to explicitně diagnostikují.

**[STŘEDNÍ] Poměr `titr/NS1` jako hlavní proměnná Two-way ANOVA.** Analyticky slabší než samostatné modely pro čitatele a jmenovatele; může maskovat biologicky odlišné chování.

**[STŘEDNÍ] Spearmanova korelace při `n = 4`.** Statistická signifikance při této velikosti vzorku prakticky nedosažitelná; ρ ≈ 1,000 u endotelů je artefakt. Autorka to v textu převážně přiznává — nejde o overclaim, ale o slabou vypovídací sílu.

**[VYSOKÁ] Neostré oddělení vlastních dat a dat Mgr. Kotounové.** Potvrzeno všemi třemi syntézami. Autorský přínos musí být ostřeji vymezen napříč metodikou, výsledky i diskuzí.

### D. Jazyk, styl a konzistence

**[VYSOKÁ] Laboratorní slang v metodice.** `dodělané post-hoc testy`, `stáčený na centrifuze`, `Mili Q`.

**[STŘEDNÍ] Překladové kalky a těžkopádné vazby** (např. „Vyloučení interferonů představuje hlavní antivirový mechanismus...").

**[STŘEDNÍ] Stylistická heterogenita.** Uhlazenější anotace a teorie vs syrovější metodika. Konzistentní s deklarovanou AI-korekturou.

**[STŘEDNÍ] Neúplný seznam zkratek.** Chybí `IFNAR1`, `TYK2`, `HMC3`, `HBVP`, `SK-N-SH`, `SN`, `PBS`, `PFU/ml` a další. Některé položky jsou přebytečné. Pouze M3 to diagnostikuje systematicky.

### E. Unikátní nálezy M1

**[STŘEDNÍ] Numerická neshoda `0,56 mg/ml` vs `0,58 μg/ml`** ve standardech NS1. *Ověřený nesoulad v textu; příčina vyžaduje doplnění autorkou* (pravděpodobně zásobní vs pracovní koncentrace, ale text vysvětlení neposkytuje).

**[STŘEDNÍ] Kauzální chyba fagocytóza → vysoké virové titry** v teoretické části. *Pravděpodobná logická chyba* — fagocytóza by titr biologicky snižovala.

### F. Konceptuální rovina

**[STŘEDNÍ] Název vs experimentální záběr.** Název slibuje „protivirovou imunitní odpověď"; experiment měří koncentraci NS1 a virový titr. Autorka si toto napětí uvědomuje a v textu explicitně přiznává:

> „Práce tedy neposuzuje protivirovou imunitní odpověď přímo, ale zaměřuje se na jeden z faktorů, který s ní může přímo souviset."

*Nejde o skrytou chybu*, ale o *rámovací slabinu*, která by měla být ostřeji dotažena v úvodu a závěru.

**[STŘEDNÍ] Přechody DENV/WNV/ZIKV → TBEV.** Analogické přenosy poznatků nejsou vždy explicitně signalizovány jako analogie. Problém argumentační kázně, ne špatné rešerše.

### G. AI a etika

**[NÍZKÁ] AI-signály ve smyslu indikátorů jazykové editace**, ne důkaz AI-generování. Transparentní deklarace použití `ChatGPT` s nástrojem i účelem. Žádný podklad pro silnější závěry.

---

## Top priority fixes

### Kritické — před odevzdáním nutné

1. **[KRITICKÁ]** Opravit `NK-κB` → `NF-κB` v těle textu i v seznamu zkratek. Kontrola všech výskytů.
2. **[KRITICKÁ]** Odstranit čtyři duplicitní páry v bibliografii (`Conde`, `Lindqvist`, `Muller & Young`, `Rastogi`); sjednotit in-text citace bez sufixů `a/b`.
3. **[VYSOKÁ]** Opravit `G-protein` → `Protein G` v celé sekci 7.4 a v in-text odkazech na purifikaci protilátek.
4. **[VYSOKÁ]** Opravit CCR5 formulaci: „chemokiny, zejména CCR5" → „chemokinové receptory, zejména CCR5".
5. **[VYSOKÁ]** Vyřešit `Apoorva et al.` — doplnit rok 2024 do bibliografie, sjednotit s in-text citací.
6. **[VYSOKÁ]** Jednoznačně oddělit vlastní data autorky od dat Mgr. Kotounové v metodice, výsledcích i diskuzi; zavést jasné značení (např. poznámka pod čarou u grafů nebo explicitní věta v úvodu kapitoly 8).
7. **[VYSOKÁ]** Jazyková redakce metodiky a výsledků: odstranit laboratorní slang, pádové chyby, kalky, `Mili Q` → `Milli-Q`, neobratné vazby.
8. **[STŘEDNÍ]** Opravit astroglykóza → astroglióza všude v textu.
9. **[STŘEDNÍ]** Opravit kauzální formulaci „pohlcení viru → vysoké titry" (M1 nález) na biologicky koherentní výklad.
10. **[STŘEDNÍ]** Vysvětlit numerickou neshodu `0,56 mg/ml` vs `0,58 μg/ml` explicitní větou o vztahu zásobní a pracovní koncentrace.
11. **[STŘEDNÍ]** Doplnit explicitní větu do diskuze o statistickém dopadu změny promývacího protokolu (2→4 cykly) napříč replikacemi — alespoň uznat omezení, ideálně provést citlivostní analýzu.
12. **[STŘEDNÍ]** Doplnit explicitní větu o efektu výměny 125 μl média v 3. a 6. dni na interpretaci koncentrací v pozdějších časových bodech.
13. **[STŘEDNÍ]** Revidovat seznam zkratek: doplnit chybějící (`IFNAR1`, `TYK2`, `HMC3`, `HBVP`, `SK-N-SH`, `SN`, `PBS`, `PFU/ml`), odstranit přebytečné (`JAK2` bez výskytu v textu).
14. **[STŘEDNÍ]** Zpřesnit rámování názvu práce v úvodu a závěru — explicitně rozšířit pasáž o tom, že experiment testuje faktor NS1 jako korelát imunitní odpovědi, ne imunitní odpověď přímo.

### Doporučené — zvyšují kvalitu, nejsou blokery

- Revidovat citace online-first publikací podle jednoho sjednoceného pravidla (online-first rok vs issue-year).
- Zvážit nahrazení `StatPearls (Sabir & Jan)` standardní oborovou referencí pro adaptivní imunitu.
- Doplnit alespoň jeden kvantitativní výsledek do abstraktu.
- Explicitně signalizovat, kdy práce přenáší poznatky z DENV/WNV/ZIKV analogicky na TBEV.
- Přehodnotit tematickou relevanci kap. 4.4 (ADE) pro TBEV — buď zúžit, nebo lépe odůvodnit.
- Posílit úvod o problémovou vymezení (gap statement) mezi širokým imunologickým rámcem a užším experimentálním cílem.

### Explicitně nepřebírané úpravy (falešné požadavky z některých externích review)

- ~~Doplnit klíčová slova na bibliografický list.~~ *P5 to nevyžaduje.*
- ~~Doplnit studijní program/obor na titulní list.~~ *P5 to nevyžaduje v podobě citované v některých analýzách.*
- ~~Opravit „anglické věty uprostřed české anotace".~~ *Jde o standardní oddělenou bilingvní anotaci.*
- ~~Zpochybnit existenci `Liang & Dai (2024)`.~~ *Článek reálně existuje, Frontiers in Microbiology, 14. srpna 2024.*
- ~~Označit `Sabir & Jan (2026)` za anachronismus.~~ *NCBI Bookshelf StatPearls 2026 Jan- potvrzuje.*
- ~~Opravit `Fares et al. (2020)` jako „chybějící v bibliografii".~~ *V bibliografii je.*

---

## Rizika pro oponenturu a obhajobu

| Riziko | Pravděpodobnost záchytu | Závažnost | Doporučená obhajobová strategie |
|--------|-------------------------|-----------|----------------------------------|
| NK-κB → NF-κB | **Jistá** (každý s imunologickým zázemím) | Kritická | Opravit před obhajobou, neobhajovat. |
| Duplicitní bibliografie | **Jistá** (pohled na seznam) | Kritická | Opravit. Při dotazu: přiznat chybu exportu z citačního manažeru, ne bagatelizovat. |
| Protein G vs G-protein | Vysoká (biochemik) | Vysoká | Opravit. Při dotazu: jazyková nepečlivost, ne pojmová. |
| CCR5 jako chemokin | Střední–vysoká | Vysoká | Opravit. Vnitřní rozpor se seznamem zkratek je přiznání, že autorka věcně ví — jen v textu zanedbala terminologii. |
| Apoorva (b.r.) vs (2024) | Vysoká | Vysoká | Opravit. |
| Změna promývacího protokolu | Střední (metodolog) | Vysoká | Přiznat jako limitaci; ideálně doplnit citlivostní analýzu nebo stratifikaci. Formulace „drobná změna" je **nebezpečná formulace**, přeformulovat. |
| Neostré oddělení dat s Kotounovou | Střední–vysoká | Vysoká | Přiznat jasně, ostře vymezit vlastní podíl. Transparentnost > defenziva. |
| Poměr titr/NS1 jako hlavní proměnná | Střední (statistik) | Střední | Připravit zdůvodnění: exploratorní analytická volba, nikoli jediná inferenční linka; doplnit oddělené modely pro čitatel a jmenovatel. |
| Spearman ρ=1,000 při n=4 | Střední | Střední | Připravit větu: „Korelace s n = 4 nemají inferenční sílu, slouží jako orientační indikátor monotónního trendu." |
| Numerická neshoda 0,56/0,58 | Nízká–střední (pečlivý čtenář) | Střední | Doplnit do textu explicitní vztah zásobní vs pracovní koncentrace. |
| Diluce výměnou média | Nízká–střední | Střední | Doplnit diskusní pasáž. |
| Astroglykóza → astroglióza | Nízká | Střední | Opravit. |
| Název vs záběr experimentu | Nízká–střední | Střední | Práce to přiznává; při obhajobě explicitně odkázat na pasáž o „korelátu imunitní odpovědi". |
| Kauzální chyba fagocytóza→titr | Nízká | Střední | Přeformulovat. |
| Sabir & Jan jako slabý zdroj | Nízká | Nízká | Případně nahradit, jinak obhájit jako kontextovou referenci. |
| AI-deklarace | Nízká | Nízká | Odkázat na transparentní deklaraci; nástroj + účel uvedeny. |
| Plagiátorství | Nízká (bez similarity reportu nelze dokázat) | Potenciálně kritická | Vedoucí práce musí ověřit Turnitin/iThenticate report před obhajobou. |

**Obhajobová doktrína:** Nejlepší strategie není vady bagatelizovat, ale přesně je přiznat, zasadit do správné váhy a ukázat, že navzdory nim experimentální jádro stojí. Kumulace malých chyb je pro dojem obhajoby horší než jedna velká, přiznaná a správně rámovaná.

---

## Otevřené nejistoty

Po syntéze zůstávají následující body *epistemicky otevřené* — tj. ani po vážení tří metaanalýz nelze rozhodnout s dostatečnou oporou:

1. **Úplnost a kompatibilita finálního PDF s P5** (PDF/A, okraje, Times New Roman 12, řádkování 1,5, podpis, konkrétní datum na prohlášení). Vyžaduje otevření finální odevzdané verze.

2. **Plagiátorství a textová podobnost.** Bez Turnitin/iThenticate nelze rozhodnout. Vedoucí práce by měl report vygenerovat a zkontrolovat parafrázové pasáže teorie proti primárním review článkům.

3. **Systematický bibliografický audit** každé položky seznamu literatury proti autoritativním databázím. Metaanalýzy prošly highlights; zbytek zůstává nekontrolován.

4. **Přesná příčina numerické neshody `0,56 mg/ml` vs `0,58 μg/ml`** — nejpravděpodobnější výklad (zásobní vs pracovní koncentrace) je hypotéza, nikoli ověřený fakt. Vyžaduje potvrzení autorkou.

5. **Systematický vliv změny promývacího protokolu na výsledky.** Bez surových dat replikací 1–2 (2 cykly) vs 3–4 (4 cykly) v intervalu +0 nelze určit, zda se výsledky mezi sériemi systematicky liší.

6. **Rozpor mezi deklarovanými 56 stranami a obsahem končícím na s. 48.** Vysvětlení (přílohy, front matter, seznam literatury) je plausibilní, ale nepotvrzené.

7. **Úplné vymezení rozsahu dat Mgr. Kotounové.** Ani z textu práce, ani z metaanalýz nelze přesně říci, která konkrétní data u kterých buněčných kultur a v jakém rozsahu pocházejí od ní a která vyprodukovala autorka.

8. **Přesná finální podoba prohlášení a jeho soulad s P5.** Textový extrakt ukazuje jen „V Českých Budějovicích, 2026 ……………………"; skutečná odevzdaná podoba s podpisem a datem je neověřitelná.

9. **CD8⁺ a cytokiny — přesná formulace v bp.txt.** M1 ji označuje jako prokázanou nepřesnost, M3 jako zjednodušující tvrzení; přímou citací problematické pasáže by se dalo rozhodnout, ale nebyla explicitně reprodukována.

10. **Zda text obsahuje další skryté terminologické chyby** mimo identifikované (`NK-κB`, `CCR5`, `G-protein`, `astroglykóza`). Kumulativní povaha symptomu naznačuje, že další menší terminologické vady pravděpodobné; systematický sweep by měl být proveden před odevzdáním.
