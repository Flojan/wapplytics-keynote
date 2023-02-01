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
---

# Website-Analyse-Plattform
## Bachelor-Arbeit 

<div class="absolute bottom-7">
  <h2>
    Florian Schmidt // 15.02.2023
  </h2>
</div>

<Footer />

<!--
Hallo und herzlich willkommen zu meinem Kolloquium über das Thema Website-Analyse-Plattform.
-->

---
title: Inhalt
hideInToc: true
---

# Inhalt 
<Toc listClass="list-disc" />

<Footer />

<!--
- Als Erstes gebe ich einen kurzen Überblick über mein Thema und mein angestrebtes Ziel
- anschließend zeige ich, wie die Website-Analyse durch den Datenschutz eingeschränkt wird
- und welche Möglichkeiten es gibt, die Website-Analyse unter Einhaltung der Datenschutzrichtlinien ohne Einwilligung durchzuführen 
- Dann stelle ich die Zielgruppe vor und zeige, wie die Website-Analyse-Plattform aufgebaut ist
- danach gehe ich auf den technischen Ablauf ein und erkläre zum einen wie die Analysedaten erfasst werden und zum wie diese visualisiert werden
- zum Schluss geh ich auf den verwendeteten Tech-Stack ein und gebe ein Fazit und Ausblick zu meiner Arbeit
-->

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

<!--
- Für viele Website-Betreiber sind die Website-Analyse-Tools ein wichtiger Bestandteil der Marketingstrategie, um ihren Erfolg zu messen
- Diese Analyse-Tools ermöglichen es, die wichtigsten Indikatoren zu messen, um die eigenen Ziele zu überprüfen
- Außerdem können hierbei die Bedürfnisse der Nutzer erkannt werden und anhand dessen die Website angepasst werden
- durch die Datenschutzrichtlinien ist das aktuell weitverbreiteste Tracking mit Cookies nur eingeschränkt möglich, da hierbei die Nutzer zur Analyse einwilligen müssen

- Ziel meiner Arbeit ist es, eine dynamische Website-Analyse-Plattform zu entwickeln, die den Datenschutz berücksichtigt und die Analyse des Website-Nutzers ohne Einwilligung ermöglicht
- Um die Übersichtlichkeit und die einfache Nutzung zu gewährleisten, beschränkt sich die Plattform auf die wichtigsten Indikatoren, sodass die Analyse-Daten auf einer einzigen Seite dargestellt werden können
-->

---
title: Einführung in das Thema
hideInToc: true
---

# Einführung in das Thema
## Ziel mit passenden Key Performance Indikatoren

- Analyse-Tool enthält viele verschiedene Performance Indikatoren
- Key Performance Indikator tragen zur Zielerreichung bei 
- kontinuierliche Erfolgskontrolle
### Performance Indikatoren

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

<!--
- um den Fortschritt der Ziele zu überprüfen, ist es wichtig die richtigen Key Performance Indikatoren zu wählen
- da diese zur Zielerreichung beitragen, ist es wichtig, dass diese kontinuierlich überprüft werden
- die Performance Indikatoren werden also erst Key Performance Indikatoren, wenn sie zur Zielerreichung beitragen
- Seitenaufrufe: Gesamtzahl der Seitenaufrufe einer Website
- Aktive Nutzer: Anzahl der Nutzer, die in Echtzeit auf der Website sind
- Unterschiedliche Nutzer: Im Gegensatz zu den Seitenaufrufen, werden hier nur unterschiedliche Nutzer gezählt
- Traffic-Quellen: sind verschiedene Kanäle, über die die Website aufgerufen wird. Zum Beispiel Suchmaschinen, Social Media oder andere Websites
- Absprungrate: die Rate beschreibt die Anzahl der Nutzer, die die Website nach einer Seite direkt wieder verlassen
- durchschnittliche Verweildauer: die durchschnittliche Zeit, die ein Nutzer auf der Website verbringt
- Nutzerpfade: welche Seiten werden von den Nutzern am meisten aufgerufen
- Standorte: woher kommen die Nutzer (aus welchem Land)
- Geräteinformationen: welche Geräteart, Betriebssystem, Auflösung und die Browserversion werden von den Nutzern verwendet

- Beispiel-Ziel: Der Website-Betreiber möchte in den nächsten 6 Monaten 100 Klicks aus Deutschland über Instagram generieren. Hierfür könnten die PIs Traffic-Quellen und Standort als KPIs betrachtet werden.

-->

---
title: Einschränkungen durch den Datenschutz
hideInToc: false
---

# Einschränkungen durch den Datenschutz

- DSGVO – schützt die personenbezogenen Daten
- TTDSG – legt die Einwilligungpflicht fest
- DSGVO & TTDSG erschweren flächendeckendes Tracking
- weitverbreiteste Variante – Nutzerdaten in Cookies speichern
- ohne Einwilligung findet kein Tracking statt
- viele Browser & Adblocker blockieren Third-Party-Cookies 
- Datenschutz ist kein Problem, sondern Grundrecht der Nutzer <!--  -->
<Footer />

<!--
- die Analyse wurde in den letzten Jahren immer stärker durch Datenschutz eingeschränkt
- das ist grob gesagt die DSGVO - Datenschutz-Grundverordnung - welche die personenbezogenen Daten schützt - dieses trat am 25.05.2018 in Kraft
- und das TTDSG - Telekommunikation-Telemedien-Datenschutz-Gesetz - welches die Einwilligungspflicht festlegt - dieses trat am 01.12.2021 in Kraft
- diese beiden Gesetze erschweren das flächendeckende Tracking 
- da die weitverbreiteste Tracking-Methode die Speicherung der Nutzerdaten in Cookies ist
- kann ohne Einwilligung des Nutzers kein Tracking stattfinden, da Analyse-Cookies keine essentiellen Cookies sind 
- außerdem ist es so, dass viele Browser und Adblocker schon standardmäßig Third-Party-Cookies blockieren, wodurch die Nutzer nicht analysiert werden können
- man sollte aber nicht vergessen, dass der Datenschutz kein Problem, sondern ein Grundrecht der Nutzer ist
-->

---
title: Einschränkungen durch den Datenschutz
hideInToc: true
---

# Einschränkungen durch den Datenschutz

- Ab wann kann auf die Einwilligung verzichtet werden?
<br/>
<br/>

### DSGVO & TTDSG

- Einsatz von ausschließlich essentiellen Cookies
- kein Zugriff auf das Endgerät, um Identifikatoren auszulesen
- Nutzer darf nicht über längeren Zeitraum wieder erkannt werden 
- keine Identifikation über personenbezogene Daten 
- keine zu extremen Tracking-Methoden 
- Datenverarbeitung und -transfer nur in Ländern mit angemessenem Datenschutzniveau 
- keine Weitergabe oder Kombination der Daten 
<Footer />

<!--
- und wir werden uns jetzt einmal anschauen, ab wann man auf die Einwilligung verzichten kann.
- hierfür müssen gewissen Voraussetzungen der Datenschutzgesetze erfüllt sein
- zum einen dürfen ausschließlich essentielle Cookies verwendet werden, damit auf die Einwilligungsbanner verzichtet werden kann
- es darf nicht explizit auf das Endgerät zugegriffen werden, um Identifikatoren (Geräte-IDs, IMEI-Nummern, MAC-Adressen) auszulesen, sondern nur mit den Daten gearbeitet werden, die der Browser automatisch übermittelt
- der Nutzer darf nicht über einen längeren Zeitraum wieder erkannt werden, also ab einem gewissen Zeitraum muss der Nutzer als neu angesehen werden
- es darf keine Identifikation über personenbezogene Daten stattfinden, also IP-Adresse, E-Mail, Name, Anschrift, Telefon, Alter, Geschlecht
- es dürfen keine zu extremen Tracking-Methoden verwendet werden, bsp. Maus-Tracking
- die Datenverarbeitung und -transfer dürfen nur in Ländern mit angemessenem Datenschutzniveau stattfinden 
- außerdem dürfen die Analysedaten nicht weitergegeben oder mit anderen Daten kombiniert werden) z. B. wenn mehrere Websites in einem Analyse-Tool analysiert werden, dürfen keine Gesamtstatistiken erstellt werden
-->

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
  <span v-click class="flex w-full justify-center">14 %</span> 
  <span v-click class="flex w-full justify-center">23 %</span> 
  <span v-click class="flex w-full justify-center">30 %</span> 
  <span v-click class="flex w-full justify-center">100 %</span> 
</div>

### Page-Tagging-Methode
- JavaScript Code, welcher beim Aufruf der Website ausgeführt wird
- Verzicht auf Cookies oder sonstiges speichern auf dem Gerät des Nutzers möglich
- Kein expliziter Zugriff auf das Gerät des Nutzers
<!-- zwei Möglichkeiten diese Methode umzusetzen -->
<Footer />

<!--
- durch das Tracking ohne Einwilligung können wir die Datenverluste um 86 % vermeiden, denn nur 14 % akzeptieren bei einem rechtskonformen Cookie-Banner das Tracking
- und ca. doppelt so viele akzeptieren das Tracking bei rechtswidrigen Nudging Techniken (hierbei werden die Nutzer in die Irre geführt, durch Farbgestaltung oder du das nicht erkennen der Buttons, um sie zum Klicken zu bewegen)
- hierfür gibt es als Lösung die Page-Tagging-Methode
- diese Methode besteht aus einem JavaScript Code, welcher beim Aufruf der Website ausgeführt wird
- hierdurch ist es möglich, auf Cookies oder sonstiges Speichern auf dem Gerät des Nutzers zu verzichten
- und es findet kein expliziter Zugriff auf das Gerät des Nutzers statt
-->

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
<h2 v-click class="bg-white dark:bg-black absolute left-20 bottom-62">2a02:810b:f3f:ea90:897d:19ee:5c6d:ff91</h2>
<h2 v-click class="w-full bg-white dark:bg-black absolute left-20 bottom-62">2a02:810b:f3f:0:0:0:0:0</h2>

- Wiedererkennbarkeit, aber keine identifizierung
- Generierung eines Hashwertes

<Footer />

<!--
- Tracking ohne Personenbezug wäre eine Möglichkeit, um eine Einwilligung zu umgehen
- hierbei werden Daten, die automatisch beim Aufruf mitgeliefert werden, verwendet 
- das sind beispielsweise der Referrer, der UserAgent oder die IP-Adresse
- der Referrer ist das englische Wort für Traffic-Quelle, also die Quelle von dem Nutzer, auf die Website kommt
- und der UserAgent ist ein String, der Informationen über den Browser und das Betriebssystem des Nutzers enthält
- verwendet man nur diese beiden Daten, stellt es keinen Personenbezug dar und der Nutzer ist über einen bestimmten Zeitraum hinweg wiedererkennbar
- um die Wiedererkennbarkeit zu erhöhen, kann zusätzlich die IP-Adresse in anonymisierter Form verwendet werden
- IPv4 & IPv6
- Die Wiedererkennbarkeit wird dadurch erhöht, aber es findet keine Identifizierung statt
- ja und daraus wird dann ein Hashwert generiert
-->

---
title: Tracking ohne Einwilligung
hideInToc: true
---

# Tracking ohne Einwilligung
## mit vernünftiger Erwartung des Nutzers

- keine Überraschung im gewissen Maße analysiert zu werden
- unerwartet sind bsp. das Aufzeichnen von Maus-Bewegungen
- erwartungsgemäß sind bsp. die Analyse der Seitenbesuche oder Aufenthaltsdauer
<br/>
<br/>

### Auflagen der DSGVO
<div class="flex">
  <div class="flex-column w-1/2">
    <ul>
      <li>Auftragsverarbeitungsvertrag</li>
      <!-- <li>keine Datenweitergabe an Dritte</li>
      <li>Kombination mit anderen Daten ist untersagt</li>
      <li>keine persönliche Identifikation</li> -->
      <li>Widerruf über Datenschutzerklärung</li>
    </ul>
  </div>
  <div class="flex-column w-1/2">
    <ul>
      <li>anonymisierte IP-Adresse</li>
      <li>Do-Not-Track berücksichtigen</li>
      <!-- <li>keinen Einsatz von Cookies oder ähnlichen</li> -->
      <!-- <li>Datenverarbeitung nur in Europa</li> -->
    </ul>
  </div>
</div>
<Footer />

<!--
- Falls die Website-Analyse nicht ohne Personenbezug stattfinden kann, bietet die DSGVO, immer noch eine Möglichkeit, die Einwilligung trotzdem zu umgehen
- und zwar, wenn die Analyse des Website-Betreibers, nicht die Erwartungen des Nutzers nicht überschreitet
- das heißt der Nutzer rechnet schon damit, dass er in einem gewissen Maß analysiert wird
- aber das heißt nicht, dass er damit rechnet, dass seine Maus-Bewegungen genaustens aufgezeichnet werden
- sondern er rechnet damit, dass seine Seitenbesuche oder Aufenthaltsdauer analysiert werden
- Dafür gibt es noch einmal eine Reihe an zusätzlichen Auflagen der DSGVO, die eingehalten werden müssen
- und zwar, dass ein Auftragsverarbeitungsvertrag zwischen Website-Betreiber und der Analyse-Plattform (bzw. dem Hosting-Anbieter) abgeschlossen wird
- da es keine Einwilligungsbanner gibt, muss der Nutzer über die Datenschutzerklärung der Analyse widerrufen können
- außerdem muss die IP-Adresse anonymisiert werden, da der Nutzer halt nicht identifiziert werden darf
- und es muss auch noch das Do-Not-Track-Protokoll berücksichtigt werden, welcher der Nutzer in den Browsereinstellungen aktivieren kann
-->

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

<!--
- Bei dem Tracking ohne Einwilligung gibt es aber ein Problem mit den Adblockern
- Adblocker sind bei vielen Nutzern sehr beliebt, da sie unter anderem Werbung blockieren
- auf Desktop-Rechnern sind das 290 Millionen Menschen und auf mobilen Endgeräten 560 Millionen Menschen
- und Adblocker blockieren mittlerweile aber nicht nur Werbung, sondern standardmäßig namenhafte URLs und Skript-Namen
- und das unabhängig davon, ob es sich um First- oder Third-Party-Requests handelt
- aber First-Party-Requests sollten bevorzugt werden, da diese ein besseres Ansehen haben und weniger wahrscheinlich blockiert werden
- d.h. die Analyse-Plattform sollte bsp. auf einer Subdomain gehostet werden, um Third-Party-Requests zu vermeiden
-->

---
title: Zielgruppe
hideInToc: false
---

# Zielgruppe

- Website-Betreiber, die ohne Cookies und Einwilligungspflicht analysieren möchten
- Datenschutz fokusiert
- mögen moderne, intuitive, anpassbare und internationalisierte Benutzungsoberflächen
- benötigen keine analytischen Vorkenntnisse 
<br/>
<br/>

### Unternehmen & Einzelpersonen

- Analyse der Website, inkl. Subdomains
- Vermeidung von verschiedenen Top-Level-Domains

<Footer />

<!--
- Die Zielgruppe meiner Plattform sind Website-Betreiber, die ohne Cookies und Einwilligungspflicht analysieren möchten
- und dabei auch noch auf den Datenschutz fokussiert sind
- außerdem mögen sie moderne, intuitive, anpassbare und internationalisierte Benutzungsoberflächen
- und ihnen ist es wichtig, dass sie keine analytischen Vorkenntnisse benötigen, also sie müssen keine Marketer sein

- Die Plattform ist für Unternehmen und Einzelpersonen gedacht
- die bsp. eine Website und vielleicht sogar Websites auf der Subdomain betreiben und diese analysieren möchten
- wenn sie bsp. Unterschiedliche Top-Level-Domains haben, dann müssen sie für jede dieser Domains eine eigene Analyse-Plattform einrichten, damit Third-Party-Requests vermieden werden
-->

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

<!--
- Jetzt zeige ich den Aufbau der Website-Analyse-Plattform zuerst einmal anhand einer Sitemap
- und zwar ist generell zu sagen, dass es 3 verschiedene Nutzergruppen gibt, welche unterschiedliche Berechtigungen haben
- das wären einmal die Leute die keinen Zugang zur Plattform haben, die kommen nur bis zum Login
- die zweite Gruppe sind die Leute die Zugang zur Plattform haben und somit authentifiziert sind
- die kommen auf die Start- bzw. Übersichtsseite und können sich dann die einzelnen Website-Analysen ansehen
- zudem können sie noch unter den Einstellungen ihr eigenes Profil bearbeiten
- und die dritte Gruppe sind die Administratoren, die haben die höchsten Rechte und können bsp. in den Einstellungen neue Websites hinzufügen/löschen und neue Nutzer anlegen/löschen
- und damit ihr besser versteht, was ich meine, zeige ich euch jetzt die Sitemap anhand von Wireframes
-->

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

<!--
- Fangen mit der Start-/Übersichtseite der Websites an
- und zwar werden hier alle Websites angezeigt, die ein Admin hinzugefügt hat
- aber nur in einer groben Zusammenfassung, welche 4 verschiedene Performance Indikatoren anzeigt
- Seitenaufrufe, einzigartige Nutzer, durchschnittliche Verweildauer und die Absprungrate
- und im Balken Diagramm sind noch einmal die Seitenaufrufe detailierter zu sehen 
- dieses Konstrukt ist eine von verschiedenen Kacheln, wo ich später noch einmal genauer eingehen werde
- Sidebar erklären
-->

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

---
---
---
---
