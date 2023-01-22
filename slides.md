---
theme: apple-basic
class: text-left
highlighter: prism
lineNumbers: true
drawings:
  persist: false
css: windicss
fonts:
  provider: 'none'
title: Website-Analyse-Plattform
layout: intro
hideInToc: true
routerMode: 'history'
# download: true
---

# Website-Analyse-Plattform
## Bachelor-Arbeit 

<div class="absolute bottom-7">
  <h2>
    Florian Schmidt // 31.01.2023
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
- Übersichlichkeit und einfache Nutzung gewährleisten
<!-- https://sli.dev/guide/animations.html#click-animations -->
<Footer />

---
title: Einführung in das Thema
hideInToc: true
---
# Einführung in das Thema
## Ziel mit passenden Key Performance Indikatoren

- Analyse-Tool enthält viele verschiedene Performance Indikatoren
- Key Performance Indikator tragen zur Zielerreichung bei 
- kontinuierliche Erfolgskontrolle
### Perfomance Indikatoren

<h4 class="absolute left-20 bottom-55" v-click>Seitenaufrufe</h4>
<h4 class="absolute left-60 bottom-60" v-click>Aktive User</h4>
<h4 class="absolute left-90 bottom-35" v-click>Unterschiedliche Nutzer</h4>
<h4 class="absolute left-130 bottom-50" v-click>Traffic-Quellen</h4>
<h4 class="absolute left-100 bottom-65" v-click>Absprungrate</h4>
<h4 class="absolute left-30 bottom-20" v-click>Durchschnittliche Verweildauer</h4>
<h4 class="absolute left-45 bottom-40 " v-click>Nutzerpfade</h4>
<h4 class="absolute left-160 bottom-25" v-click>Standorte</h4>
<h4 class="absolute left-170 bottom-57" v-click>Geräteinformationen</h4>
<!-- <h4 class="absolute left-105 bottom-10" v-click>Erfolgreiche Event Klicks</h4>
<h4 class="absolute left-180 bottom-40" v-click>Erfolgreiche Event Klickrate </h4> -->

<Footer/>
---
title: Einschränkungen durch den Datenschutz
hideInToc: false
---
# Einschränkungen durch den Datenschutz

- DSGVO & TTDSG erschweren flächendeckendes Tracking
- DSGVO – schützt die personenbezogenen Daten
- TTDSG – legt die Einwilligungpflicht fest
- weitverbreiteste Variante – Nutzerdaten in Cookies speichern
- ohne Einwilligung findet kein Tracking statt
- viele Browser & Adblocker blockieren Third-Party-Cookies 
- Datenschutz ist kein Problem, sondern Grundrecht der Nutzer <!--  -->
<Footer />

---
title: Einschränkungen durch den Datenschutz
hideInToc: true
---
# Einschränkungen durch den Datenschutz

- Ab wann kann auf die Einwilligung verzichtet werden?
<br/>
<br/>

### DSGVO & TTDSG

- Einsatz von ausschließlich essentiellen Cookies <!-- Analyse-Cookie sind nicht essentiell -->
- kein Zugriff auf das Endgerät, um Identifikatoren auszulesen <!-- das sind z. B. Geräte- oder Werbe-IDs, IMEI-Nummern, MAC-Adressen  -->
- Nutzer darf nicht über längeren Zeitraum wieder erkannt werden <!-- also ab einem gewissen Zeitraum muss der Nutzer als neu angesehen werden -->
- keine Identifikation über personenbezogene Daten <!-- IP-Adresse, E-Mail, Name, Anschrift, Phone, Alter, Geschlecht -->
- keine zu extremen Tracking-Methoden <!-- Maus- und Session-Tracking -->
- Datenverarbeitung und -transfer nur in Ländern mit angemessenem Datenschutzniveau <!-- Google Fonts, als gutes Beispiel. Hier werden beim Laden der Fonts die Nutzerdaten an Google geschickt, d.h. in die USA... deswegen gab es in der Vergangenheit dazu auch so viele Abmahnungen -->
- keine Weitergabe oder Kombination der Daten <!-- Beispiel man analysiert mit einem Analyse Tools mehrere Websites. Diese Daten müssen getrennt bleiben  -->
<Footer />

---
title: Tracking ohne Einwilligung
hideInToc: false
---
# Tracking ohne Einwilligung

- Vermeidung von 86 % Datenverlust <!-- denn nur 14 % akzeptieren bei einem rechtskonformen Cookie-Banner das Tracking: laut einer Studie eines Web-Analyse-Anbieters (2021) etracker -->
- ca. doppelt so viele akzeptieren das Tracking bei rechtswidgrigen Nudging Techniken

<div class="mt-3 w-full">
  <img src="/images/CookieBanner-Nudging.png" /> 
</div>
<div class="flex justify-between mt-2 mb-6">
  <span v-click class="flex w-full justify-center">100 %</span> 
  <span v-click class="flex w-full justify-center">30 %</span> 
  <span v-click class="flex w-full justify-center">23 %</span> 
  <span v-click class="flex w-full justify-center">14 %</span> 
</div>

### Page-Tagging-Methode
- JavaScript Code, welcher beim Aufruf der Website ausgeführt wird
- Verzicht auf Cookies oder sonstiges speichern auf dem Gerät des Nutzers möglich
- Kein expliziter Zugriff auf das Gerät des Nutzers
<!-- zwei Möglichkeiten diese Methode umzusetzen -->
<Footer />

---
title: Tracking ohne Einwilligung
hideInToc: true
---
# Tracking ohne Einwilligung
## ohne Personenbezug
- Daten die automatisch beim Aufruf mitgeliefert werden
- Bsp. Referrer, UserAgent, IP-Adresse
- Referrer & UserAgent stellen keinen Personenbezug dar
- IP-Adresse verwendbar nach Anonymisierung
<br/>
<br/>
<br/>

<h2 v-click-hide class="absolute left-20 bottom-62">185.209.196.17</h2>
<h2 v-after class="absolute left-20 bottom-62">185.209.196.0</h2>
<h2 v-click class="bg-white dark:bg-black absolute left-20 bottom-62">2a03:1b20:6:f011::a02e</h2>
<h2 v-click class="w-full bg-white dark:bg-black absolute left-20 bottom-62">2a03:1b20:6:f011::0</h2>


- Wiedererkennbarkeit, aber keine identifizierung
- Generierung eines Hashwertes
<!-- Falls die Website-Analyse nicht ohne Personenbezug stattfinden kann, bietet die DSGVO, die Möglichkeit, die Einwilligung zu umgehen  -->
<Footer />

---
title: Tracking ohne Einwilligung
hideInToc: true
---
# Tracking ohne Einwilligung
## mit vernünftiger Erwartung des Nutzers

- keine Überraschung im gewissen Maße analysiert zu werden
- Erwartungen des Nutzer nicht überschreiten
- erwartungsgemäß sind bsp. die Analyse der Seitenbesuche oder Aufenthaltsdauer
- unerwartet sind bsp. das Aufzeichnen von Maus-Bewegungen
<br/>
<br/>

### Auflagen der DSGVO
<div class="flex">
  <div class="flex-column w-1/2">
    <ul>
      <li>Auftragsverarbeitungsvertrag</li>
      <li>keine Datenweitergabe an Dritte</li>
      <li>Kombination mit anderen Daten ist untersagt</li>
      <li>keine persönliche Identifikation</li>
      <li>Widerruf über Datenschutzerklärung</li>
    </ul>
  </div>
  <div class="flex-column w-1/2">
    <ul>
      <li>anonymisierte IP-Adresse</li>
      <li>Do-Not-Track berücksichtigen</li>
      <li>keinen Einsatz von Cookies oder ähnlichen</li>
      <li>Datenverarbeitung nur in Europa</li>
    </ul>
  </div>
</div>
<Footer />

---
title: Tracking ohne Einwilligung
hideInToc: true
---
# Tracking ohne Einwilligung
## Problem mit den Adblockern

- Desktop 290 Mio. Menschen
- mobile Endgeräte 560 Mio. Menschen
- blockieren standardmäßig namenhafte URLs und Skript-Namen
- unabhängig von First- oder Third-Party-Request
- First-Party-Requests sollten bevorzugt werden
- Hosting auf Subdomain

<Footer />

---
title: Zielgruppe
hideInToc: false
---
# Zielgruppe

- Website-Betreiber, die ohne Cookies und Einwilligungspflicht analysieren möchten
- Datenschutz fokusiert
- mögen moderne, intuitive und internationalisierte Benutzungsoberfläche
- benötigen keine analytischen Vorkenntnisse 
<br/>
<br/>

### Unternehmen & Einzelpersonen

- Analyse der Website, inkl. Subdomains
- Vermeidung von verschiedenen Top-Level-Domains

<Footer />

---
title: Aufbau der Plattform
hideInToc: false
---
# Aufbau der Plattform
## Sitemap

<div class="mt-5 w-full">
  <img class="dark:hidden block" src="/images/sitemap.png" /> 
  <img class="dark:block hidden" src="/images/sitemap-dark.png" /> 
</div>

<Footer />

---
title: Aufbau der Plattform
hideInToc: true
---
# Aufbau der Plattform
## Übersicht der Websites

<div class="mt-0 w-11/12">
  <img src="/images/overview.png" /> 
</div>

<Footer />

---
title: Aufbau der Plattform
hideInToc: true
---
# Aufbau der Plattform
## Dashboard

<div class="mt-0 w-11/12">
  <img src="/images/website-detail.png" /> 
</div>

<Footer />

---
title: Aufbau der Plattform
hideInToc: true
---
# Aufbau der Plattform
## Einstellungen der Websites

<div class="mt-0 w-11/12">
  <img src="/images/settings-websites.png" /> 
</div>

<Footer />

---
title: Aufbau der Plattform
hideInToc: true
---
# Aufbau der Plattform
## Einstellungen der Nutzer

<div class="mt-0 w-11/12">
  <img src="/images/settings-accountmanagement.png" /> 
</div>

<Footer />

---
title: Aufbau der Plattform
hideInToc: true
---
# Aufbau der Plattform
## Einstellungen des Profil

<div class="mt-0 w-11/12">
  <img src="/images/settings-profile.png" /> 
</div>

<Footer />

---
title: Aufbau der Plattform
hideInToc: true
---
# Aufbau der Plattform
## Kacheltypen

- Präsentation der Analysedaten
- beinhalten Texte, Zahlen, Diagramme/Grafiken
- Kacheltypen sind für alle Performance Indikatoren geeignet
<div class="absolute bottom-8">
  <img  class="max-w-14/30" src="/images/desktop-detailview.png" /> 
</div>

<Footer />

---
title: Aufbau der Plattform
hideInToc: true
---
# Aufbau der Plattform
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
title: Technischer Ablauf
hideInToc: false
---
# Technischer Ablauf
## vom Skript zur Datenbank
<div class="absolute z-10 right-5">
  <img class="w-100 dark:hidden block" src="/images/architecture-services.png" /> 
  <img class="w-100 hidden dark:block" src="/images/architecture-services-dark.png" /> 
</div>

- Frontend, Backend, Datenbank
- Website-Nutzer triggert TrackingData-Skript
- Daten werden an Backend gesendet
- Backend verifiziert Daten und speichert sie in Datenbank
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

<Footer />

<style>
  .slidev-code-wrapper pre {
    @apply bg-white dark:bg-black
  }
</style>

---
title: Technischer Ablauf
hideInToc: true
---
# Technischer Ablauf
## von Datenbank zur Kachel im Frontend
<div class="absolute z-10 right-5">
  <img class="w-100 dark:hidden block" src="/images/architecture-services.png" /> 
  <img class="w-100 hidden dark:block" src="/images/architecture-services-dark.png" /> 
</div>

```html
<Tile website_id={id} user_id={id} tile ="smalltext" indicator="country" i18n="true" />
```

- DeployData-Service stellt API-Schnittstelle bereit
- Request-Query sorgt für passenden Funktionsaufruf
- Datenbankabfrage mit Prisma und gleichzeitige Berechnung
- Rückgabewert ist ein Array im gewünschten Format 

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
- Next.js im Frontend sowie Backend
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
<li>next-i18next - Internationalisierung</li> 

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
- Analysedaten werden kontinuierlich aktualisiert
- Fokus auf Nutzerfreundlichkeit und Usability
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
