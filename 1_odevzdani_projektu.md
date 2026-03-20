# 1. Průběžné odevzdání projektu: Polo-automatizovaný systém pro pěstování hub

**Autoři:** Radek Dvořák, Lunga Tomáš, Michenka Adam, Phamová Thi Phuong Mai, Kopecký Patrik

**Tým:** Ctrl+Grow   
**Datum:** 20.03.2026

---

## Představení projektu

Projekt se zaměřuje na návrh a verifikaci polo-automatizovaného systému pro pěstování hub, určeného primárně pro sektor malých a středních podniků (SME) a drobné živnostníky. Vzhledem k restrikcím v oblasti časových a materiálních zdrojů je realizace v této fázi koncipována výhradně jako **Minimum Viable Product (MVP) a dvouměsíční pilotní projekt**, nikoliv jako komerční zavedení produktu zahrnující plošné škálování či franšízový model.

**Hlavní cíle projektu:**
- Návrh a sestavení plně funkčního MVP systému.
- Verifikace technické a biologické proveditelnosti.
- Vypracování výchozího obchodního (business) modelu.
- Experimentální testování řešení v laboratorním či pilotním provozu.
- Formulace podložených doporučení pro navazující fáze rozvoje.

Cílovým tržním segmentem jsou firmy a podnikatelé, kterým má implementace tohoto systému snížit technologické a ekonomické bariéry pro vstup do oblasti komerčního pěstování hub.

## Trojimperativ projektu

Trojimperativ (projektový trojúhelník) definuje základní omezení projektu v rovině rozsahu, času a nákladů při dodržení definovaných standardů kvality.

* **Rozsah (Scope):** Návrh, kompletace a zprovoznění pilotní verze (MVP) polo-automatizovaného pěstebního systému. Součástí výstupu je technologický vývoj, biologické ověření, základní ekonomický model a závěrečné vyhodnocení dosažených parametrů. Komerční nasazení u většího počtu klientů a tržní škálování nejsou předmětem této projektové fáze.
* **Čas (Time):** Projektový rámec je stanoven na **2 měsíce (8 týdnů)**. Harmonogram inherentně zohledňuje restrikce plynoucí z biologického cyklu hub v logické návaznosti na technologické testování.
* **Náklady (Cost):** Předpokládaný rozpočet projektu pro fázi vývoje a testování MVP činí **1 200 000 Kč**. Tento rozpočet vychází z běžných tržních cen za vývoj podobného IT/HW řešení a můžeme ho rozdělit do tří hlavních částí:
    * **Personální náklady (1 000 000 Kč):** Práce pětičlenného týmu (role viz sekce 4) po dobu osmi týdnů. Částku jsme odhadli na základě průměrného nákladu zhruba 100 000 Kč (včetně odvodů firmou) na jednoho vývojáře/specialistu za měsíc.
    * **Hardware a elektronika (100 000 Kč):** Nákup senzorů, mikrokontrolérů a další elektroniky nezbytné pro fungování automatizace. V rozpočtu počítáme s trošku dražšími součástkami kvůli extrémní vlhkosti u hub.
    * **Materiál a provoz (100 000 Kč):** Peníze na nákup konstrukčního a izolačního materiálu pro sestavení testovací komory, pořízení substrátu a sadby hub a zaplacení elektřiny během dvouměsíčního pilotu u zákazníka.

## Harmonogram prací

Pro dodržení dvouměsíčního horizontu je projektový plán rozvržen do následujících osmi týdnů:

| Týden | Klíčová oblast a náplň práce |
|---|---|
| **1.** | Definice rozsahu MVP, přiřazení rolí, identifikace rizik, volba pěstebního scénáře |
| **2.** | Specifikace biologických a technických požadavků, architektura řešení, definice komponent |
| **3.** | Akvizice komponent, návrh automatizační logiky, příprava testovacího prostředí |
| **4.** | Kompletace testovacího prototypu, výchozí konfigurace, první iterace interních testů |
| **5.** | Kalibrace regulačního systému, biologická validace podmínek, tvorba provozních checklistů |
| **6.** | Pilotní nasazení, monitoring anomálií a incidentů, korekce chyb, aktualizace finančního modelu |
| **7.** | Aplikace revizních úprav, kompletace provozní dokumentace, příprava závěrečné prezentace |
| **8.** | Závěrečné vyhodnocení, souhrnná zpráva o rizicích, formulace doporučení pro následný rozvoj |

## Přidělení rolí v projektovém týmu

Pro zajištění efektivity řízení a jasného vymezení procesních odpovědností je uplatněn následující rámec projektových rolí:

* **PM (Project Manager):** Zastřešení celého projektu, kontrola definovaného rozsahu, řízení milníků, formální prezentace a komunikace.
* **TECH (Technik / Architekt):** Návrh celkové technické infrastruktury, integrace komponent, konstrukce prototypu, testování spolehlivosti a krizový management poruchových stavů.
* **BIO (Biolog / Specialista profilu):** Stanovení biologických limitů, kontinuální verifikace pěstebních podmínek (teplotní gradient, vlhkostní křivky, ventilace, mikrobiální hygiena).
* **FIN (Finanční analytik):** Kvantifikace nákladů pilotní fáze, formulace uceleného business modelu a predikce klíčových ekonomických rizik.
* **OPS (Provoz / Implementace):** Specifikace provozních predikátů, fyzická instalace systému, návrh servisní podpory, tvorba předávacích protokolů a koordinace pilotního nasazení.

Kopecký Patrik – PM  
Michenka Adam – TECH  
Dvořák Radek – BIO  
Phamová Thi Phuong Mai – FIN  
Lunga Tomáš – OPS  

## RACI matice

Níže uvedená matice definuje míru zapojení jednotlivých rolí v oblastech projektového řízení.  
*(Legenda: **R** = Responsible/Zpracovatel, **A** = Accountable/Odpovědný schvalovatel, **C** = Consulted/Konzultován, **I** = Informed/Informován)*

| Projektová aktivita a milníky | PM | TECH | BIO | FIN | OPS |
|---|:---:|:---:|:---:|:---:|:---:|
| Definice cílů a reálného rozsahu MVP | A | R | C | C | C |
| Sestavení harmonogramu a milníků | A | R | I | I | I |
| Identifikace stakeholderů a analýza rizik | A | C | C | C | R |
| Stanovení biologických limitů a požadavků| C | C | R | I | A |
| Volba typu hub a pěstebního paradigmatu | I | C | R | I | A |
| Návrh technologické architektury a struktury| C | R | C | I | A |
| Výběr HW specifikací a senzorické logiky | I | R | C | C | A |
| Kompletace a konfigurace prototypu | I | R | C | I | A |
| Zátěžové testování a modelování poruch | C | R | C | I | A |
| Verifikace biologické vhodnosti prostředí | I | C | R | I | A |
| Formulace instalačního a provozního protokolu | A | C | C | I | R |
| Sestavení odhadu financí a obchodního modelu| C | C | I | R | A |
| Fyzické pilotní ověření řešení v terénu | C | R | C | I | A |
| Závěrečné vyhodnocení a formální odevzdání | A | R | C | C | C |

## Stakeholdeři a analýza angažovanosti

Níže je uvedena identifikace klíčových subjektů, skupin a organizací participujících z pozice projektu, či dotčených průběhem jeho implementace.

### Interní stakeholdeři

| Stakeholder / Role | Hladina vlivu | Klíčová očekávání a zájem |
|---|---|---|
| **Projektový tým (PM, TECH, BIO, FIN, OPS)** | Vysoký | Včasná realizace projektu a dodání kvalitního výstupu (MVP). Zajištění pozitivní klasifikace a empirická verifikace proveditelnosti. |
| **Vedoucí předmětu / hodnotitel** | Vysoký | Odborně fundovaný projektový výstup, který reflektuje akademické standardy osnov. Důraz na systematickou přípravu, identifikaci rizik, aplikaci nástrojů (RACI) a přítomnost řídicí dokumentace. |

### Externí stakeholdeři

| Stakeholder / Subjekt | Hladina vlivu | Klíčová očekávání a zájem |
|---|---|---|
| **Pilotní zákazník** | Vysoký | Implementace spolehlivého MVP v domluveném termínu, uživatelská nenáročnost pěstebního cyklu a dostupnost profesionální technické garance v pilotu. |
| **Regulační a hygienické orgány** | Vysoký | Bezpodmínečné dodržení platných hygienických, bezpečnostních a fytosanitárních předpisů nezbytných pro potravinářský provoz. |
| **Drobní podnikatelé a firmy (SME)** | Střední | Validace cílových parametrů MVP k objektivní minimalizaci bariér vstupu do odvětví v budoucnu a zajištění prokazatelné návratnosti investice. |
| **Dodavatelé sadby a substrátu** | Střední | Udržení stabilních dodavatelských partnerství s plošnou garancí profesionální péče o inokulované objemy a substráty. |
| **Dodavatelé automatizace a HW logiky**| Střední | Transparentnost akvizičních procesů, jednoznačná technická definice prvků zakázky a korektní plnění objemových závazků. |
| **Koncoví odběratelé hub na trhu** | Střední | Konzistentní produkce standardizované senzorické kvality prostá mikrobiálních a fytosanitárních anomálií s garantovanou úrovní nezávadnosti. |
| **Servisní organizace** | Nízký | Zpracování sofistikované a instruktážně-přehledné technické dokumentace pro eventualitu systémové diagnostiky a údržby. |
