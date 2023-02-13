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
- Als Erstes gebe ich einen Überblick über mein Thema und mein angestrebtes Ziel und gehe hierbei auf die Einschränkungen des Datenschutzes ein
- Dann zeige ich anhand des Interaktionskonzepts, wie die Website-Analyse-Plattform aufgebaut ist
- anschließend gehe ich auf das technische Konzept ein und erkläre ein paar Abläufe, wie die einzelnen Instanzen miteinander zusammenarbeiten
- zum Schluss geh ich auf den verwendeten Tech-Stack ein und gebe ein Fazit und Ausblick zu meiner Arbeit
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
- Übersichtlichkeit und einfache Nutzung gewährleisten
<!-- https://sli.dev/guide/animations.html#click-animations -->
<Footer />

<!--
- Für viele Website-Betreiber sind die Website-Analyse-Tools ein wichtiger Bestandteil der Marketingstrategie, um ihren Erfolg zu messen
- Diese Analyse-Tools ermöglichen es, die wichtigsten Indikatoren zu messen, um die eigenen Ziele zu überprüfen
- Außerdem können hierbei die Bedürfnisse der Nutzer erkannt werden und anhand dessen die Website angepasst werden
- durch die Datenschutzrichtlinien ist das aktuell weitverbreitetste Tracking mit Cookies nur eingeschränkt möglich, da hierbei die Nutzer zur Analyse einwilligen müssen

- Ziel meiner Arbeit ist es, eine dynamische Website-Analyse-Plattform zu entwickeln, die den Datenschutz berücksichtigt und die Analyse des Website-Nutzers ohne Einwilligung ermöglicht
- Um die Übersichtlichkeit und die einfache Nutzung zu gewährleisten, beschränkt sich die Plattform auf die wichtigsten Indikatoren, sodass die Analyse-Daten auf einer einzigen Seite dargestellt werden können
-->

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

<!--
- die meisten Analyse-Tools enthalten viele verschiedene Performance Indikatoren und hierbei ist es wichtig, um den Fortschritt der Ziele überprüfen zu können, die richtigen Key Performance Indikatoren zu wählen 
- diese sollten kontinuierlich überprüft werden, da sie zur Zielerreichung beitragen 
- die Performance Indikatoren werden also erst Key Performance Indikatoren, wenn sie zur Zielerreichung beitragen
- jetzt blende ich einmal die wichtigsten Performance-Indikatoren ein, welches auch schon meist selbsterklärend sind
- Seitenaufrufe: (Gesamtzahl der Seitenaufrufe einer Website)
- Aktive Nutzer: Anzahl, die in Echtzeit auf der Website sind
- Unterschiedliche Nutzer: (Im Gegensatz zu den Seitenaufrufen, werden hier nur unterschiedliche Nutzer gezählt)
- Traffic-Quellen: Zum Beispiel Suchmaschinen oder Social Media 
- Nutzerpfade: welche Seiten werden von den Nutzern am meisten aufgerufen
- Standorte: woher kommen die Nutzer (aus welchem Land)
- Geräteinformationen: (welche Geräteart, Betriebssystem, Auflösung und die Browserversion werden von den Nutzern verwendet)
- Absprungrate: die Anzahl der Nutzer, die die Website bereits nach einer Seite direkt wieder verlassen
- durchschnittliche Verweildauer: (die durchschnittliche Zeit, die ein Nutzer auf der Website verbringt)

- Beispiel-Ziel: Der Website-Betreiber möchte in den nächsten 6 Monaten 100 Nutzer aus Deutschland über Instagram generieren. Hierfür könnten die PIs Traffic-Quellen und Standort als KPIs betrachtet werden.
-->

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

<!--
- die Analyse wurde in den letzten Jahren immer stärker durch Datenschutz eingeschränkt
- das ist grob gesagt die DSGVO - Datenschutz-Grundverordnung - welche die personenbezogenen Daten schützt - dieses trat am 25.05.2018 in Kraft
- und das TTDSG - Telekommunikation-Telemedien-Datenschutz-Gesetz - welches die Einwilligungspflicht festlegt - dieses trat am 01.12.2021 in Kraft
- diese beiden Gesetze erschweren das flächendeckende Tracking;
- da die weitverbreitetste Tracking-Methode die Speicherung der Nutzerdaten in Cookies ist
- kann ohne Einwilligung des Nutzers kein Tracking stattfinden, da Analyse-Cookies keine essentiellen Cookies sind und somit eine Einwilligungspflicht besteht
- außerdem ist es so, dass viele Browser und Adblocker schon standardmäßig Third-Party-Cookies blockieren, wodurch die Nutzer nicht analysiert werden können
- man sollte aber nicht vergessen, dass der Datenschutz kein Problem, sondern ein Grundrecht der Nutzer ist und man diesen respektieren sollte
-->

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

<!--
- und wir werden uns jetzt einmal anschauen, ab wann man auf die Einwilligung verzichten kann.
- hierfür müssen gewissen Voraussetzungen der Datenschutzgesetze erfüllt sein
- zum einen dürfen ausschließlich essentielle Cookies verwendet werden, damit auf die Einwilligungsbanner verzichtet werden kann
- es darf nicht explizit auf das Endgerät zugegriffen werden, um Identifikatoren (Geräte-IDs, MAC-Adressen) auszulesen, sondern nur mit den Daten gearbeitet werden, die der Browser automatisch an den Webserver übermittelt
- der Nutzer darf nicht über einen längeren Zeitraum wieder erkannt werden, also ab einem gewissen Zeitraum muss der Nutzer als neu angesehen werden
- es darf keine Identifikation über personenbezogene Daten stattfinden, also bspw. IP-Adresse, diese muss dann erst anonymisiert werden ... falls personenbezogene Daten verwendet werden, muss die Browsereinstellung Do-Not-Track des Nutzers berücksichtigt werden
- es dürfen keine zu extremen Tracking-Methoden verwendet werden, bspw. Maus-Tracking
- die Datenverarbeitung und -transfer dürfen nur in Ländern mit angemessenem Datenschutzniveau stattfinden, bspw. europäischen Länder, aber z. B. nicht die USA
- außerdem dürfen die Analysedaten nicht weitergegeben oder mit anderen Daten kombiniert werden) z. B. wenn mehrere Websites in einem Analyse-Tool analysiert werden, dürfen keine Gesamtstatistiken erstellt werden
-->

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

<!--
- durch das Tracking ohne Einwilligung können wir die Datenverluste um 86 % vermeiden, denn nur 14 % akzeptieren bei einem rechtskonformen Cookie-Banner das Tracking
- und ca. doppelt so viele akzeptieren das Tracking bei rechtswidrigen Nudging Techniken (hierbei werden die Nutzer in die Irre geführt, durch Farbgestaltung oder du das nicht erkennen der Buttons, um sie zum Klicken zu bewegen)
- und natürlich 100 %, wenn man einfach nur darauf hingewiesen wird
- hierfür gibt es als Lösung die Page-Tagging-Methode
- diese Methode besteht aus einem JavaScript Code, welcher beim Aufruf der Website ausgeführt wird
- hierdurch ist es möglich, auf Cookies oder sonstiges Speichern auf dem Gerät des Nutzers zu verzichten
- und es findet kein expliziter Zugriff auf das Gerät des Nutzers statt
-->

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

<!--
- Bei dem Tracking ohne Einwilligung gibt es neben den Einschränkungen durch den Datenschutz, aber auch ein Problem mit den Adblockern
- Adblocker sind bei vielen Nutzern sehr beliebt, da sie unter anderem Werbung blockieren
- auf Desktop-Rechnern sind das 290 Millionen Menschen und auf mobilen Endgeräten 560 Millionen Menschen
- und Adblocker blockieren mittlerweile aber nicht nur Werbung, sondern standardmäßig namhafte URLs und Skript-Namen (bspw. wenn man Google Analytics nutzt wird das Skript von den Google Servern geladen und hierbei kann dann die Domain blockiert sein; oder wenn man die Open Source Analyse Plattform Matomo nutzt und hierbei es sogar selbst hostet, ist die Domain eher nicht das Problem, sondern der bekannte Skript-Name namens piwik.js, welcher dann blockiert wird)
- und das unabhängig davon, ob es sich um First- oder Third-Party-Requests handelt (weil es halt URLs und Skript-Namen filtert/blockiert)
- aber First-Party-Requests sollten trotzdem bevorzugt werden, da diese ein besseres Ansehen haben und verschiedene Adblocker unterschiedlich blockieren 
- d. h. die Analyse-Plattform sollte bspw. auf einer Subdomain gehostet werden, um Third-Party-Requests zu vermeiden, also die zu analysierende Website liegt dann auf der Hauptdomain
-->

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
title: Interaktionskonzept
hideInToc: true
---

# Interaktionskonzept
## Übersicht der Websites

<div class="mt-0 w-11/12">
  <img src="/images/overview.png" /> 
</div>

<Footer />

<!--
- Fangen mit der Start-/Übersichtseite der Websites an
- und zwar werden hier alle Websites angezeigt, die ein Admin hinzugefügt hat
- aber nur in einer groben Zusammenfassung, welche 4 verschiedene Performance Indikatoren anzeigt
- Seitenaufrufe, unterschiedlichen Nutzer, durchschnittliche Verweildauer und die Absprungrate
- und im Balken Diagramm sind noch einmal die Seitenaufrufe detailierter zu sehen 
- dieses Konstrukt ist eine von verschiedenen Kacheln, wo ich später noch einmal genauer eingehen werde
- Sidebar erklären
-->

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

<!--
- Kommen wir zum sog. Dashboard, also die einzelnen Website-Analysen
- hier sehen wir direkt, dass das Dashboard, die gleiche Kachel beinhaltet, welche wir gerade auf der Übersichtsseite gesehen haben 
- gefolgt von weiteren anderen Kacheltypen, die ich gleich noch vorstellen werde
- damit das Dashboard dynamisch bleibt und für verschiedene Anwendungsfälle anpassbar ist, können über den Button rechts oben, die Seite angepasst werden
- zum einen sollen die Kacheln hinzugefügt oder entfernt werden können
- zum anderen kann man hierüber den Zeitraum auswählen, für den die Daten angezeigt werden sollen
-->

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

<!--
- Kommen wir nun zu den Kacheltypen, die hauptsächlich auf dem Dashboard zu finden sind
- diese Kacheln sind dafür da, die Analysedaten kompakt und übersichtlich zu präsentieren
- sie bestehen aus Texten, Zahlen und Diagramme/Grafiken 
- manche Kacheltypen sind für mehrere Performance-Indikatoren geeignet und andere nur für einen
- und außerdem müssen die Analysedaten in einem bestimmten Format, passend für den Kacheltyp formatiert sein -> Unterpunkte, number; Objekt, Array aus mehreren Objekten
- und die einzelnen Kacheltypen werde ich jetzt vorstellen
-->

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

<!--
- die erste Kachel ist die LiveData-Kachel, die für den PI Aktive Nutzer geeignet ist, diese zeigt die aktuelle Anzahl der Nutzer an, die sich seit den letzten 5 Minuten auf der Website befinden (Format einfache number)
- unten drunter befindet sich die MultiData-Kachel, die wir schon öfters gesehen haben und diese besteht aus vier festen PIs, dazu gehören die Seitenaufaufrufe, die unterschiedlichen Nutzer, die durchschnittliche Verweildauer und die Absprungrate; Als Balkendiagramm werden die Seitenaufrufe zum gewählten Zeitraum dargestellt
- was vielleicht etwas schwierig zu sehen ist, dass unter Zahl in so einem kompakten Quadrat noch eine farbige Zahl steht, die den Verlust oder Zugewinn zum Zeitraum anzeigt (2 Formate, einmal das Objekt für die Quadrate und einmal das Array mit mehreren Objekten für das Balkendiagramm)
- die nächste Kachel ist die SmallText-/SmallChart-Kachel, die nur halbe Breite einnehmen und diese sind für bspw. die PIs Traffic-Quellen, Standorte, Geräteinformationen oder auch Nutzerpfade geeignet
- wie der Name schon sagt, besteht diese entweder aus mehreren Zeilen von Texten oder aus einem kleinen KreisDiagramm  (Format Array mit mehreren Objekten)
- die BigChart-Kachel ist besonders gut für den PI Standorte geeignet, da hier die Karte der Welt mit den Standorten der Nutzer dargestellt wird, zusätzlich dazu stehen rechts oben noch die Zahlen der Nutzer pro Land  (Format Array mit mehreren Objekten)
- und die letzte Kachel ist die GoalProgress-Kachel, wobei man hier die Ziele der Website einstellen kann, den aktuellen- und Ziel-Wert sieht und den Fortschritt in Prozent angezeigt bekommt
-->

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

<!--
- Schauen wir uns das jetzt einmal im technischen Konzept an, und zwar gibt es für die unterschiedlichen Kacheltypen eine Universal Kachel Komponente, bestehend aus verschiedenen Props, website_id, user_id, kacheltyp, Performance-Indikator und einen Boolean Wert für die Internationalisierung
- solch eine Kachel stellt eine eigene Berechnungsanfrage an folgende API
- und anhand des Kacheltypen wird dabei die passende Funktion im Backend aufgerufen
- und in diesen Funktionen findet dann die Berechnung der Performance Indikatoren statt
- durch die Universal Kachel Komponente können somit schnell neue Kacheltypen hinzugefügt werden 
- und bei einfachen Berechnungen, wo nur gezählt wird, kann die vorhandene Funktion wiederverwendet werden
-->

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

<!--
- So, aber ohne Analysedaten bringt uns auch eine Kachel nicht, deswegen schauen wir und jetzt einmal an, wie die Daten vom Skript in der Datenbank landen
- rechts sehen wir die komplette Architektur der Plattform, aber wir schauen uns jetzt einmal nur den rechten Teil an -> Nutzer, Backend und Datenbank (klick)
- Also der Website-Betreiber platziert das Skript auf der zu analysierenden Website im Head-Tag mit folgendem Script-Element, bestehend auch data-identifier (eindeutiger Website ID), src (Pfad zum TrackingData-Skript) und dem Attribut defer, damit das Skript so geladen wird, damit es die Verarbeitung der Seite nicht blockiert
- das TrackingData-Skript startet bei jedem Aufruf der Website im Browser des Nutzers
- bevor hierbei Daten überhaupt gesammelt werden, wird erst einmal überprüft, ob Do-Not-Track beim Nutzer aktiv ist
- und falls das nicht der Fall ist, werden die Browserdaten extrahiert und in einem JSON-Objekt gespeichert und anschließend an die API des VerifyData-Services geschickt
-->

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

<!--
- Die Daten kommen dann, wie hier im JSON-Objekt zu sehen, im Backend an und werden dort verifiziert und zuletzt in der Datenbank gespeichert
- für die Verifizierung werden verschiedene Funktionen des VerifyData-Services aufgerufen und gestartet wird mit dem "identifier", welcher mit der passenden website_id in der Datenbank abgeglichen wird, ob es überhaupt eine gültige Website ist
- als Nächstes wird mithilfe einer externen Bibliothek die IP-Adresse ermittelt, da diese an vielen verschiedenen Stellen im Request sich befinden kann
- im Anschluss wird die IP-Adresse, wie vorhin gezeigt, anonymisiert 
- und eine SessionUUID wird generiert, und zwar aus der WebsiteID, anonymisierter IP, Referrer, UserAgent, einen Timestamp (Jahr und Kalenderwoche) und einen 10-stelligen Salt, um die UUID noch sicherer zu gestalten
- mithilfe der SessionUUID wird nun in der Datenbank abgeglichen, ob bereits die Session besteht, dann wird nur eine neue View angelegt (also Seitenaufruf) oder falls es ein neuer Nutzer ist, wird eine Session & eine View angelegt
- in der Session werden folgende Daten gespeichert:
sessionUUID, website_id, website, language, country, browser, os, device, screen, referrer (country, browser und device, werden mit Funktionen den VerifyData-Services ermitteln
- und in der View wird von diesen Daten nur der path gespeichert

- ZULETZT: dieser Vorgang wiederholt sich bei jedem Aufruf eines Nutzers
-->

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

<!--
- schauen wir uns zuletzt noch den Ablauf an, wie die Daten von der Datenbank zur Kachel kommen ... (klick)
- also wie wir eben gesehen haben werden die Analysedaten in der Session und View-Tabelle gespeichert, auf die wir jetzt zugreifen müssen
- und gestartet wird das bei der Universal Kachel, die die getData Funktion aufruft und die Kachel bekommt ja mehrere Props, welche als Parameter übergeben werden
- diese Funktion sendet einen GET-Request an die API, des DeployData-Services und anhand der Request-Query (grün url) 
wird die passende Funktion des DeployData-Services für den Kacheltyp aufgerufen und dort findet dann die Berechnung statt
- aber zuvor muss noch mithilfe des PIs die richtige Datenbank-Tabelle ausgewählt werden, und zwar enthält die View-Tabelle die Analysedaten für die Seitenaufrufe und Nutzerpfade und anderen PIs nutzen die Session-Tabelle
- anschließend findet die Datenbankabfrage unter Berücksichtigung der WebsiteID & Zeitspanne statt, den man mithilfe der user_id abfragt
- und bei einfachen Berechnungen findet dann bereits bei der Abfrage die Berechnung statt, weil hierbei nur gezählt wird
- andernfalls wird zusätzlich JavaScript verwendet, bspw. bei der durchschnittlichen Verweildauer oder Absprungrate, da hierbei zusätzlich neben dem Zählen einfache Rechenregeln stattfinden
- und zuletzt werden die Daten im passenden Format zurück zur Kachel gegeben
-->

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

<!--
- Jetzt kommen wir langsam zu Ende
- Hier seht ihr meinen verwendeten Tech-Stack
- Ich gehe jetzt einmal nur auf die wichtigsten ein
- Next.js, was ich im Front- und Backend eingesetzt habe
- MySQL wurde als Datenbank genutzt 
- und für die Kommunikation zwischen db und Backend
habe ich Prisma verwendet
-->

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

---
---
---
---
