# Bodování řidičů v krajích ČR – Power BI projekt

## O projektu

Tento projekt vznikl v rámci studia na Engeto Academy v kurzu **Datový analytik s Pythonem**.

Cílem bylo vytvořit interaktivní dashboard v Power BI, který vizualizuje a analyzuje data o bodovaných řidičích v Českých krajích a obcích. Uživatel má možnost filtrovat dle pohlaví, regionu, zákazu řízení a typu bodů a zobrazit podíl bodovaných řidičů v jednotlivých částech republiky.

Projekt vychází z otevřených dat Ministerstva dopravy a reflektuje stav k 1. čtvrtletí roku 2025.

## Použité datové zdroje

- [Bodovaní řidiči dle obcí a pohlaví (data.gov.cz)](https://data.gov.cz/datov%C3%A1-sada?iri=https%3A%2F%2Fdata.gov.cz%2Fzdroj%2Fdatov%C3%A9-sady%2F66003008%2F1471764192)
- [Číselníky území (data.gov.cz)](https://data.gov.cz/dataset?iri=https%3A%2F%2Fdata.gov.cz%2Fzdroj%2Fdatov%C3%A9-sady%2F00025593%2F0e136cf01f86f9446b7334c2e4f011bd)
- Topologická mapa krajů

## Funkce a prvky dashboardu

- **Rozsah**: 3 stránky dashboardu
- **Typy vizuálů**: sloupcové grafy, mapy, koláčové grafy, matice, karty
- **Slicery**: pohlaví, kraj, město, stav bodů, zákaz řízení
- **Bookmarks & navigace mezi stránkami**
- **Measure**: např. `% bodovaných řidičů`, `Pořadí obcí dle rizikovosti`
- **Kalkulovaný sloupec**: např. `Kategorie bodů`
- **Datová hierarchie**: Kraj → Obec

## Spuštění

Pro spuštění stačí otevřít soubor `Bodovani_ridicu.pbix` v Power BI Desktop (doporučena aktuální verze).

## Kontakt

📧 [romanabelohoubkova@gmail.com](mailto:romanabelohoubkova@gmail.com)  
💬 Discord: romana_belohoubkova
