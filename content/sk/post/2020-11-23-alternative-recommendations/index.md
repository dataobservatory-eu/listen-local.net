+++
title = "Listen Local: Prečo potrebujeme alternatívne odporúčacie systémy"

date = 2020-11-23T17:10:00+02:00
lastmod = 2020-12-22T17:10:00+02:00
draft = false

authors = ["Daniel Antal"]

tags = ["listen-local", "Slovakia", "justice", "algorithms", "big-data", 
"recommendations", "local-content-requirements"]

summary = "Regulácia súkromných, blackboxových algoritmov a dátových monopolov je len prvým krokom na zmiernenie škôd. Iba nasadenie bielych, transparentných algoritmov a vytváranie spoločných alebo otvorených súborov dát môže zaručiť spravodlivosť na digitálnych platformách, v odporúčaniach a všeobecne v používaní umelej inteligencie."

projects = ["listen-local"]

# Featured image
[image]
  # Caption (optional)
  caption = "Our Demo Application"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"

  # Show image only in page previews?
  preview_only = true

+++

{{< figure src="03_app_recommend.png" title="Prvá verzia našej demo aplikácia" >}}
 
Odporúčacie systémy využívajú vedomosti o hudobnej tvorbe a jej publiku a zároveň sledujú ciele alebo potreby odporúčajúcich. 

Najjednoduchšie odporúčacie systémy sledujú hudobné rebríčky: napríklad, vyberajú z aktuálnych alebo dlhodobých hitov. Takéto systémy môžu vyhovovať amatérskemu DJ-ovi na domácej oslave, alebo malému lokálnemu rádiu, ktoré si chce jednoducho zaistiť, aby sa hudba v jeho programe páčila čo najväčšiemu počtu ľudí. Zosilňujú tak existujúce trendy a čoraz viac popularizujú už populárnu hudbu a jej tvorcov.

Ak je odporúčací vyhľadávač podporovaný veľkými dátami a systémom strojového učenia alebo je dokonca kombináciou viacerých strojovo učených algoritmov, je všeobecný modus operandi využívať informácie o tvorbe a aj o používateľoch za účelom dosiahnutia istých cieľov. Po tejto stránke môžu byť podobné nariadeniu o lokálnej tvorbe, ktorej cieľom je dosiahnuť 15-percentnú kvótu slovenskej hudby. 


## Ako fungujú odporúčacie vyhľadávače?

{{< figure src="mind_map_recommendations_sk.png" title="Ako fungujú odporúčacie vyhľadávače?" >}}

Odporúčací systém využívaný službou Spotify je spojením obsahu a kolaboratívneho filtrovania, ktorý využíva informácie o predošlom správaní sa užívateľov (napríklad: lajkované, preskočené a spätne vypočuté piesne), o informácie o správaní podobných užívateľov a tiež nazbierané dáta z užívateľových sociálnych sietí a iných online aktivít. Deezer využíva podobný systém podporovaný zberom informácii zo stránky Last.fm - veľké dáta vytvorené z komentárov používateľov sú využívané napríklad na pochopenie nálady piesní.

{{< figure src="spotify_discover_weekly.png" title="Spotify vydá v roku 2020 každý mesiac 16 miliárd hudobných odporúčaní." >}}

YouTube, ktorý hrá ešte väčšiu rolu v objavovaní hudby, využíva systém zložený z dvoch neurónových sietí: jedna pre tvorbu čakateľa a jedna pre určovanie poradia. Dômyselná neurónová sieť generujúca čakateľa poskytuje diela na základe kolaboratívneho filtrovania, kým radiaci systém funguje na základe filtrovania obsahu a na hodnotení užitočnosti, ktoré berie do úvahy napríklad jazyk používateľa.

Čo robí tieto systémy bežnými je to, že maximalizujú kľúčové ukazovatele výkonnosti tvorcov algoritmov. Spotify chce byť Váš ‘playlist do života’ a chce zvyšovať množstvo hranej hudby v pozadí počas práce, športu, alebo cestovania, alebo aj počas aktívneho počúvania hudby. Je to v podstate maximalizácia času stráveného používaním týchto systémov a zároveň zamedzenie, aby prázdne časové okná boli vyplnené inými hudobnými sprostredkovateľmi ako napríklad rádiami.

## Aký je problém s black boxovými odporúčacími systémami?

Čo majú spoločné je to, že ich cieľom nie je dávať férovú šancu každej nahranej skladbe, slúžiť každému umelcovi rovnako alebo zabezpečiť rovnomerné šance pre anglické, slovenské alebo perzské skladby. Väčšinou majú tendenciu tlačiť trendy podobné hudobným rebríčkom, ale s oveľa väčšou účinnosťou. Holandský komik, autor a žurnalista Arjen Lubach vysvetľuje, že YouTubový algoritmus zaisťuje, aby boli ich osobné odporúčania aktívne celý deň a celú noc, a tým zaisťujú komfortné prostredie pre používateľa, ktoré mu umožňuje minimálne rozptýlenie. Ak chce používateľ počúvať globálne hity alebo „stoner rock“, nikdy ich nerozptýlia niečím iným.

<iframe width="710" height="410" src="https://www.youtube.com/embed/FLoR2Spftwg?cc_load_policy=1&origin=http://dataandlyrics.com&cc_lang_pref=en" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

*Zontag stretol Lubacha na Holandskom verejnom vysielaní VPRO. Kliknite na nastavenia pre
zmenu jazyka tituliek.*

Problém s takýmto hyper-personalizovaným médiami je, že nenechávajú priestor verejným
aktivitám. Verejnoprávni vysielatelia, ktorí mali monopol na televízne vysielanie vo väčšine
európskych krajín od začiatku 90. rokov, sa zameriavali na šírenie rozmanitosti správ, mali napríklad cieľ vysielať rozmanitosť správ, vedomostí spolu s prístupom k lokálnej kultúre. Veľa krajín na rôznych kontinentoch dodržiava vysielanie pokyny týkajúce sa miestneho obsahu pre vysielanie na verejných, komerčných a komunitných televíznych a rozhlasových kanáloch ako napríklad lokálnu hudbu a filmy a overené spravodajstvo. Personalizované média, sociálne siete a streamovacie platformy nemajú takéto záväzky.

Blackboxové odporúčacie systémy väčšinou maximalizujú kľúčový ukazovateľ výkonnosti spoločnosti a nepodliehajú obvyklým predpisom o nových verejných službách či o miestnom obsahu, aké majú tradičné vysielacie médiá. 

Cieľ a kroky, ktoré sledujú algoritmy nie sú autorom známe a nie sú si vedomí toho, kedy algoritmy
fungujú v ich prospech a kedy nie.

## Transparentný, dôveryhodný a regulovaný algoritmus

Podľa nášho názoru môže systém odporúčaní založený na užitočnosti poskytnúť most medzi aktuálnymi korporátne vlastnenými systémami, ktoré maximalizujú obchodné indikátory médií alebo
streamovacích platforiem.

Požiadavky na nové verejné služby alebo požiadavky na miestny obsah (*“národné kvóty”*) určené na komerčné vysielanie sú podobné úžitkovým alebo vedomostným odporúčacím systémom. Napríklad, úžitkový odporúčací systém by z dvoch kandidátov preferoval toho, ktorý má slovenského skladateľa alebo interpreta z Walesu alebo toho, ktorý má perzské texty. 

Naša skúšobná aplikácia vytvára odporúčania na základe už existujúcich rádií alebo osobných playlistov, ktorý podľa výberu obsahuje vopred definovaný pomer hudby vyrobenej na Slovensku alebo interpretovanej slovenskými umelcami. Do skúšobnej verzie pridáme čoskoro aj holandské a maďarské možnosti voľby, ale do aplikácie by sme mohli prirodzene pridať preferencie akéhokoľvek mesta, regiónu, oblasti či krajiny. 

Naša skúšobná aplikácia a sprievodná projektová štúdia na Slovensku poukazuje na to, ako môže regulačný orgán vytvoriť lepšie regulácie vysielania, pričom sa poučí zo skúseností so streamovacími platformami založenými na umelej inteligencii a ako môže tento systém uplatniť ciele požiadaviek miestneho obsahu (napr. určitú viditeľnosť slovenskej alebo mestskej hudby) a požiadaviek verejného záujmu (napr. šírenie spoľahlivých informácií alebo zastavenie [hudby s nenávistným](https://dataandlyrics.com/post/2020-10-30-racist-algorithm/).

Link: [Etické usmernenia pre dôveryhodnú umelú inteligenciu](https://op.europa.eu/sk/publication-detail/-/publication/d3988569-0434-11ea-8c1f-01aa75ed71a1)

## Prístup pre všetkých

Neveríme, že súčasná búrlivá diskusia o regulácii umelej inteligencie a streamovania hudby vyrieši všetky problémy nezávislých umelcov, skupín etnických alebo rasových menšín alebo inak zraniteľných producentov. Nové regulácie by mohli limitovať neúmyselne napáchanú škodu veľkými dátovými algoritmami nasadených veľkými korporáciami, ale zároveň nezmenšia benefity algoritmov pre týchto umelcov.

Zoberte si príklad novej [kontroverznej iniciatívy](https://www.theguardian.com/technology/2020/nov/03/spotify-artists-promote-music-exchange-cut-royalty-rates-payola-algorithm), ktorá umožňuje umelcom, hudobným vydavateľstvám a vydavateľom propagovať ich hudbu výmenou [za zníženie sadzieb licenčných poplatkov]((https://newsroom.spotify.com/2020-11-02/amplifying-artist-input-in-your-personalized-recommendations/)). Aj keď mnohí umelci cítia, že toto je nespravodlivé a dokonca až skorumpované, je to odpoveď na večne rastúcu potrebu ovplyvniť skutočnosť ako algoritmické systémy propagujú určitú hudbu na úkor desiatok tisíc nahrávok, ktoré nie sú odporúčané.

Veríme, že algoritmy sú hodnotné pre užívateľov a ak nie sú umelci ochotní platiť korporáciam za vplyv na `black boxové algoritmy`, tak musia spolupracovať a zdieľať údaje a vytvárať dostatočné veľké dátové fondy na to, aby mohli nasadiť biele, transparentné algoritmy, ktoré fungujú v ich prospech.

*	Naša štúdia poukazuje na to, prečo je dôležité, aby mali `umelci kontrolu nad tým aké dáta popisujú ich tvorbu`, ich biografiu a iné informácie na internete, pretože korporátne streamovacie platformy tieto informácie na ich algoritmy používajú.

*	Mali by sme poukázať na to, že tvorcovia vedia s relatívne malým úsilím `zhromaždiť dostatok informácií`(zhromažďovať a následne súborne zdieľať dostatok informácií) na vytvorenie alternatívnych odporúčacích systémov, ktoré sledujú prijateľnejší cieľ, ktorý je citlivý na požiadavky miestneho obsahu, je lepšie prístupný novým umelcom, ženám alebo interpretom iných rás a ktorý potláča nenávistné texty.

*	Výhoda `otvoreného algoritmu` a nazbieraných dát je tá, že umelci môžu aktívne vyhľadávať publikum v rôznych vekových skupinách alebo mestách, ktoré sú im prístupné na turné po pandémii.

Celkovo chceme ukázať, že regulovanie _black boxu_, súkromné algoritmy a dátové monopoly sú len prvým krokom k sanácii škôd. Jedine nasadenie bielych, transparentných algoritmov a vybudovanie zdieľaných alebo otvorených dátových fondov môže garantovať férovosť v digitálnych platformách, v odporúčaniach a vo všeobecnom používaní umelej inteligencie.

_[Listen Local](https://dataandlyrics.com/tag/listen-local/) vytvára transparentné algoritmy a `open source` riešenia za účelom vyhľadávania nového publika pre nezávislú hudbu. Chceme napraviť nespravodlivosť a inherentnú zaujatosť trhu, ktorý aplikuje veľké dátové algoritmy. Ak by ste chceli svoju hudbu a publikum nechať analyzovať iniciatívou ‘Listen Local’, vyplňte [tento dotazník](https://www.surveymonkey.com/r/ll_collector_2020). Zahrnieme vás v našej skúšobnej aplikácii pre odporúčanie lokálnej hudby a naša analýza bude odhalená v decembri._
