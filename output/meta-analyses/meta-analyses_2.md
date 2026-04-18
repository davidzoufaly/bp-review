# Metaanalýza externích review bakalářské práce

## Executive summary

Tato metaanalýza syntetizuje sedm externích review bakalářské práce *Protivirová imunitní odpověď u flavivirů a její možné úskalí: zaměření na NS1 protein* a filtruje je podle jejich důkazní opory, přesnosti a míry spekulace. Primárním vstupem byly externí analýzy; `input/bp.txt` byl použit jen cíleně pro ověření sporných tvrzení a citací. U formálních náležitostí byl jako normativní referenční rámec použit oficiální dokument PřF JU P5 ze dne 1. 11. 2024. U vybraných bibliografických sporů byly ověřeny autoritativní zdroje mimo práci.

Nejpevnější závěr napříč analýzami je tento: bakalářská práce má věcně nosné experimentální jádro, srozumitelnou makrostrukturu a obhajitelný odborný smysl, ale v aktuální podobě je zatížena zbytečně vysokým formálním a jazykovým rizikem. Nejzávažnější potvrzené problémy neleží v tom, že by práce byla metodicky bezcenná nebo obsahově prázdná, ale v tom, že sama oslabuje vlastní důvěryhodnost: terminologickými chybami, nečistou bibliografií, laboratorním slangem a několika slaběji obhájenými statistickými a autorizačními rozhodnutími.

Současně se ukazuje, že kvalita externích analýz je velmi nerovnoměrná. Některé zachytily skutečně podstatné a ověřitelné chyby, jiné přestřelily AI-signály, zaměnily povinnou bilingvní anotaci za „smíšený jazyk“, nebo dělaly příliš kategorické bibliografické soudy tam, kde je situace jemnější. Finální syntéza se proto neopírá o průměr názorů, ale o vážené převzetí jen těch závěrů, které obstojí po ověření.

## Kritická zjištění

- **[KRITICKÁ]** V textu je prokázaná terminologická chyba `NK-κB` místo `NF-κB`, navíc vnitřně nekonzistentní, protože správná forma `NF-κB` se v jiné pasáži práce současně objevuje.

> „Za produkcí IFN-α a IFN-β stojí aktivace transkripčních faktorů IRF-3, IRF-7 a NK-κB…“

- **[VYSOKÁ]** V metodické části je prokázaná záměna `Protein G` a `G-protein`, která je v biochemickém kontextu věcně nebezpečná.

> „K SN od buněk bylo přidáno dané množství G-proteinu…“

- **[VYSOKÁ]** Bibliografie obsahuje prokázané duplicitní záznamy se sufixy `a/b` u identických DOI (`Conde`, `Lindqvist`, `Muller & Young`, `Rastogi`) a zároveň prokázanou nekonzistenci u položky `Apoorva, Kumar, A., & Singh, S. K. (b.r.)`, přestože v textu je citováno `(Apoorva et al., 2024)` a položka má DOI `10.1080/21688370.2024.2424628`.

> „Apoorva, Kumar, A., & Singh, S. K. (b.r.). Dengue virus NS1 hits hard…“

- **[VYSOKÁ]** Jazyk metodiky a výsledků opakovaně sklouzává do laboratorního slangu a neakademických formulací.

> „Po provedení Two-way ANOVY byly dodělané post-hoc testy…“

> „Amicon byl stáčený na centrifuze…“

- **[STŘEDNÍ]** Statistická interpretace je limitovaná malým `n` a konstrukcí pomocného poměru pro Two-way ANOVA. Nejde o důkaz neplatnosti výsledků, ale o legitimní oponenturní slabinu.

> „…byl vypočítán poměr virového titru a koncentrace naprodukovaného NS1 proteinu, což umožnilo statisticky vyhodnotit experiment Two-way ANOVOU.“

- **[STŘEDNÍ]** Formální soulad s P5 je jen částečně potvrzený. Přítomnost titulního listu, bibliografického údaje, anglické anotace a AI-deklarace je doložitelná; přesné splnění požadavků na PDF/A, podpis, konkrétní datum a fyzickou podobu prohlášení z dostupných vstupů doložitelné není. Navíc text prohlášení se významově blíží P5, ale není s ním doslovně shodný.

- **[STŘEDNÍ]** Autorský přínos u části výsledků je přiznaný, ale měl by být vymezený ještě ostřeji.

> „Optimalizovanou metodou ELISA byly přeměřené i ostatní buněčné kultury (HMC3, SK-N-SH a HBVP), na kterých provedla Mgr. Eliška Kotounová, Msc totožné experimenty.“

## Souhrnné vyhodnocení kvality externích analýz

- `Nejspolehlivější` a zároveň `nejlépe podložená` je **externí analýza 5**. Zachytila více prokázaných textových a bibliografických chyb, přitom většinou držela rozumnou míru jistoty.
- `Nejpřísnější` je **externí analýza 7**. Je diagnosticky velmi užitečná, zejména u P5, metodiky a bibliografie, ale místy sklouzává k příliš kategorickým soudům.
- `Nejpovrchnější` a současně `nejslabší v interpretaci` je **externí analýza 4**. Obsahuje několik jasných misreadů vstupu a podezřele jisté závěry bez odpovídající opory.
- Těsně za analýzou 5 stojí **externí analýza 6**, která je silná v syntéze a prioritizaci rizik, ale několik bibliografických soudů formulovala tvrději, než dovolují ověřená data.

## Vyhodnocení externí analýzy 1

**Co vidí správně**

- Velmi dobře zachycuje lokální jazykové vady metodiky a výsledků: `Mili Q`, `dodělané`, `stáčený`, `oživení`.
- Správně identifikuje problém `Protein G` versus `G-protein`.
- Přiměřeně hodnotí práci jako obsahově silnou, ale jazykově a terminologicky nedotaženou.

**Co přehání, chybně interpretuje nebo míjí**

- Tvrdí, že v práci je „ledová kyselina“ bez upřesnění „octová“, ale v cíleně prohledaném `bp.txt` se tato pasáž neobjevila; tento nález tedy z dostupného vstupu nelze potvrdit.
- Přehlíží zásadnější bibliografické a citační vady, které se později ukázaly jako významnější než část jím akcentovaných jazykových detailů.
- Nevšimla si chyby `NK-κB`, která je pro obhajobu minimálně stejně nebezpečná jako `G-protein`.

**Verdikt**

Analýza 1 je užitečná a konkrétní v mikroúrovni jazyka a terminologie, ale není dostatečně úplná a na jednom důležitém bodě (`ledová kyselina`) zůstává neověřená.

## Vyhodnocení externí analýzy 2

**Co vidí správně**

- Správně upozorňuje na potřebu zpřesnit interpretaci korelací a limitací malého `n`.
- Zachycuje duplikace v bibliografii a všímá si obecné formální nekonzistence.
- Dobře postihuje, že teoretická část někdy přenáší poznatky z jiných flavivirů na TBEV jen analogicky.

**Co přehání, chybně interpretuje nebo míjí**

- Přestřeluje jazykové hodnocení a místy si doslova domýšlí příklady; například pracuje s formulací typu „bychom se ráda“, která v cíleně ověřeném textu práce doložena nebyla.
- Tvrdí, že AI-prohlášení je příliš vágní, ale P5 v aktuálním znění požaduje doplnit nástroj a důvod použití; práce uvádí `ChatGPT` i účel použití.
- Označuje `Sabir & Jan (2026)` za „budoucnost“, což neobstojí po ověření: aktuální NCBI Bookshelf nyní uvádí `StatPearls [Internet]; 2026 Jan-`, s poslední aktualizací kapitoly 1. prosince 2025.
- Silně nadhodnocuje stylistické ukazatele AI bez dostatečné distinkce mezi skutečným důkazem a dojmem.

**Verdikt**

Analýza 2 obsahuje několik legitimních připomínek, ale v interpretaci je rozkolísaná a příliš sebevědomá tam, kde by měla zůstat jen u podezření.

## Vyhodnocení externí analýzy 3

**Co vidí správně**

- Je opatrnější než analýza 2 v tom, že AI nepovažuje za důkaz neautentičnosti obsahu.
- Správně připouští, že práce je vědecky nosná a strukturálně přiměřená.
- Dobře upozorňuje na potřebu standardizace bibliografie.

**Co přehání, chybně interpretuje nebo míjí**

- Příliš spekuluje nad „uhlazeností“ abstraktu a z fluentní angličtiny dělá nepřiměřeně silný AI-signál.
- Označuje `Liang & Dai (2024)` za položku, jejíž existence je sporná; to je po ověření chybné, článek ve *Frontiers in Microbiology* reálně existuje a byl publikován 14. srpna 2024.
- Tvrdí, že `Fares et al. (2020)` není v bibliografii viditelný; v `bp.txt` bibliografii prokazatelně je.
- Přehled terminologických a metodických rizik je slabší než u analýz 5–7.

**Verdikt**

Analýza 3 je použitelná jako opatrná sekundární vrstva, ale selhává ve verifikaci několika snadno dohledatelných bibliografických tvrzení. Je spíš opatrně napsaná než skutečně přesná.

## Vyhodnocení externí analýzy 4

**Co vidí správně**

- Správně zachycuje alespoň část bibliografických problémů, zejména duplicitu `Conde et al. (2017a/b)`.
- Správně upozorňuje, že práce má celkově slušnou makrostrukturu.

**Co přehání, chybně interpretuje nebo míjí**

- Zjevně chybně četla bilingvní anotaci jako „anglický text v češtině“:

> „Pasáž v abstraktu ‘Because the host immune response is highly complex…’ je patrně AI-pročitaná, následují ale český text.“

Ve skutečnosti jde o standardní sousedství české a anglické anotace na bibliografickém listu.

- Tvrdí, že kapitola 4.5 není v textovém extraktu dostupná; v `bp.txt` dostupná je.
- Z „Muller & Young, 2013“ versus „van den Elsen et al., 2021“ dělá problém jednotnosti `et al.`, což je metodicky chybné: rozdíl plyne z odlišného počtu autorů, nikoli z nekonzistence stylu.
- Podezírá práci z „factical neoverení“ u tvrzení o více než 70 flavivirech, ačkoli bez pokusu o ověření autoritativního zdroje.

**Verdikt**

Analýza 4 je nejméně důvěryhodná. Má několik správných intuic, ale zároveň obsahuje zřetelné misready a metodicky slabé závěry, které nelze bezpečně převzít.

## Vyhodnocení externí analýzy 5

**Co vidí správně**

- Velmi přesně identifikuje chybu `NK-κB` a správně ji klasifikuje jako věcnou, ne jen stylistickou.
- Správně zachycuje `CCR5` jako receptor, nikoli chemokin.
- Správně identifikuje duplicitní bibliografické záznamy a rozpor `Apoorva et al., 2024` versus `(b.r.)` v seznamu literatury.
- Metodologickou kritiku drží v obhajitelné míře: neprohlašuje experiment za neplatný, ale upozorňuje na limity Spearmanovy korelace při `n = 4`.
- U `Sabir & Jan (2026)` zůstává rozumně zdrženlivá a nevydává tento bod za jistou chybu.

**Co přehání, chybně interpretuje nebo míjí**

- Místy má sklon přísněji formulovat dopad jednotlivých chyb na oponenturu, než je nutné.
- Nevěnuje se tolik strukturálnímu rozlišení mezi prokazatelným problémem a neověřitelným layoutovým dojmem.

**Verdikt**

Analýza 5 je nejspolehlivější a nejlépe podložená. Jako základ finální syntézy má nejvyšší váhu.

## Vyhodnocení externí analýzy 6

**Co vidí správně**

- Velmi dobře skládá širší syntézu: jazyk, bibliografie, metodické limity i oponenturní strategii.
- Správně zachycuje duplikace v bibliografii, rozpor u `Apoorva`, chybu `NK-κB` a slabiny poměrové analýzy.
- Přiměřeně hodnotí práci jako obsahově udržitelnou, ale formálně nedotaženou.
- Dobře rozlišuje mezi vysokým rizikem v bibliografii a středním rizikem ve statistice.

**Co přehání, chybně interpretuje nebo míjí**

- Tvrdí, že `Sabir & Jan (2026)` je anachronismus; po aktuálním ověření to nelze potvrdit takto kategoricky.
- Podezření kolem rozsahu `p. 56` versus konec obsahu na s. 48 je legitimní, ale bez znalosti fyzického svazku nebo příloh zůstává jen podezřením.
- Některé vizuální výtky k layoutu nelze z textového zdroje přenést s vysokou jistotou.

**Verdikt**

Analýza 6 je velmi silná a prakticky nejpoužitelnější pro finální hodnotící zprávu. Jen je třeba mírně zkorigovat některé kategorické bibliografické závěry.

## Vyhodnocení externí analýzy 7

**Co vidí správně**

- Nejlépe pracuje s normativním rámcem P5 a správně připomíná, že u formálních náležitostí nestačí obecný dojem „vypadá to jako standard“.
- Správně upozorňuje na rozdíl mezi názvem práce a užší experimentální náplní, aniž by z toho dělala fatální nesoulad.
- Velmi dobře zachycuje oponenturní zranitelnost poměrové Two-way ANOVY a korelací při `n = 4`.
- Správně zpochybňuje automatické převzetí layoutových soudů, když není vše doložené.

**Co přehání, chybně interpretuje nebo míjí**

- Příliš kategoricky označuje `Sabir & Jan (2026)` za fakticky chybný záznam; aktuální NCBI stav tomu neodpovídá.
- Stejně příliš kategoricky zachází s některými roky online-first publikací. U `Wahaab et al.` je situace smíšená: PubMed uvádí `Int J Mol Sci. 2024 Dec 24`, zatímco issue citation odpovídá ročníku 2025. Tvrdit jednoduše „2024 je chyba“ je proto příliš silné.
- Je přísná na hraně přepólování: místy už spíše simuluje oponenta než analyticky váží sílu důkazu.

**Verdikt**

Analýza 7 je nejpřísnější a velmi cenná jako stres-test práce, ale není vhodné ji přebírat bez korekce jistoty a bez doplnění bibliografických nuancí.

## Porovnání všech 7 externích analýz

### Hlavní shody mezi analýzami

- Práce má smysluplné experimentální jádro a není obsahově prázdná.
- Makrostruktura práce je v zásadě logická a odpovídá očekávatelnému schématu experimentální bakalářské práce.
- Jazyková vrstva práce je slabší než odborné jádro a před odevzdáním vyžaduje redakční zásah.
- Bibliografie není čistá a zaslouží důkladný audit.
- AI byla v práci deklarována; žádná analýza nepředložila důkaz, že by experimentální obsah byl generován AI.

### Hlavní rozpory mezi analýzami

- **Míra jazykové závažnosti:** analýzy 1, 5, 6 a 7 mluví o vážném, ale opravitelném problému; analýzy 2 a 4 jazyk místy líčí téměř jako diskvalifikační.
- **AI-signály:** analýzy 2, 3 a 4 přisuzují hladkosti textu příliš velkou diagnostickou váhu; 5, 6 a 7 jsou v tom opatrnější.
- **Formální soulad s P5:** analýzy 1, 3, 4 a 5 mají sklon vycházet z dojmu „většinou v pořádku“, zatímco 7 správně připomíná, že část bodů je bez PDF a finální odevzdávané verze neověřitelná.
- **Bibliografický fact-check:** analýzy 5–7 zachytily hlubší problémy, ale 6 a 7 někdy formulují příliš tvrdě to, co je ve skutečnosti jen pravděpodobný problém.
- **Metodika/statistika:** analýza 6 je relativně benevolentní; analýza 7 je naopak nejtvrdší. Přesvědčivější je střední pozice: metodika je obhajitelná, ale statisticky limitovaná.

### Body s vysokou jistotou

- `NK-κB` je prokázaná chyba v textu i v seznamu zkratek.
- `G-protein` v purifikaci protilátek je prokázaný terminologický problém.
- Bibliografie obsahuje prokázané duplicity u identických DOI.
- Položka `Apoorva ... (b.r.)` je v rozporu s vlastním in-text odkazem `(2024)` i s DOI nesoucím rok 2024.
- Práce používá laboratorní slang nevhodný pro akademický text.
- Použití dat z experimentů Mgr. Kotounové je přiznáno, ale zaslouží ještě jasnější vymezení.

### Slabě podložené body

- Silné soudy o „AI-generovaném textu“ založené převážně na rytmu věty, nominalizacích nebo kvalitní angličtině.
- Tvrzení, že anglický odstavec v anotaci je nepatřičný „anglický text v češtině“.
- Kategorické soudy, že `Sabir & Jan (2026)` je nutně chybný bibliografický údaj.
- Kategorické soudy, že `Wahaab et al. (2024)` je nutně špatně, bez rozlišení online-first a issue-year.
- Layoutové soudy, které nejsou z dostupného textového vstupu doložitelné.

### Závěry s nejvyšší důkazní silou

- Oponenturně nejnebezpečnější nejsou spekulované AI-signály, ale tvrdé, snadno viditelné chyby: `NK-κB`, `G-protein`, duplicity v literatuře, rozpor `Apoorva`, slang metodiky.
- Práce sama v úvodu poctivě přiznává, že neměří protivirovou imunitní odpověď přímo; námitka „název je širší než experiment“ je tedy relevantní, ale ne likvidační.
- Statistická část není nekorektní, ale její interpretační síla je menší, než by naznačovala sebejistější formulace některých review.

### Závěry nepřevzitelné do finální syntézy

- Podezření, že `Liang & Dai (2024)` nemusí existovat nebo nemusí být peer-reviewed.
- Tvrzení, že `Fares et al. (2020)` v bibliografii chybí.
- Tvrzení, že AI-deklarace je formálně nedostatečná jen proto, že nevyjmenovává přesné procento zásahů.
- Tvrzení, že samotná plynulost angličtiny je silný indikátor generování obsahu.

### Oblasti přehlédnuté všemi 7 externími analýzami

- Nikdo neprovedl systematický audit úplnosti seznamu zkratek. Přitom v textu běžně vystupují zkratky a označení jako `SN`, `PBS`, `SEM`, `HBVP`, `HMC3`, `SK-N-SH`, `AGS` nebo `PFU/ml`, které v seznamu zkratek chybějí.
- Nikdo explicitně nepojmenoval, že bilingvní bibliografický list může být zdrojem falešně pozitivních AI-signálů. Právě tato slepá skvrna vedla alespoň jednu analýzu k chybné interpretaci anglické anotace jako „smíšeného jazyka“.
- Nikdo neoddělil dostatečně přísně „prokázanou chybu práce“ od „chybného fact-checku externí analýzy“. Výsledkem je, že se v některých review mísí skutečné vady bakalářky s vadami samotného review procesu.

## Metaanalýza a finální syntéza

### Soulad se zadáním a akademickým účelem

Práce je v jádru v souladu se zadáním, jen název tematizuje širší rámec, než experiment skutečně měří. Tento nesoulad je ale v samotné práci přiznán:

> „Práce tedy neposuzuje protivirovou imunitní odpověď přímo, ale zaměřuje se na jeden z faktorů, který s ní může přímo souviset.“

To je důležité. Nejde tedy o skrytou koncepční chybu, ale o otázku, zda je toto zúžení dostatečně explicitně dotaženo i v diskuzi a závěru. Můj závěr: ano, práce je akademicky legitimní, ale formulace názvu a přechodu od teorie k experimentu zvyšuje nárok na obhajobové vysvětlení.

### Struktura práce a logická návaznost

Makrostruktura je dobrá. Teoretická část, cíle, metodika, výsledky a diskuze tvoří srozumitelný celek. Slabším místem není chaos, ale spíše redundance a ne zcela čistá hierarchie některých podkapitol o NS1. Analýzy, které z práce dělají strukturální problém, nejsou přesvědčivé. Jde spíš o práci, která je strukturovaná dostatečně, nikoli výjimečně.

### Formální náležitosti a soulad s P5

Po ověření proti oficiálnímu P5 PřF JU ze dne 1. 11. 2024 lze říci:

- přítomnost titulního listu, bibliografického údaje, anglické anotace a AI-deklarace je doložená,
- P5 skutečně vyžaduje PDF/A bez vodoznaků, Times New Roman 12, řádkování 1,5, zarovnání do bloku, závazný titulní list, konkrétní text prohlášení, a při použití AI i doplnění nástroje a důvodu,
- práce má AI-deklaraci věcně správně, protože uvádí nástroj i účel,
- přesnou technickou kompatibilitu PDF/A a přítomnost podpisu/konkrétního data však z textového výstupu potvrdit nelze,
- samotné prohlášení není doslovnou kopií formulace P5, takže nejde o čistý „splněno bez výhrad“.

Tvrzení některých analýz, že AI-deklarace je příliš obecná, nepovažuji za přesvědčivé. Tvrzení, že je vše formálně bez problému, také ne. Přesvědčivější je střední pozice: práce je formálně blízko souladu, ale část bodů zůstává otevřená a jeden bod – doslovná formulace prohlášení – je pravděpodobně jen aproximací požadavku.

### Dodržení citačního stylu a práce se zdroji

Tady je práce nejslabší po jazyce. Rozhodující není detail typu `DOI ano/ne`, ale kombinace čtyř druhů potíží:

- prokázané duplicitní záznamy,
- rozpor mezi in-text a bibliografií u `Apoorva`,
- volba slabšího zdroje `StatPearls` pro elementární imunologii,
- občasné přenášení poznatků z jiných flavivirů na TBEV bez dostatečně viditelného signalizování hranice jistoty.

Naopak nepřijímám podezření, že `Liang & Dai (2024)` je sporný zdroj. Ověření ukazuje, že jde o existující článek ve *Frontiers in Microbiology*, publikovaný 14. srpna 2024. Stejně tak nepřijímám kategorický soud, že `Sabir & Jan (2026)` je nutně chybný rok. Po aktuálním ověření lze spolehlivě říci jen to, že jde o bibliograficky a metodicky slabší volbu zdroje, ne o prokázanou neexistenci.

### Jazyk, styl a terminologie

To je nejslabší vrstva práce. Přesnější je ale mluvit o kombinaci tří problémů než o nějaké obecné „špatné češtině“:

- lokální terminologické chyby s vysokým dopadem (`NK-κB`, `G-protein`, `CCR5`),
- laboratorní a polohovorové formulace v metodice a výsledcích,
- těžkopádnost a kalky, které zhoršují čitelnost, ale samy o sobě nejsou důkazem AI generování.

Nejpřesnější interpretace AI otázky je tato: práce vykazuje stylovou heterogenitu konzistentní s deklarovanou AI korekturou, nikoli konzistentní s důkazem, že obsah vznikl strojově. Analýzy, které z plynulé angličtiny nebo z nominalizací dělají skoro forenzní důkaz, jdou dál, než dovoluje evidence.

### Argumentace, metodologie a kritické myšlení

Experimentální jádro je obhajitelné. Výsledky nejsou bezcenné, metodika není zjevně chybná a diskuze se umí opřít o literaturu. Slabina leží spíš v interpretabilditě některých statistických kroků:

- Spearmanova korelace nad čtyřmi časovými body má velmi nízkou vypovídací sílu.
- Poměr `virový titr / NS1` je analyticky slabší než samostatná práce s oběma proměnnými.
- Přítomnost cizích experimentálních sérií od Mgr. Kotounové je transparentně přiznána, ale autorský přínos by měl být vymezen ještě čistěji.

Nejpřesvědčivější výklad tedy není „metodika je špatně“, ale „metodika je v bakalářském rámci přijatelná, ovšem statisticky a interpretačně skromnější, než by si práce sama přála“.

### Rizika plagiátorství, nepřiznané parafráze a AI-generovaného textu

Z dostupných vstupů neplyne podklad pro kategorické obvinění z plagiátorství ani z AI-generovaného obsahu. Vizuální zdroje jsou vesměs označené, AI je explicitně deklarovaná a text obsahuje dostatek lidsky specifických, neuhlazených a lokálně nekonzistentních míst, aby hypotéza „masově vygenerovaného textu“ nebyla přesvědčivá.

Správný závěr je opatrnější:

- **prokázaná chyba**: jazyková a terminologická nedotaženost,
- **pravděpodobný problém**: přílišná závislost na jazykové korektuře bez následné lidské redakce,
- **podezření vyžadující ověření**: těsnost některých parafrází vůči review literatuře, což ale bez similarity systému nelze rozhodnout.

## Top priority fixes

1. Opravit `NK-κB` na `NF-κB` v textu i seznamu zkratek.
2. Opravit `G-protein` na `Protein G` ve všech relevantních pasážích metodiky.
3. Ručně vyčistit bibliografii: odstranit duplicity `Conde`, `Lindqvist`, `Muller & Young`, `Rastogi`.
4. Opravit položku `Apoorva ... (b.r.)` a sjednotit ji s in-text citací.
5. Znovu projít slabé nebo hraniční bibliografické položky (`Sabir`, online-first záznamy) podle autoritativních databází, ne podle exportu citačního manažeru.
6. Provést cílenou jazykovou redakci metodiky a výsledků: odstranit slang, pádové chyby, neobratné vazby a technicky neakademické formulace.
7. Přidat explicitní větu o limitaci korelačních závěrů při `n = 4` a obhájit použití poměru pro Two-way ANOVA.
8. Ještě ostřeji oddělit vlastní experimentální výkon autorky od dat navázaných na experimenty Mgr. Kotounové.
9. Zkontrolovat úplnost seznamu zkratek a doplnit chybějící položky.
10. Před finálním odevzdáním ověřit skutečný soulad prohlášení, data, podpisu a technických parametrů PDF s P5.

## Rizika pro oponenturu a obhajobu

- **[VYSOKÁ]** Oponent zachytí `NK-κB`, pokud má byť základní imunologické zázemí.
- **[VYSOKÁ]** Oponent může velmi rychle znejistět po pohledu na duplicitní bibliografii; to podkopává důvěru i tam, kde je obsah dobrý.
- **[VYSOKÁ]** `Protein G` versus `G-protein` je přesně ten typ chyby, který působí hůř než řada větších stylistických nedostatků.
- **[STŘEDNÍ]** Bude padat otázka, co přesně je vlastní experiment autorky a co už je převzatá nebo navazující datová vrstva.
- **[STŘEDNÍ]** Padne otázka, proč byla použita Spearmanova korelace při `n = 4` a proč byl analyzován poměr místo dvou proměnných zvlášť.
- **[NÍZKÁ]** Mohou padnout dotazy na použití AI, ale pokud autorka zůstane u deklarovaného rozsahu jazykové korektury, nejde o hlavní obrannou linii.

## Finální verdikt

Práce je obsahově obhajitelná a její experimentální jádro má reálnou hodnotu. Současně ale v současné podobě není formálně ani jazykově dostatečně dotažená na to, aby se dala bez zbytečného rizika označit za připravenou k odevzdání. Největší hrozbou není metodická prázdnota, ale zbytečně viditelné chyby, které působí dojmem nedotaženosti a oslabují důvěru ve zbytek textu.

Nejpřesnější celkové hodnocení tedy zní: **obsahově slibná a obhajitelná práce, která však před odevzdáním potřebuje tvrdou terminologickou, bibliografickou a jazykovou sanaci.**

## Otevřené nejistoty a co ještě ověřit

- Zda finální odevzdaná verze skutečně splňuje technický požadavek P5 na `PDF/A`.
- Zda je v reálné odevzdané podobě bibliografický list opatřen konkrétním datem a podpisem, nebo jde jen o pracovní export.
- Zda rozdíl mezi `p. 56` a koncem obsahu na s. 48 odpovídá přílohám či front matter, nebo jde o nepřesný bibliografický údaj.
- Jak přesně chce školitelské pracoviště formulovat hranici mezi vlastními daty autorky a navazujícími experimentálními sériemi Mgr. Kotounové.
- Který bibliografický rok je zvolen u online-first článků v celém seznamu a zda je tento princip použit konzistentně.

---

## Forenzní annex

Tato sekce záměrně nepůsobí diplomaticky. Neopakují se v ní hlavní závěry; rozšiřuje je o tvrdší diagnostiku práce i samotných externích analýz.

### 1. Co je v práci skutečně nebezpečné

- `NK-κB` není „překlep jako každý jiný“. Je to chyba, která okamžitě signalizuje rozpojení terminologické kontroly.
- `G-protein` v kontextu purifikace protilátek není kosmetika. Je to chyba, která při obhajobě zní jako záměna dvou různých biologických entit.
- Duplicitní bibliografie není jen estetický problém. Je to viditelná známka, že autor nebo redakční dohled pustili ven seznam literatury bez základního auditu.
- Přiznaná AI korektura práci eticky nepoškozuje. To, co ji poškozuje, je nevyrovnaný výsledek: část textu je uhlazená, část laboratorně syrová. Problém je redakční selhání, ne samotné přiznání nástroje.

### 2. Kde externí analýzy samy selhaly

- Některé analýzy zaměnily povinnou anglickou anotaci za „angličtinu v českém textu“. To není přísnost; to je chybné čtení vstupu.
- Některé analýzy zacházely s AI-signály jako s téměř forenzním indikátorem, aniž by měly pevnější oporu než stylový dojem.
- Některé analýzy dělaly kategorický fact-check tam, kde by poctivější bylo napsat „pravděpodobný problém, vyžaduje ověření“.

Zvlášť ilustrativní jsou tyto dva příklady:

> „Pasáž v abstraktu ‘Because the host immune response is highly complex…’ je patrně AI-pročitaná, následují ale český text.“

To je chybné čtení bibliografického listu, nikoli platný nález o práci.

> „Sabir & Jan (2026) … dosud nevydaný zdroj.“

Aktuálně ověřený stav NCBI Bookshelf tomu neodpovídá. Přesnější soud zní: bibliograficky a metodicky slabší volba zdroje, ne bezpečně prokázaná neexistence.

### 3. Které závěry bych do oponentury nepřevzal

- Nepřevzal bych rétoriku o „silných AI-signálech“, pokud by měla sloužit jako hlavní linie kritiky práce.
- Nepřevzal bych tvrzení, že práce je metodicky skoro neobhajitelná. To neodpovídá tomu, co je z textu skutečně doložitelné.
- Nepřevzal bych ani opačný extrém, totiž že práce je „v zásadě hotová a chybí jen kosmetika“. To podceňuje závažnost terminologických a bibliografických chyb.

### 4. Tvrdá diagnostická syntéza

Kdyby oponent viděl jen vědeckou myšlenku, práce obstojí. Kdyby viděl jen povrch textu, práce se sama poškodí. Rozdíl mezi přijatelnou a zbytečně zpochybnitelnou prací zde nedělá experiment, ale disciplína při finální redakci.

Nejtvrdší, ale věcně podložené shrnutí proto zní:

- práce není slabá proto, že by nevěděla, co zkoumá,
- práce je slabá tam, kde působí, jako by po dokončení experimentu nikdo neprovedl poslední intelektuální úklid,
- a přesně to je důvod, proč část externích analýz sahá k přestřeleným interpretacím: text jim k tomu zbytečně dává příležitost.

Pokud má finální verze obstát, musí odstranit právě ty chyby, které jsou nejvíc vidět po prvním otevření: terminologie, bibliografie, jazyková poloha a čistota autorství dat. Bez toho bude práce obhajitelná jen navzdory své podobě, ne díky ní.
