# 1. Průběžné odevzdání projektu: Polo-automatizovaný systém pro pěstování hub

**Autoři:** Radek Dvořák, Lunga Tomáš, Michenka Adam, Phamová Thi Phuong Mai, Kopecký Patrik

**Tým:** Ctrl+Grow   
**Datum:** 20.03.2026

---

## Představení projektu

Projekt se zaměřuje na návrh a ověření polo-automatizovaného systému pro pěstování hub, určeného primárně pro malé firmy a drobné podnikatele. Z důvodu časových a zdrojových omezení je aktuální realizace cílena jako **MVP (Minimum Viable Product) a pilotní projekt na 2 měsíce**, nikoliv jako plné komerční uvedení na trh včetně plného škálování a franšízového modelu.

**Hlavní cíle projektu:**
- Navrhnout a sestavit funkční MVP systému.
- Ověřit technickou a biologickou proveditelnost.
- Připravit základní business model.
- Otestovat řešení v pilotním nebo laboratorním režimu.
- Předat doporučení pro další fázi rozvoje.

Cílovým trhem jsou malé firmy a podnikatelé, kterým má systém dlouhodobě snížit bariéru vstupu do komerčního pěstování hub.

## Trojimperativ projektu

* **Rozsah (Scope):** Navržení, sestavení a zprovoznění funkčního MVP (Minimum Viable Product) polo-automatizovaného pěstebního systému. Zahrnuje technologický vývoj MVP, biologické ověření, základní ekonomický model a závěrečné vyhodnocení parametrů. Škálování a komerční nasazení u většího počtu zákazníků není do aktuálního scope zahrnuto (out of scope).
* **Čas (Time):** Projekt je naplánován na **2 měsíce (8 týdnů)**. Harmonogram je nastaven tak, aby zohledňoval sladění biologického cyklu hub s fázemi technologického testování.
* **Náklady (Cost):** [Doplňte odhadovaný rozpočet / finanční rámec týmu, jelikož ve zdrojové dokumentaci není výslovně definován přesný rozpočet]. Reálně zahrnuje náklady na HW komponenty, senzory a vývoj prototypu pro pilotní otestování.

## Hrubý časový odhad (Harmonogram)

| Týden | Fokus a hlavní pracovní náplň |
|---|---|
| **1.** | Scope MVP, přidělení rolí, identifikace rizik, výběr pěstebního scénáře |
| **2.** | Biologické a technické požadavky, architektura řešení, výběr a specifikace komponent |
| **3.** | Zajištění komponent, návrh automatizace, příprava testovacího prostředí |
| **4.** | Sestavení testovacího prototypu, počáteční konfigurace, první interní testy |
| **5.** | Ladění regulace systému, biologické ověření vhodnosti podmínek, návrh checklistů |
| **6.** | Pilotní ověření, záznam anomálií a incidentů, korekce chyb, aktualizace ekonomického modelu |
| **7.** | Zapracování nezbytných úprav, finalizace provozní dokumentace, příprava prezentace |
| **8.** | Závěrečné vyhodnocení, shrnutí zbývajících rizik, předložení doporučení pro další fázi |

## Přidělení rolí v projektovém týmu

K zajištění plynulého chodu a jasných procesních odpovědností za dílčí agendy je využíván následující rámec projektových rolí:

* **PM (Project Manager):** Řízení celého projektu, sledování definovaného rozsahu (scope), kontrola milníků, prezentace a finální komunikace.
* **TECH (Technik / Architekt):** Návrh celkové technické architektury, výběr komponent, sestavení prototypu, testování stability a řešení mimořádných poruchových stavů.
* **BIO (Biolog / Specialista profilu):** Definice úzkých biologických požadavků, kontrola a ověřování pěstebních podmínek (teplota, vlhkost, ventilace, hygiena).
* **FIN (Finanční analytik):** Odhad nákladů pilotu, sestavení celého business modelu a identifikace klíčových ekonomických rizik.
* **OPS (Provoz / Implementace):** Stanovení požadavků na samotný provoz, instalace řešení, servisní model řešení, provozní a předávací checklisty, pilotní nasazení u zákazníka.

Kopecký Patrik – PM  
Michenka Adam – TECH  
Dvořák Radek – BIO  
Phamová Thi Phuong Mai – FIN  
Lunga Tomáš – OPS  

## RACI matice

Níže uvedená matice definuje míru zapojení jednotlivých rolí v konkrétních projektových fázích.  
*(Legenda: **R** = Responsible/Zpracovatel, **A** = Accountable/Odpovědný schvalovatel, **C** = Consulted/Konzultován, **I** = Informed/Informován)*

| Projektová aktivita a milníky | PM | TECH | BIO | FIN | OPS |
|---|:---:|:---:|:---:|:---:|:---:|
| Definice cílů a reálného scope MVP | A | R | C | C | C |
| Vytvoření harmonogramu a milníků | A | R | I | I | I |
| Identifikace stakeholderů a řízení rizik | A | C | C | C | R |
| Definice biologických limitů a požadavků| C | C | R | I | A |
| Výběr typu hub a pěstebního režimu | I | C | R | I | A |
| Návrh technické architektury a struktury| C | R | C | I | A |
| Výběr HW specifikací, senzorů a logiky | I | R | C | C | A |
| Sestavení a konfigurace prototypu | I | R | C | I | A |
| Testování stability a poruchových stavů | C | R | C | I | A |
| Ověření biologické vhodnosti podmínek | I | C | R | I | A |
| Návrh instalačního a provozního postupu | A | C | C | I | R |
| Sestavení odhadu financí a business modelu| C | C | I | R | A |
| Fyzické pilotní ověření řešení | C | R | C | I | A |
| Závěrečné vyhodnocení a odevzdání | A | R | C | C | C |

## Stakeholdeři a analýza angažovanosti

Níže je uvedena analýza osob, skupin a organizací, které mohou být projektem ovlivněny, nebo přímo ovlivňují jeho úspěch.

### Interní stakeholdeři

| Stakeholder / Role | Hladina vlivu | Hlavní očekávání a zájem |
|---|---|---|
| **Projektový tým (PM, TECH, BIO, FIN, OPS)** | Vysoký | Úspěšné dokončení projektu na čas a v kvalitě funkčního MVP. Mají zájem o dobré hodnocení a technickou i biologickou proveditelnost. |
| **Vedoucí předmětu / hodnotitel** | Vysoký | Validní a srozumitelný projektový výstup dle standardů zadání. Správná identifikace rizik, dobrá organizace, přítomnost harmonogramu a RACI matice. |

### Externí stakeholdeři

| Stakeholder / Subjekt | Hladina vlivu | Hlavní očekávání a zájem |
|---|---|---|
| **Pilotní zákazník** | Vysoký | Včasné dodání MVP do provozu, jednoduché používání, funkčnost a případná provozní podpora po čas celého testu. |
| **Regulační a hygienické autority** | Vysoký | Striktní dodržení základních hygienických a bezpečnostních pravidel a platných předpisů pro nakládání s potravinami. |
| **Budoucí zákazníci (malé firmy)** | Střední | Dosažení slibovaných parametrů MVP, vidina zajistit si nízkou bariéru vstupu do trhu a rozumnou nákladovost (ROI). |
| **Dodavatelé substrátu / sadby** | Střední | Odběr materiálu, záchrana investic pomocí funkčního zacházení v navrženém MVP, dodržení biologických zásad. |
| **Dodavatelé celých technologií a komponent**| Střední | Transparentnost a spolehlivost objednávek, jasné specifikace a zaplacení hardwarového vybavení. |
| **Koncoví odběratelé hub** | Střední | Velmi stabilní objem dodávek hub, které nebudou poškozovat pěstební neduhy či špatná péče (vysoká jakost a hygiena). |
| **Servisní partneři** | Nízký | Připravená zevrubná technická i provozní dokumentace s jasnými diagnostikami k udržování systému. |
