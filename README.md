# **Sve zadaće iz predmeta Poslovna Inteligencija** 

## Zadaća 1
Ispod je data šema baze podataka za prodaju i upravljanje resursima.

![Screenshot 2025-02-19 233404](https://github.com/user-attachments/assets/4250542f-da93-42d1-9f60-1ae628a30294)

1. Napisati pet poslovnih zahtjeva u vidu pitanja koje je potrebno odgovoriti.
2. Za svako pitanje napisati kratko obrazloženje šta se može saznati iz
navedenog pitanja i na koji način takve informacije mogu uticati na donošenje
neke odluke.
3. Navesti koje tabele su potrebne za zadane informacije i za svako pitanje
navesti koje tabele je potrebno povezati i kako se povežu da bi se dobile
tražene informacije.
4. Dizajnirati erd šemu za zvjezda šemu koja može odgovoriti na tražena pitanja.

## Zadaća 2
1. Koristeći generatedata.com generisati tabelu sa podacima prema datim
postavkama.
2. Učitati tabelu u proizvoljnu bazu podataka.
3. Napraviti izmjene tabele koristeći skriptu Vjezba2Izmjene.sql (u slučaju druge
baze koja nije SqlServer napraviti analogne izmjene).
4. Koristeći datum iz tabele kreirati vremensku dimenziju i njene hijerarhije.
5. Kreirati posebnu tabelu koja predstavlja olap kocku nad datom tabelom sa sve
tri dimenzije i svim hijerarhijama za mjeru M1,M2 i MPostotak i Count.

## Zadaća 3
Nad bazom AdventureWorks(AW) datoj u prilogu vježbi ILI nad bazom sa šemom
sales history (SH) postavljenoj u Oracle live izvršiti sljedeće smislene analize. Za
svaki upit napisati kratko obrazloženje, SQL kod upita i priložiti sliku rezultata upita.
1. Slice nad tabelom FactInternetSales(AW) ili Sales(SH)
2. Dice nad tabelom FactFinance(AW) ili Profits(SH)
3. ROLLUP nad tabelom FactResellerSales(AW) ili Costs(SH)
4. CUBE nad tabelom FactResellerSales(AW) ili Profits(SH)
5. GROUP SET nad tabelom FactResellerSales(AW) ili Costs(SH)
6. PIVOT nad tabelom FactFinance(AW) po godinama ili Sales(SH) po
godinama.

## Zadaća 4
Nad kockom AdventureWorks datoj u prilogu vježbi obaviti MDX analize. Za svaki
upit napisati kratko obrazloženje, MDX kod upita i priložiti sliku rezultata upita. Nije
dozvoljeno kopirati identičan upit sa prezentacije i ponuditi ga u takvoj formi kao
jedan od upita.
1. SLICE nad mjerom [Resseler Gross Profit] prikazanu po dvije proizvoljne
dimenzije i proizvoljnom trećom dimenzijom za slice bez null vrijednosti.
2. Dice nad proizvoljnom mjerom i proizvoljnom dimenzijom za godine 2011,
2012 i 2013.
3. PIVOT nad defaultnom mjerom, po dvije proizvoljne dimenzije.
4. Analiza sa izračunatom mjerom od Discount percentage i jednom ili više
drugih mjera, po jednoj proizvoljnoj dimenziji.
5. Analizu koristeći RANGE u rasponu od 2010 do 2014 prikazati proizvoljnu
mjeru po proizvoljnoj dimenziji.
6. Analiza koristeći HAVING sa proizvoljnom mjerom i lokacijskom dimenzijom.
7. DRILL-Down analiza sa proizvoljnom mjerom i dimenzijom koja nije
vremenska dimenzija.
8. Podupit sa TOP analizom nad mjerom [Reseller order quantity].

## Zadaća 5
Nad sample podacima iz PowerBi napraviti sljedeće vizuelizacije. Sve vizuelizacije
priložiti u jednom Power BI projektu i na mail poslati PDF izvještaj i PowerBI
projekat. U izvještaju je potrebno uzeti screenshot svake od vizuelizacija i obrazložiti
vizuelizaciju. Za vizuelizaciju pod tačkom 1 je potrebno priložiti sliku prije i poslije drill
down operacije.
1. Chart vizuelizaciju sa drill down mogućnošću, sa pie ili donut ili treemap
vizuelizacijom sa 3 slicera.
2. Chart vizuelizaciju koja na sebi ima i line.
3. Vizuelizaciju mape sa državama i jednim slicerom.
4. KPI vizuelizacija gdje je potrebno odrediti referentnu vrijednost.
5. Importovati jednu proizvoljnu custom vizuelizaciju i primijeniti je nad
podacima.

## Zadaća 6
1. Koristeći generatedata.com generisati tabelu sa podacima prema datim
postavkama.
2. Učitati tabelu u proizvoljnu bazu podataka.
3. Generisati ponovo CSV i 3 puta JSON datoteku sa istim kolonama.
4. Koristeći generate rows generisati još jednu dodatnu tabelu sa istim
kolonama.
5. Potrebno je spojiti podatke svih izvora u jednu tabelu činjenica (pri čemu je za
JSON datoteke potrebno koristiti GetFileNames).
6. Sve generisane datoteke koriste First tabelu vezanu za Proizvod preko id a
CSV koristi Second tabelu koju ćete kreirati preko Data Grid ulaza.
7. Rezultat svih predhodnih tačaka spojenih u jednu fact tabelu treba upisati u
CSV datoteku.

## Zadaća 7
Data je šema relacione baze podataka. Potrebno je koristeći apache hop generisati
sve tabele i njihove sadržaje kao jedan pipeline.

![Screenshot 2025-02-19 232846](https://github.com/user-attachments/assets/86d4873a-8f7f-423e-9740-3fd2f9fd76b6)

Drugi pipeline treba da sve tabele i podatke prebaci u star šemu datu na sljedećoj
slici. Zarada se računa po dužini trajanja gledanja filma puta cijena po minuti, a
gubici kao cijena licence po gledanju filma. Zatim je potrebno napraviti workflow koji
prvo pokreće pipeline za generisanje a zatim pipeline za transformacije. Koristiti
varijable za workflow konfiguraciju da li se radi generisanje ili transformacija. Dva
pipeline i workflow trebaju biti u sklopu jednog projekta.

## Zadaća 8
Koristeći rapidminer primijeniti detekciju outlier na sample skupu podataka iz
rapidminera koji nije wine dataset. U izvještaju je potrebno priložiti screenshot i
obrazloženje za:
1. Početni skup podataka.
2. Tabelu sa detektovanih 10 outlier vrijednosti.
3. Vizualizaciju outlier vrijednosti

## Zadaća 9
Koristeći rapidminer nad skupom podataka iz predhodne vježbe proglasiti jednu
kolonu za outlier vrijednosti kao null i obaviti čišćenje podataka. U izvještaju je
potrebno priložiti screenshot i obrazloženje za:
1. Početni skup podataka.
2. Tabelu sa null vrijednostima
3. Pipeline i odabrani metod čišćenja (ne može ignore missing values)
4. Tabelu sa zamijenjenim očišćenim vrijednostima

## Zadaća 10
Koristeći GoogleBigQuery nad jednim od sample skupom podataka obaviti 3
proizvoljna upita. Za svaki upit je potrebno:
1. Objasniti koji su podaci i cilj upita
2. Priložiti screenshot upita
3. Priložiti screenshot rezultata
4. Priložiti screenshot vizualizacije rezultata upita

## Zadaća 11
Nad sample skupom podataka iz rapidminer koji nije potrošačka korpa ili iris dataset
kreirati asocijativna pravila. U izvještaju je potrebno prikazati sliku i obrazložiti sliku
za:
1. Screenshot rapidminer projekta.
2. Primjer skupa podataka
3. Primjer kreiranih asocijativnih pravila.
4. Vizuelizaciju asocijativnih pravila.
5. Skup podataka sa podrškom i pouzdanošću

## Zadaća 12
Nad sample skupom podataka iz rapidminer koji nije golf ili iris dataset kreirati dva
stabla odlučivanja i uporediti rezultate. U izvještaju je potrebno prikazati sliku i
obrazložiti sliku za:
1. Screenshot rapidminer projekta.
2. Primjer skupa podataka
3. Primjer oba kreirana stabla odlučivanja.
4. Prikazane predikcije za isti dataset za jedno i drugo stablo.

## Zadaća 13
Nad sample skupom podataka iz rapidminer koji nije polynomial dataset napraviti i
primijeniti model linearne regresije. U izvještaju je potrebno prikazati sliku i
obrazložiti sliku za:
1. Screenshot rapidminer projekta.
2. Primjer skupa podataka
3. Rezultat modela linearne regresije
4. Rezultat testnog skupa podataka

## Zadaća 14
Uraditi cross validaciju za jednu od predhodnih zadaća 11, 12, 13 za predikcijske
modele.
1. Screenshot rapidminer projekta.
2. Screenshot rezultata cross validacije
3. Obrazloženje rezultata

## Zadaća 15
Za dataset iz vježbe napraviti primjer teksta koji će biti označen kao pozitivan i jedan
primjer koji će biti označen kao negativan. Zatim izmijeniti podatke tako da za riječ
“POZITIVA” daje predikciju da je pozitivan komentar a za riječ “NEGATIVA” da je
negativan komentar.
