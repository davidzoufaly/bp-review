# Review bakalářské práce
## „Protivirová imunitní odpověď u flavivirů a její možné úskalí: zaměření na NS1 protein"

- **Autor:** Lucie Novotná
- **Vedoucí:** RNDr. Martin Palus, Ph.D.
- **Konzultant:** Mgr. Václav Hönig, Ph.D.
- **Pracoviště:** Přírodovědecká fakulta JU, ve spolupráci s Parazitologickým ústavem AV ČR (lab. Arbovirologie)
- **Rozsah:** 56 stran (s. 1–48 hlavní text + zkratky a literatura)
- **Rok:** 2026
- **Posuzované zdroje:** `input/bp.txt` (textový extrakt), `input/bp.pdf` (vizuální kontrola), opatření prodekana PřF JU P5 (formální normy), styl Harvard.

---

## Executive summary

Práce splňuje zadání a prokazuje, že studentka samostatně zvládla netriviální experimentální metodiku (optimalizace ELISA, plaková titrace, vícefaktorová statistika nad pěti buněčnými kulturami). Obsahově je kompetentní, výsledková data jsou věrohodná, závěry konzervativní a přiměřené velikosti vzorku (n = 4). Teoretická část kompetentně mapuje literaturu, byť místy klouže k obecné encyklopedické rovině na úkor cíleného kontextu k NS1 a TBEV.

**Hlavní silné stránky:** korektně provedená a poctivě dokumentovaná optimalizační studie ELISA; transparentní popis metodiky; opatrná interpretace statistiky (nezneužívání Spearmanových koeficientů z n = 4); věcné prohlášení o použití generativní AI; slušný rozsah literatury (cca 50 citací, převážně primární a recenzované).

**Hlavní slabiny:** systémové **stylistické nedostatky češtiny** (kalky, neosobní vazby, špatná shoda, neústrojné nominalizace, chybějící čárky u vedlejších vět) — viz kap. 7; **nečistá bibliografie** (duplicitní záznamy se sufixy „a/b", chybný rok „b.r." spárovaný s in-text rokem 2024, anachronická citace s rokem **2026**); **nesrovnalost v rozsahu** (deklarováno 56 stran, dle obsahu hlavní text končí na s. 48); **drobné věcné nepřesnosti** v seznamu zkratek (záměna NK-κB ↔ NF-κB, „MAC" definováno dvakrát s rozdílným označením); **layoutové problémy** (Tab. I se třemi sloupci a čtyřmi řádky pro „cykly" — vizuálně rozpadlá; s. 30 obsahuje 3 řádky textu a zbytek prázdný).

**Celkový dojem:** Práce je věcně připravená k odevzdání; před odevzdáním je nutná **systematická jazyková revize** a **kompletní úklid bibliografie**. Jádro výzkumu obhajobu unese.

---

## Největší rizika

1. **Duplicitní záznamy v bibliografii se sufixy „a/b" a identickým DOI** — `Conde et al. (2017a)` a `(2017b)` se stejným DOI 10.3389/fmicb.2017.00213; analogicky `Lindqvist et al. (2016a/b)`, `Muller & Young (2013a/b)`, `Rastogi et al. (2016a/b)`. To je čistě formální chyba (zřejmě dvojí import do Zotero/Mendeley), ale v Harvardském stylu signalizuje, že autorka má dvě různé práce stejného autorského kolektivu z téhož roku — což zde není pravda. Vyhodnotí to každý oponent. **Závažnost: vysoká.**
2. **Anachronická / nepoužitelná citace** `Sabir, S., & Jan, A. (2026). Physiology, Immune Response. In StatPearls.` — kapitola o adaptivní imunitě se opírá o dosud nevydaný zdroj a navíc o bookshelf-modul StatPearls, což pro bakalářskou práci v oboru imunologie není autoritativní zdroj. **Závažnost: vysoká.**
3. **Citace s `(b.r.)` v seznamu, ale s konkrétním rokem v textu** — `Apoorva, Kumar, A., & Singh, S. K. (b.r.)` v bibliografii vs. „(Apoorva et al., 2024)" v textu (kap. 5.3). Buď doplnit rok, nebo sjednotit. **Závažnost: střední.**
4. **AI-asistence přiznána, ale stylistický otisk zůstal viditelný** — abstrakt a první odstavec diskuze mají charakteristickou „uhlazenou" rytmiku (paralelismy, výčtové trojice, generické spojky), zatímco materiály a metody mají autenticky studentskou syntax. Není to porušení etiky (autorka prohlášení správně doplnila), ale stylová heterogenita je upozornění pro oponenta. **Závažnost: střední.**
5. **Nesrovnalost rozsahu** — bibliografický záznam udává „p. 56", obsah PDF končí číslem 48 (Použitá literatura). Pokud práce dále neobsahuje přílohy, je deklarace v rozporu se skutečností. **Závažnost: střední.**
6. **Statistická omezení nezvýrazněna** — Spearmanovy koeficienty jsou počítány nad 4 časovými body, tj. korelace s n = 4 je interpretačně téměř bezcenná (i ρ = 1,000 u endotelů, kap. 8.2, je artefakt malé n). Diskuze to zmiňuje („by bylo nutné provést další experimenty"), ale neformuluje to dost tvrdě. **Závažnost: střední.**

---

## Top priority fixes

1. **Smazat duplicitní bibliografické záznamy** (Conde, Lindqvist, Muller & Young, Rastogi); sjednotit citaci a in-text odkazy bez sufixů „a/b".
2. **Nahradit / doplnit zdroj `Sabir & Jan (2026)`** — buď reálný rok publikace (StatPearls má rotující update, ověřit aktuální), nebo ho nahradit imunologickou učebnicí (Murphy: Janeway, Abbas: Cellular and Molecular Immunology).
3. **Doplnit rok u Apoorva et al.** v seznamu literatury (Tissue Barriers, 13(3), 2424628 → vyšlo 2024) a sjednotit s in-text odkazem.
4. **Jazyková revize** zaměřená na: (i) shodu přísudku s podmětem rodu středního / nesouladnou kongruenci, (ii) chybějící čárky před „kdy/který/co", (iii) kalky („protokol, který sestavila", „ve výsledku") a anglicismy (viz kap. 7), (iv) sjednocení psaní jednotek se zlomenou mezerou (10⁵ PFU/ml vs. 10⁵ PFU/ml).
5. **Opravit Tab. I** — má 3 datové sloupce, ale 4 řádky; sloupec „Rozmrazovací cykly" obsahuje hodnoty 1, 3, 4, 8, zatímco zbylé sloupce jen tři hodnoty. Vizuálně rozpadlé, čtenář nepozná, co s čím koreluje.
6. **Opravit seznam zkratek** — `NK-κB` má být `NF-κB`; `MAC` je definováno jednou jako „Membrane attack complex", ale v záznamu `C5b-9` je popsáno jako „Membránový atakující komplex (specifická forma — terminální komplex komplementu)". Sjednotit terminologii.
7. **Doplnit čísla stran** k přímým odvolávkám v diskuzi (Palus et al., 2017; Lindqvist et al., 2016) tam, kde se přebírají konkrétní hodnoty.
8. **Vyjasnit deklaraci rozsahu** (56 vs. 48 stran).

---

## 1. Soulad se zadáním a akademickým účelem práce

**Stav:** vyhovující.

Práce splňuje 5 deklarovaných cílů (kap. 6, s. 19): rešerše imunitní odpovědi u flavivirů s důrazem na NS1; optimalizace ELISA; stanovení koncentrace NS1 v supernatantu; stanovení virového titru; vyhodnocení vztahu mezi proměnnými. Autorka navíc explicitně oznamuje omezení: „Práce tedy neposuzuje protivirovou imunitní odpověď přímo, ale zaměřuje se na jeden z faktorů, který s ní může přímo souviset" (Úvod, s. 1). Toto vymezení je akademicky korektní.

**Riziko:** název práce slibuje „protivirovou imunitní odpověď a její možná úskalí", což je rozsáhlejší rámec než to, co experimentální část měří (NS1 produkce v jednotlivých kulturách). Pro obhajobu doporučuji být připravena vysvětlit, proč experimentální část nepokrývá imunitní odpověď přímo.

**Závažnost:** nízká.

---

## 2. Struktura a logika práce

**Stav:** logicky vystavěná, ale s redundantními pasážemi a nepřesnostmi v hierarchii.

**Zjištění:**

- Posloupnost teoretická část → cíle → materiály a metody → výsledky → diskuze → závěr je standardní a srozumitelná.
- **Duplicita 3.1/4.5:** Vrozená imunitní odpověď (kap. 3.1) i Imunomodulační účinky NS1 (kap. 4.5) opakovaně vysvětlují totéž (TLR–IFN–STAT dráhu, role C1q/C4). Doporučuji v kap. 3.1 dráhu představit a v kap. 4.5 jen referovat.
- **Kap. 4.4 (ADE)** je v práci zmíněna, ale nemá vazbu na experimentální část (autorka neměří subneutralizační protilátky ani sekundární infekci). Pro bakalářskou práci je to obhajitelné jako kontext, ale měla by být explicitně označena jako „kontextová".
- Kap. 4.2 (Cytokinová bouře) se odvíjí téměř výhradně z DENV studií — autorka to v závěru kapitoly přiznává („Většina poznatků vychází ze studií infekcí DENV, zatímco u TBEV zůstávají méně objasněné"). Toto přiznání je v pořádku, ale ukazuje, že rešerše opisuje vzorec literatury, místo aby ho rekonstruovala kolem TBEV (jádro práce).
- **Číslování:** kap. 6 „Cíle práce" obsahuje očíslovaný seznam (1.–5.), ale ostatní úrovně používají decimální systém (2.1, 4.5). Funkčně OK, vizuálně nesourodé.

**Závažnost:** střední — strukturální čistění by zvýšilo kvalitu rešeršní části.

---

## 3. Formální náležitosti a soulad s fakultními pokyny (P5)

**Stav:** většinově v souladu, několik nesrovnalostí.

**Zjištění proti P5 (opatření prodekana PřF JU):**

- **Titulní list (s. I, viz PDF s. 1):** Obsahuje JU, fakultu, název, „Bakalářská práce", autora, vedoucího, konzultanta, místo, rok. Chybí explicitní uvedení **studijního programu / oboru**, který vzor P3a požaduje (P5, bod 4.2). **Závažnost: střední** — snadno opravitelné.
- **List s bibliografickými údaji (PDF s. 2):** Citace je v pořádku, anglický překlad názvu uveden. Anotace je přítomna v češtině i angličtině. Chybí ale **klíčová slova** v obou jazycích, která doporučení P5 očekává (a oponenti je často vyžadují). **Závažnost: střední.**
- **Prohlášení o samostatnosti + AI:** Korektní, věcně formulované, splňuje aktuální požadavky na deklaraci použití generativní AI. **Bez výhrad.**
- **Sazba:** Times New Roman 12, řádkování 1,5, zarovnání do bloku — vizuálně sedí (P5 bod 4.1).
- **Číslování stran:** Arabské číslice začínají na s. 1 u Úvodu (viz PDF s. 11). Korektní vůči P5 4.6.
- **Deklarace rozsahu „p. 56":** Text končí na s. 48 (Použitá literatura), bez příloh. Pokud bibliografie + závěrečné prázdné strany dorovnávají na 56, uvést to v bibliografickém záznamu (např. „p. 56 + appendices"). Nyní působí nekonzistentně.
- **Anglický překlad názvu:** „Antiviral immune response in flaviviruses and its potential pitfalls: focus on the NS1 protein" — gramaticky OK, ale „pitfalls" je hovorovější než český „úskalí" v akademickém kontextu; alternativa „limitations" / „caveats" by byla přesnější. **Závažnost: nízká.**

---

## 4. Citační styl a bibliografie

**Stav:** styl je v zásadě Harvardský (autor, rok), ale **bibliografický seznam je nečistý**.

**Konkrétní zjištění:**

- **Formálně Harvardský zápis in-text** je dodržen: `(Best, 2016)`, `(Liang & Dai, 2024)`, `(Pierson & Diamond, 2020)`, `(Y. Pan et al., 2022)`. Použití iniciály před příjmením u Pan a P. Pan je správné (rozlišení dvou autorů Pan).
- **Duplicity** — viz Největší rizika (Conde, Lindqvist, Muller & Young, Rastogi). Tyto záznamy mají identický DOI, jsou to nedopatření exportu z reference manageru, nikoli skutečné duplicitní zdroje. V Harvardu nemají sufixy „a/b" co dělat, pokud autoři skutečně nepublikovali ve stejném roce dvě různé práce.
- **`Sabir, S., & Jan, A. (2026)`** — anachronismus. StatPearls navíc není prvotřídní zdroj pro adaptivní imunitu; lépe je odkázat na recenzovanou monografii.
- **`Apoorva, Kumar, A., & Singh, S. K. (b.r.)`** v seznamu, ale `(Apoorva et al., 2024)` v textu — chybí rok v bibliografii (Tissue Barriers, 13(3), 2424628, 2024).
- **Bibliografický styl Harvardu** podle uvedeného vzoru `(Liang & Dai, 2024)`: APA-7-podobný formát s DOI je v seznamu literatury akceptovatelný, ale měl by být použit konzistentně. V seznamu se občas objeví formát se závorkou pro vydání („Vaccines — the Key Paradigm…"), jindy ne. Tyto vnořené informace o speciálních číslech časopisu (např. `Vaccine, Vaccines - the Key Paradigm for the 21st Century's Health Care Strategy, 30(29), 4301–4306` u Heinz & Stiasny, 2012; podobně u Bogovic et al., 2010 a Beutler, 2004) jsou redundantní a zhoršují čitelnost — Harvardský styl je standardně neuvádí. **Závažnost: nízká, ale plošná.**
- **Ahead-of-print:** `Glasner et al. (2018)` má v záznamu `Annual Review of Virology, 5(Volume 5, 2018), 227–253` — duplicitní označení svazku je artefakt automatického exportu, opravit na `5, 227–253`.
- **Křestní jména a iniciály:** `de Madrid, A. T., & Porterfield, J. S. (1969)` má korektní formát; `Lin, A. V. (2015)` rovněž. Konzistentní.
- **In-text bez interpunkce v některých případech:** `(Aberle et al., 2018).. Po rozpoznání` (s. 7, kap. 3.2) — dvojtečka u Aberle je chyba (dvě tečky za sebou).

**Závažnost celku:** vysoká — toto je první oblast, kterou bude oponent kontrolovat.

---

## 5. Práce se zdroji

**Stav:** zdroje jsou převážně relevantní, primární a recenzované.

**Zjištění:**

- Autorka kombinuje **revue články** (Pierson & Diamond, 2020; Mukhopadhyay et al., 2005; Muller & Young, 2013; Rastogi et al., 2016) jako rámec a **primární experimentální práce** (Růžek et al., 2009, 2011; Palus et al., 2017; Fares et al., 2020; Tavčar Verdev et al., 2022) pro konkrétní tvrzení. Tato vrstvená strategie je správná.
- **Chybí kritičtější použití zdrojů.** Většina pasáží je „X popsal Y". Téměř nikde není konfrontace dvou studií se sporným výsledkem (např. proinfikovanost astrocytů 14 % u Fares et al., 2020 vs. 37 % u Tavčar Verdev et al., 2022 — tato diskrepance v diskuzi (s. 41) je zaznamenána, ale ne vysvětlena).
- **Self-replication zdrojů:** `Palus et al., 2017` a `Růžek et al., 2009` jsou domácí (Parazitologický ústav AV ČR) — to je legitimní (laboratoř autorky), ale měla by být v diskuzi přiznána určitá blízkost ke školícímu pracovišti.
- **Stáří zdrojů:** několik klíčových revue je z let 2013–2017 (Muller & Young, 2013; Rastogi et al., 2016; Conde et al., 2017). Pro NS1 to není diskvalifikující (jádro znalostí stabilní), ale kdekoli je k dispozici novější komprehensivní revue (Perera et al., 2024 — to autorka cituje), měla by se preferovat.

**Závažnost:** nízká až střední.

---

## 6. Plagiátorství, podobnost a AI-signály

**Stav:** žádné indicie přímého plagiátu, **ale stylistické indikátory AI-asistence jsou patrné** (autorka to ostatně přiznává v prohlášení).

**Indikátory podezření na AI-leštění (nikoli vlastní generování):**

- **Abstrakt v češtině** (s. 33–57 původního txt extraktu, s. II PDF) — paralelní výčtové trojice („mírných příznaků až po hemoragické horečky a úmrtí"), generická prohlášení („velmi komplexní"), absence konkrétních čísel — toto je typická signatura LLM jazykové úpravy.
- **Úvod prvního odstavce diskuze** (s. 40): „V první části diskuze bych se ráda zaměřila na samotnou optimalizaci metody ELISA." — tato meta-narativní konstrukce („v první části bych se ráda…") je neobvyklá pro vědecký text, kde jsou přechody implicitní; LLM ji typicky vkládá.
- **Naopak materiály a metody** (kap. 7) působí autenticky — věty mají variabilní délku, drobné syntaktické chyby, odborný žargon (`harvestovaný SN`, `přefiltrován přes filtr`), což je studentský styl. Stejně diskuze na s. 41–42 (proinfikovanost astrocytů) má znaky autorského myšlení.

**Verdikt:** **Není zjevný plagiát.** Autorka splnila etické prohlášení o použití AI. Stylistická heterogenita ale signalizuje, že úpravy AI byly aplikovány nerovnoměrně. Doporučuji manuálně přepsat abstrakt a první odstavce kapitol tak, aby byly v souladu se zbytkem práce.

**Závažnost:** střední (etika OK, formálně řešitelné).

---

## 7. Jazyková a stylistická kvalita

**Stav:** **systémové problémy.** Tato kategorie je největším těžištěm review. Text obsahuje opakující se typy chyb — uvádím reprezentativní vzorek.

### 7.1 Shoda podmětu s přísudkem / kongruence

**Příklad 1 (s. 1, Úvod):**
- **Původní:** „Tato práce proto v teoretické části shrnuje současné poznatky o protivirové imunitní odpovědi u flavivirů se zaměřením na NS1 protein."
- **Problém:** kostrbatá vazba „se zaměřením na", která je administrativní šablona; lépe substantivně.
- **Návrh:** „Teoretická část práce shrnuje současné poznatky o protivirové imunitní odpovědi u flavivirů s důrazem na NS1 protein."
- **Vysvětlení:** odstraňuje redundantní „proto", ruší metanarativní „tato práce" a nahrazuje frázové „se zaměřením na" konkrétnějším „s důrazem na".
- **Závažnost:** nízká, ale opakující se vzorec.

**Příklad 2 (s. 5, kap. 3):**
- **Původní:** „V kontextu TBEV infekce je důležité zdůraznit, že imunitní odpověď probíhá nejen v periferních tkáních, ale i v prostředí CNS, kde se na ní podílejí buňky neurovaskulární jednotky (Mustafá et al., 2019)."
- **Problém:** „V kontextu TBEV infekce" je kalk z anglického „in the context of TBEV infection"; čeština preferuje „U infekce TBEV" nebo „V případě infekce TBEV".
- **Návrh:** „U infekce TBEV je nutné zdůraznit, že imunitní odpověď probíhá nejen v periferních tkáních, ale i v CNS, kde se na ní podílejí buňky neurovaskulární jednotky (Mustafá et al., 2019)."
- **Vysvětlení:** ruší kalk, „je důležité zdůraznit" je v odborném textu výplň → „je nutné" je přesnější.
- **Závažnost:** střední (anglicismus).

**Příklad 3 (s. 7, kap. 3.2):**
- **Původní:** „Po rozpoznání antigenu začínají CD4⁺ T-lymfocyty produkovat určité cytokiny, což vede ke stimulaci B-lymfocytů a zároveň k podpoře CD8⁺ T-lymfocytů, cytotoxických T-lymfocytů (Aberle et al., 2018).."
- **Problémy:** (a) „určité cytokiny" je vágní (které?); (b) dvě tečky na konci věty — typografická chyba; (c) přístavek „cytotoxických T-lymfocytů" je redundantní (CD8⁺ T-lymfocyty = cytotoxické T-lymfocyty, není třeba glosovat dvakrát).
- **Návrh:** „Po rozpoznání antigenu začínají CD4⁺ T-lymfocyty produkovat cytokiny (zejména IL-2, IFN-γ), což vede ke stimulaci B-lymfocytů a k aktivaci cytotoxických CD8⁺ T-lymfocytů (Aberle et al., 2018)."
- **Vysvětlení:** specifikuje cytokiny, opravuje interpunkci, integruje přístavek do přívlastku.
- **Závažnost:** vysoká (vágnost + interpunkce).

### 7.2 Trpný rod a neosobní vazby (nadužívání)

**Příklad 4 (s. 20, kap. 7.1):**
- **Původní:** „Obě buněčné kultury byly uchovávány v tekutém dusíku při teplotě – 196 °C. HA byly zakoupeny od ScienCell (katalogové číslo: #1801) a po oživení kultivovány v médiu AM + 2 % FBS + AGS + P/S."
- **Problém:** Trpný rod je v metodice akceptovatelný, ale **mezera ve znaménku „– 196 °C"** je chyba (má být `−196 °C` bez mezery, případně `–196 °C`); navíc znaménko mínus zde má být U+2212 (`−`), ne pomlčka U+2013 (`–`).
- **Návrh:** „Obě buněčné kultury byly uchovávány v tekutém dusíku při teplotě −196 °C."
- **Vysvětlení:** typografické pravidlo — záporné teploty se píší se znaménkem mínus těsně před číslicí.
- **Závažnost:** střední (opakuje se: „v – 80 °C" na s. 20, „−80 °C" je správně).

### 7.3 Hovorové výrazy v odborném textu

**Příklad 5 (s. 42, Diskuze):**
- **Původní:** „Rychlé a efektivní pohlcení viru může mít za následek vysoké virové titry v prvním dni po infekci."
- **Problém:** Sémantická nepřesnost — „pohlcení" mikrogliemi by mělo virus eliminovat, ne zvyšovat virový titr. Pokud autorka myslí, že fagocytovaný virus uvnitř mikroglie přispívá k titru měřenému v supernatantu, jde o chybnou kauzální logiku.
- **Návrh:** „Vysoký virový titr v supernatantu mikroglií 1. den po infekci může odrážet rychlou virovou replikaci v aktivovaných buňkách, případně uvolnění virionů z fagocytovaných infikovaných buněk; samotná fagocytóza by titr v supernatantu spíše snižovala."
- **Vysvětlení:** rektifikuje kauzální vztah — fagocytóza není zdrojem volných virionů.
- **Závažnost:** vysoká (potenciální obsahová chyba, nikoli jen styl).

### 7.4 Pleonasmy a nominalizace

**Příklad 6 (s. 23, kap. 7.5):**
- **Původní:** „Promývací roztok, používaný několikrát mezi jednotlivými reagenciemi byl připraven z PBS a 20% Tween, používaný jako detergent snižující nespecifické vazby v koncentraci 0,05 %."
- **Problémy:** (a) chybí čárka před „byl připraven" (vedlejší věta); (b) opakování „používaný" v jedné větě (pleonasmus); (c) nejasné, co je v koncentraci 0,05 % — Tween 20 nebo celý promývací roztok.
- **Návrh:** „Promývací roztok byl připraven z PBS s 0,05 % Tween 20, který slouží jako detergent snižující nespecifické vazby."
- **Vysvětlení:** ruší redundanci, opravuje interpunkci, jednoznačně přiřazuje koncentraci k Tween 20.
- **Závažnost:** střední (opakující se vzorec — viz kap. 7.4 původní text obsahuje analogicky kostrbaté formulace).

### 7.5 Chybějící čárky před vedlejšími větami

**Příklad 7 (s. 9, kap. 4.1):**
- **Původní:** „Mechanismy patogeneze mohou být také komponenty, které jsou zprostředkované složkami imunitního systému."
- **Problém:** Sémantická chyba — věta tvrdí, že mechanismy „jsou komponenty", což je nelogické (mechanismy jsou procesy, ne komponenty). Patrně myšleno: patogenezi mohou způsobovat samotné složky imunitního systému.
- **Návrh:** „Patogenezi mohou způsobovat i samotné složky imunitního systému, nikoli pouze přímý cytopatický efekt viru."
- **Vysvětlení:** věcně přesněji formuluje paradox imunopatogeneze.
- **Závažnost:** vysoká (sémantika, ne jen styl).

### 7.6 Anglicismy / kalky

**Příklad 8 (s. 30, kap. 8.1):**
- **Původní:** „Metoda byla optimalizována na základě pilotních experimentů, kdy výsledná koncentrace neodpovídala teoretickým koncentracím vzorků, předem změřených na Nanodropu."
- **Problém:** „kdy" zde funguje jako anglické „where/in which" (časové „kdy" se v češtině váže k času, ne k podmínce); v češtině preferujeme „při nichž" / „u nichž" / „protože".
- **Návrh:** „Metoda byla optimalizována na základě pilotních experimentů, ve kterých výsledná koncentrace neodpovídala teoretickým koncentracím vzorků předem změřených na Nanodropu."
- **Vysvětlení:** „ve kterých" je gramaticky správný vztažný odkaz na „experimentech"; navíc lze odebrat čárku za „vzorků" (přívlastek je shodný a krátký).
- **Závažnost:** střední (systémový vzorec — `kdy` ve významu `ve kterém` se v textu opakuje desítky krát).

### 7.7 Vágní formulace

**Příklad 9 (s. 9, kap. 4.1):**
- **Původní:** „Avšak hranice mezi obranou systému a imunopatogenezí je tenká."
- **Problém:** Klišé. „Hranice je tenká" je publicistická metafora, v odborném textu nevhodná.
- **Návrh:** „Hranice mezi efektivní obranou a imunopatologickým poškozením tkáně není ostrá; identické mediátory (IFN-I, IL-1, TNF-α) působí v určitých koncentracích ochranně a v jiných destrukčně."
- **Vysvětlení:** nahrazuje metaforu konkrétním biologickým mechanismem.
- **Závažnost:** střední.

### 7.8 Systémové vzorce — souhrn

| Typ chyby | Frekvence | Příklad |
|---|---|---|
| Trpný rod / neosobní vazby (v metodice OK, jinde nadužívané) | velmi vysoká | „byl připraven", „byly stanoveny" v rešerši |
| Anglické „kdy" místo „ve kterém" | velmi vysoká | viz Příklad 8 |
| Chybějící čárky u vedlejších vět | vysoká | Příklady 4, 6 |
| Pleonasmy (`používaný … používaný`, `velice široké škále`) | střední | s. 4: „velice široké škále" |
| Nedotažený slovosled | střední | s. 7: „Po počáteční produkci IgM začínají B-lymfocyty produkovat IgG protilátky" — slovosled v pořádku, ale opakování „protilátky/IgM/IgG" v jedné větě je redundantní |
| Typografie záporné teploty `– 80 °C` | systematicky | celý kap. 7 |
| Klišé / publicistické metafory | nízká | „hranice je tenká" |

**Závažnost kategorie celkem:** **vysoká.** Nutná systematická revize češtiny rodilým mluvčím s redaktorskou zkušeností (ne jen automatický spell-check).

---

## 8. Terminologie a konzistence

**Stav:** v zásadě konzistentní, několik rušivých nesrovnalostí.

**Zjištění:**

- **NF-κB vs. NK-κB**: V seznamu zkratek (s. 45) je `NK-κB	Nuclear factor kappa B`. To je překlep — správně je `NF-κB`. V textu kap. 4.5 (s. 13) je správně `NF-κB`. **Sjednotit na NF-κB všude.** (Závažnost: vysoká — viditelná v seznamu zkratek.)
- **MAC** je v seznamu zkratek (s. 47): `MAC	Membrane attack complex (membránový atakující komplex)`. Současně `C5b-9` je popsáno jako „Membránový atakující komplex (specifická forma — terminální komplex komplementu)". Tyto dvě definice se překrývají. Sjednotit (MAC = C5b-9 v dospělé formě).
- **TBEV vs. TBEV Neu:** První je virus, druhý je konkrétní kmen (Neudoerfl). V práci se používají oba, většinou správně, ale např. na s. 33 (popisek Obr. 13) je „infekce u astrocytů" bez specifikace kmene — měl by být `TBEV Neu` všude konzistentně tam, kde se odkazuje na konkrétní experiment.
- **„nestrukturní" vs. „nestrukturální":** seznam zkratek používá `Nestrukturní protein 1` (NS1), text používá obojí (`nestrukturálních proteinů` na s. 1, `nestrukturní protein` na s. 14). Doporučuji sjednotit na **nestrukturální** (převažující v anglické literatuře non-structural).
- **„96ti jamkové panely":** typograficky chybný zápis (s. 24, 28). Buď `96jamkové panely` nebo `96-ti jamkové` (nedoporučováno) → preferovaný tvar je `96jamkové`. Vyskytuje se opakovaně.
- **µ vs. μ:** v textu se střídají dvě různé znaky (mikro): `μl` vs. `µl`. Vizuálně téměř identické, ale jiná Unicode (`U+03BC` vs. `U+00B5`). Sjednotit.
- **Velikosti písmen u virů:** `dengue virus (DENV)` (s. 2) vs. `virus dengue (DENV)` (s. 1) — sjednotit slovosled.

**Závažnost:** střední.

---

## 9. Argumentace a analytická úroveň

**Stav:** v rešeršní části deskriptivní, v experimentální části přiměřeně kritická.

**Zjištění:**

- **Diskuze (kap. 9, s. 40–43)** je jádrem analytické práce. Obsahuje kvalitní pasáže, kde autorka konfrontuje vlastní data s literaturou:
  > „Tyto hodnoty jsou v podobném řádu jako údaje publikované v literatuře, kde titry dosahovaly 10⁵ – 10⁶ PFU/ml již druhý den po infekci, a to i při nízké proinfikovanosti buněk (Palus et al., 2017)." (s. 41)

  Toto je správný akademický pohyb (porovnání s publikovanou referencí).

- **Argumentační slabina:** Spearmanova korelace s n = 4 je interpretačně velmi limitovaná. Autorka koeficient ρ = 1,000 u endotelů (kap. 8.2) prezentuje jako fakt, ale neříká, že při n = 4 znamená ρ = 1,000 jen monotónní vztah napříč 4 body, což je triviálně náhodný výsledek. Doporučuji v diskuzi explicitně přiznat: „Vzhledem k n = 4 nelze žádnou Spearmanovu korelaci interpretovat jako důkaz vztahu, slouží pouze jako orientační indikátor monotónního trendu."

- **Two-way ANOVA:** statisticky relevantnější, korektně použitá. Šídákův post-hoc test je správná volba pro vícenásobné porovnání.

- **Vágní kauzalita:** „Tento rozdíl by mohl souviset s proinfikovaností buněk" (s. 41) — autorka spekuluje, ale neměří proinfikovanost ve vlastních vzorcích. Pro diskuzi je to legitimní hypotéza, ale měla by být označena jako „je třeba ověřit imunofluorescencí v dalších experimentech".

**Závažnost:** střední — analytický základ je pevný, jen nedotažený v některých formulacích.

---

## 10. Fact-checking a věcná správnost

**Stav:** většinou správné; několik nepřesností a jedno potenciální zjednodušení.

**Ověřená tvrzení:**

- TBEV genom ~11 kb, jednovláknová RNA s pozitivní polaritou, jediný ORF kódující polyprotein, 3 strukturální + 7 nestrukturálních proteinů (s. 2) — **správně.**
- NS1 ~352 aminokyselin, 46–55 kDa, glykosylovaný (Asn207, Asn310) (s. 15, 16) — **správně.**
- TBEV Neudoerfl izolován v Rakousku 1971 z *Ixodes ricinus* (s. 20) — **správně** (Mandl et al., 1997).
- 70 % infekcí evropským subtypem TBEV asymptomatických (s. 4) — **správně** (epidemiologický konsenzus).

**Pravděpodobné nepřesnosti / ke zvážení:**

- **„C5b-9 = membránový atakující komplex":** technicky terminální komplement complex (TCC) v membránové formě. Označení MAC se užívá zaměnitelně s C5b-9, ale v seznamu zkratek je `C5b-9	Membránový atakující komplex (specifická forma — terminální komplex komplementu)` — to je kruhová definice. **Pravděpodobný problém.**
- **„Genom flavivirů kóduje jeden otevřený čtecí rámec, tudíž výsledkem je syntéza nových virových proteinů, konkrétně jednoho dlouhého polyproteinu" (s. 2):** logická vazba „tudíž" je nesprávně použitá — z toho, že genom má jeden ORF, nevyplývá produkce polyproteinu jako důsledek, ale jako definiční vlastnost ORF (jeden ORF = jeden translaát = jeden polyprotein). Lepší formulace: „Genom kóduje jediný ORF, jehož translací vzniká jeden polyprotein, který je následně štěpen na strukturální a nestrukturální proteiny."
- **„Asn207 pro transport NS1 proteinu ven z infikované buňky" (s. 15):** glykosylační místa Asn207 a Asn310 jsou popsána konzistentně s literaturou, ale role konkrétního Asn pro sekreci je flavivirus-specifická a v literatuře se údaje liší (DENV vs. WNV vs. TBEV). Pro bakalářskou práci akceptovatelné, ale lépe formulovat: „U DENV bylo prokázáno, že glykosylace Asn207 je důležitá pro sekreci…"
- **„Typ I interferonová odpověď, čímž se zvýší exprese interferon-stimulačních genů, což omezuje šíření viru" (s. 41):** mírná nadinterpretace v kontextu astrocytů — IFN-I sice indukuje ISG, ale schopnost omezit TBEV replikaci v astrocytech je popisována nekonzistentně. Lindqvist et al. (2016) ukazují rychlou IFN-I odpověď, ale samotná blokace replikace je menší než v jiných buněčných typech.

**Míra jistoty fact-checkingu:** střední (nelze ověřit každou primární referenci, ale konzistence s recenzovanými revue je dobrá).

**Závažnost:** nízká — žádné fundamentální chyby, jen nuance.

---

## 11. Metodologie

**Stav:** **silná stránka práce.** Materiály a metody (kap. 7, s. 20–29) jsou pečlivě popsány, většina experimentů by byla reprodukovatelná.

**Zjištění:**

- **Optimalizace ELISA (kap. 7.6, s. 25–27):** Tabulka II uvádí 16 kombinací parametrů, Tabulka III výsledné koncentrace — to je seriózní optimalizační studie, která je plně reprodukovatelná. Použití Grubbsova testu pro výjimky a koeficientu determinace pro porovnání standardních křivek je metodicky korektní.
- **Plaková titrace (kap. 7.7):** popsáno standardně, zdroj metody (de Madrid & Porterfield, 1969) korektně citován.
- **Statistická analýza (kap. 7.8):** Spearmanův test, Two-way ANOVA + Šídákův post-hoc test — odpovídá charakteru dat. SEM = SD/√n s n = 4 je správně. **Slabina:** test normality není zmíněn (Shapiro-Wilk, D'Agostino-Pearson). Při n = 4 je test normality stejně bezcenný, ale je dobré to zdůvodnit.
- **Promývání kultur:** Kap. 7.3 přiznává, že počet promývacích cyklů byl navýšen z 2 na 4 v 3.–4. experimentu. Statistická analýza pak v kap. 7.8 deklaruje: „Statistická analýza zahrnovala všechny biologické replikace, a to i přes drobnou změnu v počtu promývacích cyklů napříč experimenty." Toto je metodologicky **diskutabilní** — pokud změna promývání ovlivnila reziduální virovou kontaminaci v intervalu +0, mohla ovlivnit i pozdější časové body. Autorka by měla v diskuzi explicitně analyzovat, zda byl systematický rozdíl mezi prvními dvěma a posledními dvěma replikacemi, a doložit, že není.
- **MOI = 5** (kap. 7.3) — vysoké MOI, vhodné pro synchronní infekci, ale ne pro modelování přirozené infekce. Pro účely této studie OK, ale pro obhajobu se připravit na otázku.
- **Kontroly:** Negativní kontroly (buňky bez infekce) jsou zmíněny (kap. 7.3), ale ne explicitně co se s nimi měřilo a jak vypadají v ELISA grafech (chybějící bar v Obr. 13?). Doporučuji v textu výsledků zmínit, že negativní kontroly měly NS1 koncentraci pod detekčním limitem (pokud je tomu tak).

**Závažnost:** nízká až střední (silná oblast s drobnými nedostatky).

---

## 12. Kvalita abstraktu, úvodu a závěru

**Stav:** funkční, ale stylisticky heterogenní (viz kap. 6 — AI-signály).

**Abstrakt (s. II):**
- Český i anglický verze pokrývají kontext, motivaci, materiál, metody, výsledky. Anglická verze je gramaticky čistá.
- **Slabiny:** chybějí konkrétní výsledky (např. „NS1 produkce u astrocytů 150–200 ng/ml, u endotelů ~10 ng/ml") — abstrakt by měl obsahovat alespoň jeden kvantitativní výsledek. Stávající abstrakt je čistě deskriptivní bez čísel.
- **Chybějí klíčová slova** (viz kap. 3 — formální požadavek).

**Úvod (kap. 1, s. 1):**
- Stručný (jeden odstavec), motivační, končí explicitním vymezením rozsahu práce. Korektní.
- Postrádá strukturu „co je v této práci v jakých kapitolách" (klasický „road map" odstavec). Pro bakalářskou práci to není povinné, ale pomáhá čtenáři.

**Závěr (kap. 10, s. 44):**
- 5 odrážek, jasných, podložených daty z výsledků. **Bez výhrad k obsahu.**
- Stylisticky: „Astrocyty mají vyšší produkční aktivitu NS1 proteinu" — „produkční aktivita" je nešikovné, lépe „produkují více NS1 proteinu" nebo „mají vyšší expresi/sekreci NS1".
- Závěr neobsahuje „outlook" (co dál) — to je v diskuzi (s. 43), ale formálně by mělo být i v závěru.

**Závažnost:** nízká.

---

## 13. Závěry a jejich opora v textu

**Stav:** závěry jsou **konzervativní a věrně odráží data.** Toto je silná stránka.

**Zjištění:**

- **Závěr 1** (optimalizace ELISA) — jasně podložený daty z kap. 8.1.
- **Závěr 2** (astrocyty > endotely v produkci NS1) — konzistentní s Obr. 13 (150–200 ng/ml vs. ~10 ng/ml).
- **Závěr 3** (endotely stabilní titr, astrocyty klesající) — vizuálně podloženo Obr. 14, statisticky neprokázáno (autorka to korektně neříká jako „statisticky významný").
- **Závěr 4** („Nebyl prokázaný vztah mezi NS1 a virovým titrem") — formálně správné. Spearmanův koeficient u astrocytů je −0,400 a u endotelů 1,000 (kap. 8.2), což autorka interpretuje opatrně. Korektní.
- **Závěr 5** (různé buněčné linie mají různou sekreci NS1 a virové titry) — podloženo Two-way ANOVA s p < 0,0001 (Obr. 17, 19, 20). Robustní.

**Slabina:** závěry by mohly být explicitnější o **velikosti efektu** a **klinické relevanci**. Např. „150–200 ng/ml NS1 u astrocytů odpovídá řádově hladinám popisovaným v séru pacientů s těžkým průběhem DENV (200–600 ng/ml; Paranavitane et al., 2014), což naznačuje, že in vitro produkce dosahuje fyziologicky relevantních koncentrací." — to by zvýšilo dopad závěrů.

**Závažnost:** nízká.

---

## 14. Formální prvky (obrázky, tabulky, popisky, přílohy)

**Stav:** kvalita obrázků je solidní, ale **několik problémů s tabulkami a layoutem.**

### 14.1 Obrázky

- **Obr. 1, 2, 3, 4, 5, 7, 9, 10:** Schémata BioRender / upraveno z literatury. Vizuálně OK. **Citace zdroje** je u každého obrázku uvedena („upraveno dle X" / „zdroj: vlastní, BioRender") — **správně.**
- **Obr. 6 (NS1 dimer/hexamer):** zdroj „vlastní, BioRender" — popis dimeru a hexameru s β-roll, β-ladder, wing doménami je korektní.
- **Obr. 8 (schéma experimentu):** „zdroj: vlastní, BioRender" — popisek je konzistentní s textem.
- **Obr. 11 (16 standardních křivek, panely A–G):** **drobný problém s rozlišením** — texty v legendách jsou velmi malé (PDF s. 31), na tisku by byly nečitelné. Doporučuji zvětšit písmo v grafech nebo dát víc panelů na samostatnou stránku.
- **Obr. 13, 14, 15, 16, 17, 18, 19, 20:** GraphPad Prism výstupy, statisticky korektně označené hvězdičkami. Konzistentní vizuální styl. **Bez výhrad.**
- **Popisky obrázků** mají jednotný styl (`Obr. X: Popis. (zdroj/data jsou prezentována jako…)`) — **konzistentní.**

### 14.2 Tabulky

- **Tab. I (s. 26):** **vážný problém s formátem.** Tabulka má 3 sloupce datového obsahu (Koncentrace, Objem, Cykly), ale 4 řádky. Třetí sloupec má hodnoty 1, 3, 4, 8, zatímco první dva sloupce jen 3 hodnoty (28/5,6/0,56 µg/ml a 10/20/50 µl). Vizuálně tabulka „uplakaná", čtenář nepochopí, že to není matice 3×3, ale výčet možných hodnot pro každý parametr. **Doporučuji** přepsat na 3 odrážky („Koncentrace: 28/5,6/0,56 µg/ml; objem: 10/20/50 µl; cykly: 1/3/4/8") nebo udělat tabulku se sjednoceným počtem řádků a explicitním nadpisem „Možné hodnoty parametrů".
- **Tab. II (s. 27):** 16 řádků kombinací — **OK formátově**, ale tabulka je dlouhá a redundantní s pozdějším Obr. 11. Mohla by být zkrácena (např. uvést jen kombinace, které byly statisticky odlišné).
- **Tab. III (s. 32):** popisek `Tab. III.:` má dvojtečku po čísle, zatímco Tab. I a II mají `Tab. I:` a `Tab. II:` — **inkonzistence v interpunkci.**
- Popis pod tabulkou Tab. III: „Z tabulky III jsou vypočítané koncentrace jednotlivých testovacích standardů." — **gramatická chyba.** Mělo by být „V tabulce III jsou uvedeny vypočítané koncentrace…" nebo „Tabulka III obsahuje vypočítané koncentrace…".

### 14.3 Layout

- **s. 30 (PDF):** kapitola 8.1 začíná, ale obsahuje jen 3 řádky textu, zbytek stránky je prázdný (následuje Obr. 11 na s. 31). Toto je špatný zlom — buď přesunout obrázek na s. 30, nebo přesunout úvodní text k obrázku.
- **s. 1 a další:** odsazení prvního řádku odstavce je nekonzistentní — některé odstavce mají odrážku 3 mezery, jiné nemají. Vizuálně rušivé (viz s. 1 Úvod, srovnání s. 4 Klinické projevy).

**Závažnost:** střední (Tab. I je nutné opravit, ostatní je kosmetika).

---

## 15. Vnitřní konzistence napříč dokumentem

**Stav:** většinou konzistentní; několik drobných rozporů.

**Zjištění:**

- **NS1 koncentrace v abstraktu vs. výsledcích:** Abstrakt neuvádí konkrétní hodnoty, takže rozpor není možný — viz ale kap. 12 (chybí kvantita).
- **Promývání:** kap. 7.3 (s. 21) říká „2 promývání" v experimentech 1–2 a „4 promývání" v 3–4; kap. 7.8 (s. 28) toto akceptuje ve společné statistice. Vnitřně konzistentní, ale metodologicky diskutabilní (viz kap. 11).
- **MOI = 5 (kap. 7.3) vs. žádná zmínka o MOI v diskuzi** — autorka v diskuzi mluví o „proinfikovanosti", ale neuvádí, že její vlastní MOI = 5 je vyšší než většina referencí v diskuzi (Fares et al., 2020 používá MOI = 0,1–1). **Drobná inkonzistence v interpretačním rámci.**
- **„Standard 0,58 μg/ml" (s. 40, Diskuze) vs. „0,56 mg/ml" (s. 27, Materiály):** Nesoulad — buď 0,56 mg/ml = 560 μg/ml, nebo 0,58 μg/ml. **Velký řádový rozdíl.** Jedná se o standard NS1 — pokud zásobní alikvot byl 0,56 mg/ml, finální používaný standard po naředění je v rozsahu nižších koncentrací. Diskuze říká „uchovávány jsou v koncentraci 0,58 μg/ml v alikvotech po 55 μl", ale Materiály říkají „zásobního alikvotu standardu NS1 o koncentraci 0,56 mg/ml". **Nutno vysvětlit, zda jde o zásobní vs. ředěný alikvot, nebo o numerickou nepřesnost.**
- **Cíle vs. závěry:** Cíl 5 (vztah mezi NS1, virovým titrem, časem, typem buňky) je v závěru explicitně řešen jako „nebyl prokázán" + „statisticky prokázány rozdíly mezi liniemi". Konzistentní.

**Závažnost:** střední (numerický rozpor 0,56 mg/ml vs. 0,58 μg/ml je zásadní k vyjasnění).

---

## 16. Rizika pro oponenturu / obhajobu

**Pravděpodobné dotazy oponenta — připravit odpovědi:**

1. **„Proč duplicity v bibliografii (Conde 2017a/b atd.)?"** — odpovědět: technické nedopatření exportu, opraveno.
2. **„Proč je v diskuzi 0,58 μg/ml a v metodách 0,56 mg/ml?"** — vysvětlit zásobní vs. naředěný standard.
3. **„Jak interpretujete Spearmanův koeficient ρ = 1,000 u endotelů při n = 4?"** — odpovědět: monotónní trend, statisticky neprůkazný kvůli n.
4. **„Jak validujete statistiku přes 4 biologické replikace s různým počtem promývacích cyklů?"** — odpovědět: srovnáním reziduálního titru +0 v experimentech 1–2 vs. 3–4 (mít předpřipravený graf).
5. **„Proč MOI = 5? Je to fyziologicky relevantní?"** — odpovědět: synchronní infekce pro maximální detekci NS1 v ranných intervalech.
6. **„Cituje práce zdroj z roku 2026 (Sabir & Jan)?"** — opravit před obhajobou.
7. **„Jak vysvětlíte stylistickou heterogenitu mezi abstraktem a kapitolou 7?"** — odpovědět odkazem na deklaraci o použití AI pro jazykovou korekturu.

**Riziko:** spíše formální (bibliografie, jazyk), nikoli obsahové. **Obhajoba by měla projít** za předpokladu, že drobné formální závady budou opraveny před odevzdáním a autorka bude umět odpovědět na otázky 2, 3 a 4.

---

## Celkové kvalitativní hodnocení

Práce demonstruje, že studentka:

1. **zvládla netriviální experimentální metodiku** (vícestupňová ELISA optimalizace, plaková titrace, vícefaktorová statistická analýza),
2. **dokáže interpretovat data konzervativně** a přiznat limity (n = 4),
3. **má slušný přehled o literatuře** v oblasti flavivirů a NS1,
4. **má slabší kontrolu nad odborným češtinou** (systémové problémy s anglicismy, nominalizacemi, interpunkcí),
5. **má slabší kontrolu nad bibliografickým aparátem** (duplicity, anachronická citace, chybějící rok),
6. **přiznala použití generativní AI** korektně, ale stylistické dopady této asistence nezvládla zcela vyhladit.

Akademická úroveň je **na střední hranici bakalářské práce v experimentální biologii** — věcně pevná, formálně nedotažená. Před odevzdáním je nutná **systematická revize** ve dvou oblastech (jazyk + bibliografie), nikoli ve výzkumném obsahu.

---

## Verdict on readiness

**Podmíněně připravená k odevzdání po cílených úpravách.**

**Nutné opravy před odevzdáním:**
1. Bibliografie — odstranit duplicity, opravit Sabir & Jan (2026), doplnit rok u Apoorva et al.
2. Seznam zkratek — opravit NK-κB → NF-κB.
3. Tab. I — restrukturalizovat / přepsat.
4. Numerický rozpor 0,56 mg/ml vs. 0,58 μg/ml v textu standardu.
5. Cílená jazyková korektura abstraktu, úvodu a první stránky diskuze (3–4 hodiny redaktorské práce).

**Doporučené úpravy (zvyšují kvalitu, ale nejsou kritické):**
- Doplnit klíčová slova (cs/en) na bibliografický list.
- Doplnit kvantitativní výsledky do abstraktu.
- V diskuzi přidat větu o limitaci n = 4 pro Spearmanovy korelace.
- Doplnit obor / studijní program na titulní list.

Po těchto úpravách práce **standardy bakalářské práce splňuje** a je obhajitelná.

---

## Otevřené nejistoty a co ještě ověřit

- **Skutečný rozsah práce** — bibliografie udává 56 stran, obsah indikuje konec hlavního textu na s. 48; ověřit, zda neexistují přílohy, které nejsou v PDF, který jsem analyzoval.
- **Zda jsou negativní kontroly v Obr. 13 zahrnuté** — z PDF nelze rozlišit, zda sloupce „1 dpi" obsahují i kontroly bez infekce.
- **Konkrétní citace u Sabir & Jan** — `(2026)` může být chybný export, nebo skutečně budoucí update StatPearls; ověřit u zdroje.
- **Variabilita mezi experimenty 1–2 (2 promývání) vs. 3–4 (4 promývání)** — vyžaduje samostatnou analýzu reziduálního titru +0 nebo SD intervalu +0 napříč experimenty; nelze ověřit z dostupných výstupů.
- **Klíčová slova v cs/en verzi** — v PDF ani v txt extraktu jsem je nenašel; pokud existují, mohou být na samostatné straně, kterou bych přehlédl.
- **Soulad s aktuální verzí Opatření prodekana P5** — pracuji s verzí dostupnou na webu PřF JU v dubnu 2026; pokud existuje novější revize, některé formální požadavky se mohly změnit.
