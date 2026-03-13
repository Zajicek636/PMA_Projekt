# Rozpad tasků, RACI matice a stakeholder analýza

## Shrnutí

Projekt je zaměřen na **polo-automatizovaný systém pro pěstování hub** pro malé firmy a malé podnikatele. Ze zdrojů vyplývá, že původní plán počítal s horizontem **20+ měsíců**, ale pro potřeby tohoto dokumentu je projekt přeplánován do **2 měsíců** jako **MVP / pilotní varianta**, nikoli plné uvedení na trh včetně škálování a franšízového modelu.

## Co víme ze zdrojů

- Téma: systém pro pěstování hub.
- Charakter řešení: polo-automatizovaný systém.
- Cílový trh: malé firmy a malí podnikatelé.
- Původní harmonogram: výzkum, vývoj, pilot, franšíza a škálování přes 20 měsíců.
- Hlavní rizika:
  - lidský faktor a biologický cyklus hub,
  - finanční rizika: podhodnocení zdrojů, nízká marže, vysoké náklady na vývoj, dlouhá doba do prvního příjmu,
  - časová rizika: delší příprava prostor, pomalé hledání zákazníků,
  - technická rizika: selhání klimatizace, výpadek elektřiny, plísně a škůdci, nevhodně nastavená automatizace, různorodé prostředí u zákazníků.

## Co není jasné

- Ve zdrojích není popsán konkrétní rozsah MVP.
- Není určeno, kdo z uvedených členů týmu zastává kterou roli.
- Není definován rozpočet.
- Není potvrzen konkrétní pilotní zákazník.

Proto jsou níže uvedené role, scope a stakeholdery **návrh** pro řízení projektu v semestrálním zadání.

## Doporučený rámec projektu na 2 měsíce

Pro dvouměsíční realizaci doporučuji neplánovat plné komerční uvedení na trh. Reálným cílem je:

- navrhnout a sestavit funkční MVP systému,
- ověřit biologickou a technickou proveditelnost,
- připravit základ business modelu,
- provést pilotní nasazení nebo laboratorní ověření,
- připravit podklady pro další fázi projektu.

## Rozpad tasků (WBS)

### 1. Řízení projektu

1.1 Definice cíle MVP, rozsahu a kritérií úspěchu  
1.2 Nastavení rolí, odpovědností a komunikačního režimu  
1.3 Vytvoření harmonogramu na 8 týdnů  
1.4 Evidence rizik a pravidelný status reporting  
1.5 Kontrola milníků a závěrečné vyhodnocení

### 2. Produktový a biologický návrh

2.1 Definice cílového typu hub a pěstebního cyklu  
2.2 Stanovení biologických požadavků na teplotu, vlhkost, ventilaci a hygienu  
2.3 Návrh provozního konceptu systému  
2.4 Návrh minimálního rozsahu automatizace  
2.5 Definice provozních limitů a kritických bodů

### 3. Technický vývoj MVP

3.1 Návrh architektury řešení  
3.2 Výběr komponent hardware a senzoriky  
3.3 Návrh řídicí logiky a automatizačních pravidel  
3.4 Sestavení prototypu  
3.5 Oživení zařízení a základní software / firmware konfigurace  
3.6 Test bezpečnosti, stability a reakce na poruchové stavy

### 4. Testování a pilot

4.1 Příprava testovacího prostředí  
4.2 Ověření funkce měření a regulace  
4.3 Ověření biologické vhodnosti podmínek  
4.4 Záznam odchylek, chyb a provozních incidentů  
4.5 Návrh úprav po pilotu

### 5. Finance a business model

5.1 Odhad nákladů na MVP a pilot  
5.2 Odhad jednotkových nákladů budoucího řešení  
5.3 Návrh hodnotové nabídky pro malé zákazníky  
5.4 Návrh cenové logiky a základního business modelu  
5.5 Vyhodnocení ekonomických rizik

### 6. Provoz a implementace

6.1 Návrh požadavků na prostor u zákazníka  
6.2 Návrh instalačního a provozního postupu  
6.3 Návrh servisního modelu a základní podpory  
6.4 Návrh provozní dokumentace a checklistů  
6.5 Příprava předávacího balíčku pro pilot

### 7. Výstupy projektu

7.1 Závěrečný souhrn MVP a výsledků testu  
7.2 RACI, stakeholder mapa a registr rizik  
7.3 Prezentace projektu  
7.4 Doporučení pro další fázi po skončení 2měsíčního pilotu

## Návrh harmonogramu na 8 týdnů

### Týden 1

- potvrzení scope MVP,
- rozdělení rolí,
- definice rizik,
- výběr pěstebního scénáře.

### Týden 2

- biologické a technické požadavky,
- návrh architektury,
- seznam komponent,
- první verze business modelu.

### Týden 3

- nákup / zajištění komponent,
- návrh automatizace,
- příprava testovacího prostředí,
- návrh provozních podmínek.

### Týden 4

- sestavení prototypu,
- základní konfigurace,
- první interní testy,
- průběžná revize nákladů.

### Týden 5

- ladění regulace,
- biologické ověření podmínek,
- doplnění provozních checklistů,
- příprava pilotního scénáře.

### Týden 6

- pilotní ověření,
- záznam incidentů,
- návrh korekcí,
- aktualizace ekonomického modelu.

### Týden 7

- zapracování úprav,
- finalizace provozní dokumentace,
- stakeholder komunikace,
- příprava prezentace.

### Týden 8

- závěrečné vyhodnocení,
- shrnutí rizik,
- doporučení další fáze,
- odevzdání výstupů.

## RACI matice

Legenda:

- R = Responsible
- A = Accountable
- C = Consulted
- I = Informed

| Aktivita | PM | TECH | BIO | FIN | OPS |
|---|---|---|---|---|---|
| Definice scope MVP a cílů | A | R | C | C | C |
| Vytvoření harmonogramu a milníků | A | R | I | I | I |
| Řízení rizik projektu | A | C | C | C | R |
| Definice biologických požadavků | C | C | R | I | A |
| Výběr typu hub a pěstebního režimu | I | C | R | I | A |
| Návrh technické architektury | C | R | C | I | A |
| Výběr HW, senzorů a automatizace | I | R | C | C | A |
| Sestavení a konfigurace prototypu | I | R | C | I | A |
| Ověření biologické vhodnosti podmínek | I | C | R | I | A |
| Testování stability a poruchových stavů | C | R | C | I | A |
| Návrh požadavků na instalaci u zákazníka | C | C | C | I | R |
| Návrh provozních checklistů a servisu | I | C | C | I | R |
| Odhad nákladů a business model | C | C | I | R | A |
| Vyhodnocení ekonomických rizik | C | I | I | R | A |
| Pilotní nasazení / pilotní ověření | C | R | C | I | A |
| Závěrečné vyhodnocení projektu | A | R | C | C | C |
| Prezentace a odevzdání výstupů | A | R | C | C | C |

## Stakeholdeři

Níže je návrh stakeholderů, protože ve zdrojích nejsou explicitně vypsáni.

### Interní stakeholdeři

| Stakeholder | Typ | Zájem | Vliv | Očekávání |
|---|---|---|---|---|
| Projektový tým | interní | úspěšné dokončení semestrálního projektu a funkční MVP | vysoký | jasné role, termíny, rozhodování |
| PM | interní | dodržení času, koordinace a kvality výstupů | vysoký | dostupnost informací, spolupráce týmu |
| TECH | interní | funkční a stabilní technické řešení | vysoký | realistický scope, dostupné komponenty |
| BIO | interní | správné pěstební podmínky a biologická proveditelnost | vysoký | respektování biologických limitů |
| FIN | interní | ekonomická smysluplnost a odhad návratnosti | střední až vysoký | data o nákladech a variantách výnosů |
| OPS | interní | provozovatelnost a implementovatelnost u zákazníka | vysoký | jednoduchá instalace a servis |
| Vedoucí předmětu / hodnotitel | interní | kvalitní projektový výstup podle zadání kurzu | vysoký | strukturovaný dokument, RACI, harmonogram, rizika |

### Externí stakeholdeři

| Stakeholder | Typ | Zájem | Vliv | Očekávání |
|---|---|---|---|---|
| Pilotní zákazník | externí | levné a použitelné řešení pro pěstování hub | vysoký | jednoduchý provoz, funkčnost, základní podpora |
| Budoucí zákazníci z řad malých firem | externí | snížení bariéry vstupu do pěstování hub | střední | rozumná cena, spolehlivost, návratnost |
| Dodavatelé technologií a komponent | externí | prodej komponent a případná servisní spolupráce | střední | jasná specifikace a objednávky |
| Dodavatelé substrátu / sadby / biologického materiálu | externí | stabilní odběr a správné zacházení s materiálem | střední | správné podmínky pěstování a plán odběru |
| Odběratelé hub | externí | stabilní kvalita a objem produkce | střední | hygienická a kvalitativní stabilita |
| Servisní partneři | externí | možnost technické podpory a oprav | nízký až střední | standardizované řešení a dokumentace |
| Regulační a hygienické autority | externí | dodržení hygienických a provozních pravidel | vysoký | bezpečný provoz a dokumentované postupy |
| Pojišťovna | externí | omezení provozních a odpovědnostních rizik | nízký až střední | technická a provozní opatření |

## Doporučení ke stakeholder managementu

- **Řídit úzce**: projektový tým, PM, TECH, BIO, OPS, vedoucí předmětu, pilotní zákazník.
- **Udržovat spokojené**: FIN, regulační a hygienické autority.
- **Průběžně konzultovat**: dodavatelé komponent a biologického materiálu.
- **Průběžně informovat**: budoucí zákazníci, odběratelé hub, servisní partneři.

## Kritické poznámky

- Požadavek realizace celého projektu do 2 měsíců je realistický pouze pro **MVP / pilotní verzi**.
- Pokud by měl projekt skutečně zahrnovat plné uvedení na trh, ověření obchodního modelu, zákaznické implementace a škálování, je dvouměsíční termín podle dostupných zdrojů nereálný.
- Největší tlak bude na sladění biologického cyklu hub s tempem technického vývoje a testování.

## Doporučení

Pro semestrální projekt doporučuji oficiálně vymezit rozsah jako:

- návrh a realizace MVP,
- laboratorní nebo omezený pilot,
- ekonomický model v hrubých obrysech,
- plán další fáze po skončení 2 měsíců.

Tím zůstane projekt časově obhajitelný a zároveň bude odpovídat rizikům i zdrojům uvedeným v podkladech.
