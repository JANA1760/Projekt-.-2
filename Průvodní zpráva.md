# Projekt-.-2

Průvodní zpráva k projektu č. 2
Vstup:
V rámci zadání projektu jsem zvolila volně přístupná data z ČSÚ k evidenci ekonomických subjektů.

Zadání:
•	rozsah 2-5 stránek
•	použití minimálně 5 různých typů vizuálů,
•	filtrování (primárně) pomocí průřezů/slicerů
•	využití interaktivních prvků jako jsou záložky, tlačítka navigátory
•	navigace po stranách, 
•	odkazy na webové stránky, ...
•	propojení několika (2+) datových tabulek, buď přes vazby v rámci Power BI nebo přes propojení v Power Query
•	použití vytvořené hierarchie o alespoň dvou úrovních (nepovinné)
•	vytvoření alespoň 1 measure (metrika/míra) a 1 kalkulovaného sloupce/tabulky

Grafická úprava použitých vizuálů, zvolení správných typů vizuálů a vizuálně přívětivý výsledný report.

Úvod:
V rámci zadání projektu jsem zvolila volně přístupná data z ČSÚ k evidenci ekonomických subjektů. Zpracovala jsem analýzu dynamiky vývoje počtu ekonomických subjektů v letech 2017 – 2024.  Zdrojová data byla stažena ve formátu xls. Jednalo se o následující tabulky:
•	Vznik a zánik ekonomických subjektů,
•	Registrace ekonomických subjektů podle činnosti.

V programu dax byla vytvořena Kalendářová tabulka s jednotným časovým formátem.  Na tuto tabulku byly navázána zdrojová data i nově vytvořená tabulka v Power query Obory činnosti – dlouhý formát, kterou jsem vytvořila duplikováním tabulky Registrace ekonomických subjektů podle činnosti a následně transponovala do dlouhého formátu. Všechny relace jsou 1:N.

Metodika analýzy:
Byla provedena:
1)	analýza vývoje podnikatelského prostředí co do počtu vzniku a zániku ekonomických subjektů ve vazbě na rozlišení právnická/fyzická osoba, současně byly znázorněny i trendy vývoje.
2)	Trendová a poměrová analýza vývoje přírůstku ekonomických subjektů v jednotlivých letech a oborech s vyjádřením absolutního počtu a procentického podílu formou výsečového grafu.
3)	 Oborová analýza vývoje přírůstku s vyjádřením charakteristik úrovně (průměr, minimum, maximum) v jednotlivých letech
Celý projekt obsahuje 1 úvodní stranu a 3 strany s vizuálními elementy. Celkem byly použity následující typy vizuálů – skupinový sloupcový, spojnicový, výsečový, skládaný plošný, matice, karta nová, skládaný sloupcový. 

K filtrování jsem připravila průřez přes tlačítka – roky, činnosti.
Mezi jednotlivými stranami lze listovat pomocí šipek. Navigátor stránek je na úvodní straně. Tlačítka na přepínání jsou na straně č. 1.

V daxu bylo vytvořeno 8 nových měr, které jsou zvizualizované formou výsečového grafu ve formátu procento.

Výsledky:
1)	V letech 2017 – 2024 počet vzniklých ekonomických subjektů převyšoval počet zaniklých ekonomických subjektů, s vyjimkou roku 2023, kde byl vlivem zvýšeného počtu zániku fyzických osob zaznamenán propad.  Nárůst počtu subjektů – fyzických osob byl v řádu vyšších desetitisíců, nárůst počtu právnických osob je v řádu nižších desetitisíců. 

2)	Úroveň vývoje nově vzniklých subjektů byla v letech stabilní, bez výkyvů, s lehkým vzestupným trendem v posledních 3 letech. V letech 2019 a 2020 byl mírný propad nárůstu vzhledem k rokům předchozím i následujícím. Největší podíl nově vzniklých ekonomických subjektů je v oboru finančních služeb a v oboru osobních služeb. Na třetí pozici se v letech 2022 – 2024 co počtu nových subjektů dostal sektor stavební. 

3)	Největší progres ve vývoji co do počtu nových subjektů zaznamenala oblast logistiky – doprava a skladování, zde byl nárůst v průběhu všech zmiňovaných roků. Dalšími progresivními obory byla oblast průmyslu a oblast stavebnictví. Obory IKT zaznamenaly mírný progresivní trend. Obory jako finanční služby, gastro zaznamenaly v letech 2019, 2020 propad, postupně dochází ke srovnání s úrovní v letech 2018, 2019. Osobní služby mají v posledních 5 letech stabilní úroveň přírůstku. Oblast obchodu zaznamenala výrazný propad.

       


