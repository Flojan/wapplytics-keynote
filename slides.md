---
theme: apple-basic
class: text-left
highlighter: prism
lineNumbers: true
drawings:
  persist: false
css: windicss
fonts:
  provider: none
title: Website-Analyse-Plattform
layout: intro
hideInToc: true
routerMode: history
presenter: false
---

# Website-Analyse-Plattform
## Bachelor-Arbeit 

<div class="absolute bottom-7">
  <h2>
    Florian Schmidt // 15.02.2023
  </h2>
</div>

<Footer />


---
title: Inhalt
hideInToc: true
---

# Inhalt 
<Toc listClass="list-disc" />

<Footer />


---
title: Einführung in das Thema
hideInToc: false
---

# Einführung in das Thema

- Erfolgsmessung durch Website-Analyse-Tools
- anhand wichtigster Indikatoren können Ziele überprüft werden
- Bedürfnisse der Nutzer kennenlernen
- Datenschutz schränkt das Tracking ein
<br/>
<br/>

### Ziel der Bachelor-Arbeit

- Datenschutzfreundliche und dynamische Website-Analyse-Plattform entwickeln
- Tracking des Website-Nutzers ohne Einwilligung 
- Übersichtlichkeit und einfache Nutzung gewährleisten
<!-- https://sli.dev/guide/animations.html#click-animations -->
<Footer />


---
title: Einführung in das Thema
hideInToc: true
---

# Einführung in das Thema
## Ziel mit passenden Key Performance Indikatoren

- Analyse-Tools enthalten viele verschiedene Performance Indikatoren
- Key Performance Indikator tragen zur Zielerreichung bei 
- kontinuierliche Erfolgskontrolle
### Performance Indikatoren

<h4 class="absolute left-20 bottom-55" v-click>Seitenaufrufe</h4>
<h4 class="absolute left-60 bottom-60" v-click>Aktive Nutzer</h4>
<h4 class="absolute left-90 bottom-35" v-click>Unterschiedliche Nutzer</h4>
<h4 class="absolute left-130 bottom-50" v-click>Traffic-Quellen</h4>
<h4 class="absolute left-45 bottom-40 " v-click>Nutzerpfade</h4>
<h4 class="absolute left-160 bottom-25" v-click>Standorte</h4>
<h4 class="absolute left-170 bottom-57" v-click>Geräteinformationen</h4>
<h4 class="absolute left-100 bottom-65" v-click>Absprungrate</h4>
<h4 class="absolute left-30 bottom-20" v-click>Durchschnittliche Verweildauer</h4>
<!-- <h4 class="absolute left-105 bottom-10" v-click>Erfolgreiche Event Klicks</h4>
<h4 class="absolute left-180 bottom-40" v-click>Erfolgreiche Event Klickrate </h4> -->

<Footer/>


---
title: Einführung in das Thema
hideInToc: true
---

# Einführung in das Thema

## Einschränkungen durch den Datenschutz

- DSGVO – schützt die personenbezogenen Daten
- TTDSG – legt die Einwilligungspflicht fest
- DSGVO & TTDSG erschweren flächendeckendes Tracking
- weitverbreitetste Variante – Nutzerdaten in Cookies speichern
- ohne Einwilligung findet kein Tracking statt
- viele Browser & Adblocker blockieren Third-Party-Cookies 
- Datenschutz ist kein Problem, sondern Grundrecht der Nutzer 
<Footer />


---
title: Einführung in das Thema
hideInToc: true
---

# Einführung in das Thema
## Ab wann kann auf die Einwilligung verzichtet werden?
<br/>
<br/>

### DSGVO & TTDSG

- Einsatz von ausschließlich essentiellen Cookies
- kein Zugriff auf das Endgerät, um Identifikatoren auszulesen
- Nutzer darf nicht über längeren Zeitraum wieder erkannt werden 
- keine Identifikation über personenbezogene Daten -> 
- keine zu extremen Tracking-Methoden 
- Datenverarbeitung und -transfer nur in Ländern mit angemessenem Datenschutzniveau 
- keine Weitergabe oder Kombination der Daten 

<h2 v-click-hide class="absolute left-120 bottom-59">185.209.196.17</h2>
<h2 v-after class="absolute left-120 bottom-59">185.209.196.0</h2>
<h2 v-click class="bg-white dark:bg-black absolute left-120 bottom-59">2a02:810b:f3f:ea90:897d:19ee:5c6d:ff91</h2>
<h2 v-click class="w-full bg-white dark:bg-black absolute left-120 bottom-59">2a02:810b:f3f:0:0:0:0:0</h2>
<Footer />


---
title: Einführung in das Thema
hideInToc: true
---

# Einführung in das Thema
## Tracking ohne Einwilligung

- Vermeidung von 86 % Datenverlust <!-- denn nur 14 % akzeptieren bei einem rechtskonformen Cookie-Banner das Tracking: laut einer Studie eines Web-Analyse-Anbieters (2021) etracker -->
- ca. doppelt so viele akzeptieren das Tracking bei rechtswidrigen Nudging Techniken

<div class="mt-3 w-full">
  <img src="/images/CookieBanner-Nudging.png" /> 
</div>
<div class="flex justify-between mt-2 mb-6">
  <span v-click class="flex w-full justify-center">14 %</span> 
  <span v-click class="flex w-full justify-center">23 %</span> 
  <span v-click class="flex w-full justify-center">30 %</span> 
  <span v-click class="flex w-full justify-center">100 %</span> 
</div>

### Page-Tagging-Methode
- JavaScript Code, welcher beim Aufruf der Website ausgeführt wird
- Verzicht auf Cookies oder sonstiges Speichern auf dem Gerät
- Kein expliziter Zugriff auf das Gerät des Nutzers
<!-- zwei Möglichkeiten diese Methode umzusetzen -->
<Footer />


---
title: Einführung in das Thema
hideInToc: true
---

# Einführung in das Thema 
## Tracking ohne Einwilligung – weiteres Problem mit den Adblockern

- Desktop 290 Mio. Menschen
- mobile Endgeräte 560 Mio. Menschen
- blockieren standardmäßig namhafte URLs und Skript-Namen
- unabhängig von First- oder Third-Party-Request
- First-Party-Requests sollten bevorzugt werden
- Hosting auf Subdomain

<Footer />


---
title: Interaktionskonzept
hideInToc: false
---

# Interaktionskonzept
## Sitemap

<div class="mt-5 w-full">
  <img class="dark:hidden block" src="/images/sitemap.png" /> 
  <img class="dark:block hidden" src="/images/sitemap-dark.png" /> 
</div>

<Footer />


---
title: Interaktionskonzept
hideInToc: true
---

# Interaktionskonzept
## Übersicht der Websites

<div class="mt-0 w-11/12">
  <img src="/images/overview.png" /> 
</div>

<Footer />


---
title: Interaktionskonzept
hideInToc: true
---

# Interaktionskonzept
## Dashboard

<div class="mt-0 w-11/12">
  <img src="/images/website-detail.png" /> 
</div>

<Footer />


---
title: Interaktionskonzept
hideInToc: true
---

# Interaktionskonzept
## Kacheltypen

- Präsentation der Analysedaten
- beinhalten Texte, Zahlen, Diagramme/Grafiken
- Kacheltypen sind für bestimmte Performance Indikatoren geeignet
- Analyse-Daten in bestimmten Format
  <li>number</li>
  <li>{number: 15, diff: -10}</li>
  <li>[ {name: "text", value: 10}, {name: "text", value: 5} ]</li>
<div class="absolute right-20 bottom-8 w-5/12">
  <img class="" src="/images/desktop-detailview.png" /> 
</div>

<Footer />


---
title: Interaktionskonzept
hideInToc: true
---

# Interaktionskonzept
## Kacheltypen
<div class="">
  <h3>LiveData-Kachel</h3>
  <img class="w-30" src="/images/tile-liveuser.png" /> 
</div>
<div class="grid grid-cols-2 gap-x-6 w-4/5">
  <div class="">
    <h3>MultiData-Kachel</h3>
    <img class="w-100" src="/images/tile-multipis.png" /> 
  </div>
  <div class="">
    <h3>SmallText-/SmallChart-Kachel</h3>
    <img class="w-100" src="/images/tile-halfwidth.png" /> 
  </div>
  <div class="">
    <h3>BigChart-Kachel</h3>
    <img class="w-100" src="/images/tile-locationmap.png" /> 
  </div>
  <div class="">
    <h3>GoalProgress-Kachel</h3>
    <img class="w-100" src="/images/tile-goalprogress.png" /> 
  </div>
</div>

<Footer />


---
title: Technisches Konzept
hideInToc: false
---

# Technische Konzept 
## Universal Kachel

```html
<Tile website_id={id} user_id={id} tile="smalltext" indicator="country" i18n="true" />
```

- jede Kachel stellt eigene Berechnungsanfrage an API
<!-- - Request-Query: -->
```javascript
`/api/data/${props.website_id}/${props.user_id}/${props.tile}/${props.indicator}/calculate`
```

- anhand des Kacheltypen wird passende Funktion im Backend aufgerufen
- schnell erweiterbar durch neue Kacheltypen

<Footer />

<style>
  .slidev-code-wrapper pre {
    @apply bg-white dark:bg-black
  }
</style>


---
title: Technisches Konzept
hideInToc: true
---

# Technisches Konzept
## vom Skript zur Datenbank
<div v-click-hide class="absolute z-10 right-5">
  <img class="w-95 dark:hidden block" src="/images/architecture-services.png" /> 
  <img class="w-95 hidden dark:block" src="/images/architecture-services-dark.png" /> 
</div>
<div v-after class="absolute z-10 right-8 bottom-25">
  <img class="w-85 dark:hidden block" src="/images/architecture-script-to-db.png" /> 
  <img class="w-85 hidden dark:block" src="/images/architecture-script-to-db-dark.png" /> 
</div>

- Nutzer, Backend, Datenbank
```html
<script defer data-identifier="yMt0DNtgSJ" src="http://example.de/wapplytics.js"></script>
```

- TrackingData-Skript startet bei Aufruf der Website
- Do-Not-Track Überprüfung
- Browserdaten werden extrahiert
- Daten werden an API des VerifyData-Services gesendet

<Footer />

<style>
  .slidev-code-wrapper pre {
    @apply bg-white dark:bg-black
  }
</style>


---
title: Technisches Konzept
hideInToc: true
---

# Technisches Konzept
## vom Skript zur Datenbank
<div class="absolute z-10 right-8 bottom-25">
  <img class="w-85 dark:hidden block" src="/images/architecture-script-to-db.png" /> 
  <img class="w-85 hidden dark:block" src="/images/architecture-script-to-db-dark.png" /> 
</div>

- Verifizierung folgender Daten mit Funktionen des VerifyData-Services
```json
{
  "userAgent": "Mozilla/5.0 (Macintosh; Intel Mac OS ...",
  "touchpoints": { "maxTouchPoints": 0 },
  "os": "MacIntel",
  "screen": { "width": 2560, "height": 1440 },
  "language": "en−GB",
  "referrer ": "https://duckduckgo.com/",
  "website": "example.de",
  "path": "/",
  "identifier ": "yMt0DNtgSJ"
}
```

- SessionUUID Generierung 
  <li> WebsiteID, anonymisierter IP, Referrer, UserAgent, Timestamp <br/>und Salt </li>
- anhand der SessionUUID, wird neue Session & View oder nur eine View erstellt

<Footer />

<style>
  .slidev-code-wrapper pre {
    @apply bg-white dark:bg-black
  }
</style>


---
title: Technisches Konzept
hideInToc: true
---

# Technisches Konzept
## von Datenbank zur Kachel im Frontend
<div v-click-hide class="absolute z-10 right-5">
  <img class="w-95 dark:hidden block" src="/images/architecture-services.png" /> 
  <img class="w-95 hidden dark:block" src="/images/architecture-services-dark.png" /> 
</div>
<div v-after class="absolute z-10 right-15 bottom-15">
  <img class="w-70 dark:hidden block" src="/images/architecture-db-to-frontend.png" /> 
  <img class="w-70 hidden dark:block" src="/images/architecture-db-to-frontend-dark.png" /> 
</div>

- Analysedaten befinden sich in der Session- und View-Tabelle
- Universal Kachel ruft getData(props)-Funktion auf
- Request-Query sorgt für passenden Funktionsaufruf
```javascript
`/api/data/${props.website_id}/${props.user_id}/${props.tile}/${props.indicator}/calculate`
```

- Ermittlung der richtigen Datenbanktabelle
- Datenbankabfrage unter Berücksichtigung <br/>der Zeitspanne und WebsiteID
- einfache Berechnungen finden innerhalb der Abfrage statt
- andernfalls wird zusätzlich JavaScript verwendet 
- Rückgabewert passenden Format 

<Footer />

<style>
  .slidev-code-wrapper pre {
    @apply bg-white dark:bg-black
  }
</style>


---
title: Tech-Stack
hideInToc: false
---

# Tech-Stack

<div class="flex justify-center mt-8">
  <img class="w-9/12 dark:hidden block" src="/images/techstack.png" /> 
  <img class="w-9/12 hidden dark:block" src="/images/techstack-dark.png" /> 
</div>

<!-- - Next.js im Frontend sowie Backend
- MySQL als Datenbank
- Prisma für Datenbankzugriff 
- Styling mit Tailwind CSS
- kleinere Bibliotheken:
<li>tremor - Diagramme/Grafiken</li>
<li>headless UI - Dropdowns/Popups</li>
<li>request-ip - Filterung der IP-Adresse</li> 
<li>geolite2-redist - Ermittlung des Landes</li> 
<li>luxon - Verarbeitung der Zeitangaben</li> 
<li>next-auth - Authentifizierung</li> 
<li>next-i18next - Internationalisierung</li>  -->

<Footer />


---
title: Fazit und Ausblick
hideInToc: false
---
# Fazit und Ausblick
<!-- ### Ziel der Bachelor-Arbeit --> 
### Guter Prototyp für weitere Entwicklungen
- Datenschutzkonforme Website-Analyse-Plattform
- Tracking ohne Einwilligung des Nutzers
- beliebig viele Websites in anpassbaren Zeitspannen und Zeitzonen
- Universal Kachel-Komponente für alle Performance Indikatoren
### Ausblick
- Erweiterung der Kacheltypen und Gruppierung der Kacheln
- Kacheleinstellungen zum Anpassen der Darstellung
- Individualisierung der Plattform erweitern
- Hybride Trackingvariante

<Footer />

---
title: Live-Demo
hideInToc: true
layout: section
---
# Live-Demo
<div class="absolute z-10 top-1/10 -right-20">
  <img class="w-150 dark:hidden block" src="/images/wapplytics-dark.png" /> 
  <img class="w-150 hidden dark:block" src="/images/wapplytics-light.png" /> 
</div>
