# Stezka Českem - Datová analýza a Power BI Report

Tento projekt obsahuje interaktivní Power BI report určený pro turisty plánující přechod **Stezky Českem**. Report poskytuje přehled o náročnosti jednotlivých etap a umožňuje dynamické plánování tras v obou směrech.

##  Obsah repozitáře
* `Stezka_Ceskem.pbix` - Hlavní soubor s Power BI reportem a DAX metrikami.
* `Stezka_Ceskem_Data.xlsx` - Původní zdrojová data z Excelu obsahující kilometry, dny a výškové metry etap.

##  Popis Reportu
Report je rozdělen do dvou hlavních logických celků:

1. **Přehled všech etap:** Celkový katalog, kde si turista může na jedné obrazovce porovnat všechny dostupné etapy v České republice podle jejich délky a celkového převýšení. Obsahuje moderní KPI blok se souhrnnými informacemi.
2. **Plánovač trasy (Detail):** Detailní průvodce pro jednu vybranou etapu. Zobrazuje průměrnou denní náročnost kopců (při kalkulaci standardního výkonu 25 km na den).

##  Hlavní interaktivní funkce
* **Dynamický protisměr:** Report obsahuje pokročilé DAX metriky, které po stisknutí tlačítka (Tam / Protisměr) automaticky prohodí hodnoty stoupání a klesání v tabulkách i grafech podle toho, jakým směrem se turista rozhodne jít.
* **Očištěné vizuály:** Vodorovné sloupcové grafy zajišťují perfektní čitelnost dlouhých názvů etap.

##  Použité technologie
* **Microsoft Power BI Desktop**
* **DAX** (Data Analysis Expressions) pro tvorbu dynamických měr
* **Microsoft Excel** jako datový zdroj
