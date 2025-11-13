# Flight Delays, Cancellations & Environmental Factors

## Project Overview
Dit project onderzoekt hoe weersomstandigheden en luchtkwaliteit invloed hebben op vertragingen en annuleringen van vluchten.  
Hiervoor worden drie open datasets van Kaggle gecombineerd en geanalyseerd met Apache Spark.  
Het doel is om te visualiseren of afwijkende luchtkwaliteit of extreme weersomstandigheden correleren met meer vertragingen of annuleringen in het vliegverkeer.

---

## Datasets

### 1. Flight Delay & Cancellation Data (2024)
📘 **Link:** [https://www.kaggle.com/datasets/nalisha/flight-delay-and-cancellation-data-1-million-2024](https://www.kaggle.com/datasets/nalisha/flight-delay-and-cancellation-data-1-million-2024)

**Beschrijving:**  
Deze dataset bevat gegevens over vluchtvertragingen en annuleringen in 2024.  
**Belangrijke kolommen:** vluchtdatum, luchthaven (stad/land), vertraging in minuten, reden van annulering.  
Deze data toont waar en wanneer de meeste vertragingen of annuleringen plaatsvinden.

---

### 2. Urban Air Quality & Climate Dataset (1958–2025)
📘 **Link:** [https://www.kaggle.com/datasets/krishd123/urban-air-quality-and-climate-dataset-1958-2025](https://www.kaggle.com/datasets/krishd123/urban-air-quality-and-climate-dataset-1958-2025)

**Beschrijving:**  
Bevat luchtkwaliteits- en klimaatdata van stedelijke gebieden wereldwijd.  
**Belangrijke kolommen:** stadsnaam, datum, Air Quality Index (AQI), CO₂, NO₂, PM2.5, temperatuur.  
Deze dataset wordt gebruikt om te onderzoeken of luchtvervuiling of temperatuurpieken samenhangen met vluchtvertragingen.

---

### 3. Global Climate Change Indicators (2000–2024)
📘 **Link:** [https://www.kaggle.com/datasets/bhadramohit/climate-change-dataset/data](https://www.kaggle.com/datasets/bhadramohit/climate-change-dataset/data)

**Beschrijving:**  
Deze dataset bevat wereldwijde klimaatveranderingsindicatoren over meerdere jaren.  
**Belangrijke kolommen:** land, jaar, gemiddelde temperatuur, totale neerslag, extreme neerslagdagen, hittegolven.  
Wordt gebruikt om bredere klimaattrends weer te geven en hun mogelijke link met vliegverkeerstoornissen te onderzoeken.

---

## Data Processing & Analysis
De drie datasets worden samengevoegd op **locatie (stad/land)** en **tijdstip (datum/jaar)** met behulp van **Apache Spark**.  
Daarna worden visualisaties gemaakt (bijv. met PySpark, Pandas of Matplotlib) om patronen te tonen tussen:
- Luchtkwaliteit en vluchtvertragingen  
- Weersextremen en annuleringen  
- Klimaattrends op langere termijn en regionale vliegproblemen

---

## Doel
Het doel is om data-inzichten te krijgen in hoe milieu- en klimaatomstandigheden het wereldwijde vliegverkeer beïnvloeden.  
De resultaten kunnen helpen bij het voorspellen van vertragingen onder bepaalde weers- of luchtkwaliteitscondities.

---

## Auteur
**Karim Ibrahim**  
Student Toegepaste Informatica / AI  
Antwerpen, België
