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
- Als Erstes gebe ich einen Überblick über mein Thema und mein angestrebtes Ziel
- Dann stelle ich die Zielgruppe vor und zeige anhand des Interaktionskonzepts, wie die Website-Analyse-Plattform aufgebaut ist
- danach zeige ich das technische Konzept und erkläre ein paar Abläufe, wie die einzelnen Instanzen miteinander zusammenarbeiten
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
- Seitenaufrufe: Gesamtzahl der Seitenaufrufe einer Website
- Aktive Nutzer: Anzahl der Nutzer, die in Echtzeit auf der Website sind
- Unterschiedliche Nutzer: Im Gegensatz zu den Seitenaufrufen, werden hier nur unterschiedliche Nutzer gezählt
- Traffic-Quellen: sind verschiedene Kanäle, über die die Website aufgerufen wird. Zum Beispiel Suchmaschinen, Social Media oder andere Websites
- Nutzerpfade: welche Seiten werden von den Nutzern am meisten aufgerufen
- Standorte: woher kommen die Nutzer (aus welchem Land)
- Geräteinformationen: welche Geräteart, Betriebssystem, Auflösung und die Browserversion werden von den Nutzern verwendet
- Absprungrate: die Rate beschreibt die Anzahl der Nutzer, die die Website bereits nach einer Seite direkt wieder verlassen
- durchschnittliche Verweildauer: die durchschnittliche Zeit, die ein Nutzer auf der Website verbringt

- Beispiel-Ziel: Der Website-Betreiber möchte in den nächsten 6 Monaten 100 Klicks aus Deutschland über Instagram generieren. Hierfür könnten die PIs Traffic-Quellen und Standort als KPIs betrachtet werden.
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
- man sollte aber nicht vergessen, dass der Datenschutz kein Problem, sondern ein Grundrecht der Nutzer ist
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
- dafür gibt es nun 2 Möglichkeiten das Ganze umzusetzen
-->

---
title: Einführung in das Thema
hideInToc: true
---
# Einführung in das Thema
## Tracking ohne Einwilligung – ohne Personenbezug
- Daten, die automatisch beim Aufruf mitgeliefert werden
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

- Wiedererkennbarkeit, aber keine Identifizierung
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
title: Einführung in das Thema
hideInToc: true
---

# Einführung in das Thema
## Tracking ohne Einwilligung – mit vernünftiger Erwartung des Nutzers

- keine Überraschung im gewissen Maße analysiert zu werden
- unerwartet sind bspw. das Aufzeichnen von Maus-Bewegungen
- erwartungsgemäß sind bspw. die Analyse der Seitenbesuche oder Aufenthaltsdauer
<br/>
<br/>

### Technische Auflagen der DSGVO
<div class="flex">
  <div class="flex-column w-1/2">
    <ul>
      <li>anonymisierte IP-Adresse</li>
      <li>Do-Not-Track berücksichtigen</li>
      <!-- <li>Auftragsverarbeitungsvertrag</li> -->
      <!-- <li>keine Datenweitergabe an Dritte</li> -->
      <!-- <li>Kombination mit anderen Daten ist untersagt</li> -->
      <li>keine persönliche Identifikation</li>
      <!-- <li>Widerruf über Datenschutzerklärung</li> -->
    </ul>
  </div>
  <div class="flex-column w-1/2">
    <ul>
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
- Dafür gibt es noch einmal eine Reihe an zusätzlichen Auflagen der DSGVO, die eingehalten werden müssen. Ich gehe jetzt einmal nur auf die technischen Auflagen ein, denn es gibt auch noch weitere für den Website-Betreiber (Auftragsverarbeitungsvertrag, Widerruf über Datenschutzerklärung)

- die IP-Adresse muss anonymisiert werden, da der Nutzer halt nicht identifiziert werden darf
- und es muss auch noch das Do-Not-Track-Protokoll berücksichtigt werden, welcher der Nutzer in den Browsereinstellungen aktivieren kann
- der Nutzer darf in keinster Weise identifiziert werden
-->

---
title: Einführung in das Thema
hideInToc: true
---

# Einführung in das Thema 
## Tracking ohne Einwilligung – Problem mit den Adblockern

- Desktop 290 Mio. Menschen
- mobile Endgeräte 560 Mio. Menschen
- blockieren standardmäßig namhafte URLs und Skript-Namen
- unabhängig von First- oder Third-Party-Request
- First-Party-Requests sollten bevorzugt werden
- Hosting auf Subdomain

<Footer />

<!--
- Bei dem Tracking ohne Einwilligung gibt es aber ein Problem mit den Adblockern
- Adblocker sind bei vielen Nutzern sehr beliebt, da sie unter anderem Werbung blockieren
- auf Desktop-Rechnern sind das 290 Millionen Menschen und auf mobilen Endgeräten 560 Millionen Menschen
- und Adblocker blockieren mittlerweile aber nicht nur Werbung, sondern standardmäßig namhafte URLs und Skript-Namen (bspw. wenn man Google Analytics nutzt wird das Skript von den Google Servern geladen und hierbei kann dann die Domain blockiert sein; oder wenn man die Open Source Analyse Plattform Matomo nutzt und hierbei es sogar selbst hostet, ist die Domain eher nicht das Problem, sondern der bekannte Skript-Name namens piwik.js, welcher dann blockiert wird)
- und das unabhängig davon, ob es sich um First- oder Third-Party-Requests handelt (weil es halt URLs und Skript-Namen filtert/blockiert)
- aber First-Party-Requests sollten trotzdem bevorzugt werden, da diese ein besseres Ansehen haben und die Adblocker unterschiedliche Voreinstellungen haben 
- d. h. die Analyse-Plattform sollte bspw. auf einer Subdomain gehostet werden, um Third-Party-Requests zu vermeiden
-->

---
title: Zielgruppe
hideInToc: false
---

# Zielgruppe

- Website-Betreiber, die ohne Cookies und Einwilligungspflicht analysieren möchten
- Datenschutz fokussiert
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
- die bspw. eine Website und vielleicht sogar Websites auf der Subdomain betreiben und diese analysieren möchten
- wenn sie bspw. unterschiedliche Top-Level-Domains haben, dann sollten sie für jede dieser Domains eine eigene Analyse-Plattform einrichten, damit Third-Party-Requests vermieden werden
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
- Seitenaufrufe, einzigartige Nutzer, durchschnittliche Verweildauer und die Absprungrate
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
- und außerdem müssen die Analysedaten in einem bestimmten passend für den Kacheltyp formatiert sein -> Unterpunkte, number; Objekt, Array aus mehreren Objekten
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
- einfache und komplexe Berechnungen der Performance Indikatoren
- schnell erweiterbar durch neue Kacheltypen

<Footer />

<style>
  .slidev-code-wrapper pre {
    @apply bg-white dark:bg-black
  }
</style>

<!--
- Schauen wir uns das jetzt einmal im technischen Konzept an, und zwar gibt es für die unterschiedlichen Kacheltypen eine Universal Kachel Komponente, bestehend aus verschiedenen Parametern, website_id, user_id, kacheltyp, Performance-Indikator und einen Boolean Wert für die Internationalisierung
- solch eine Kachel stellt eine eigene Berechnungsanfrage an folgende API
- und anhand des Kacheltypen wird dabei die passende Funktion im Backend aufgerufen
- und in diesen Funktionen findet dann die Berechnung der Performance Indikatoren statt, meistens direkt bei der Datenbankabfrage, aber bei komplexeren Berechnungen wird zusätzlich Javascript eingesetzt (komplexere Berechnung finden bspw. bei der durchschnittlichen Verweildauer oder Absprungrate statt, da hierbei nicht nur die einzelnen Tabelleneinträge gezählt werden)
- durch die Universal Kachel Komponente können somit schnell neue Kacheltypen hinzugefügt werden und bei einfachen Berechnungen kann die vorhandene Funktion wiederverwendet werden
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
- Überprüfung, ob Do-Not-Track aktiv ist
- Browserdaten werden extrahiert und in JSON-Objekt gespeichert
- Objekt wird an API des VerifyData-Services gesendet

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
  <li> WebsiteID, anonymisierter IP, UserAgent, Timestamp und Salt </li>
- anhand der SessionUUID, wird neue Session & View oder nur eine View erstellt

<Footer />

<style>
  .slidev-code-wrapper pre {
    @apply bg-white dark:bg-black
  }
</style>

<!--
- Jetzt werde ich den Ablauf vom User über das Backend zur Datenbank erklären
- Der Website-Betreiber platziert das TrackingData-Skript auf seiner Website im Head-Tag
- und dieses wird bei jedem Seitenaufruf ausgeführt und sendet die Daten an das Backend
- Die Daten kommen dann so, wie hier im JSON zu sehen, im Backend an und werden dort verifiziert und in der Datenbank gespeichert
-->

---
title: Technisches Konzept
hideInToc: true
---
# Technisches Konzept
## von Datenbank zur Kachel im Frontend
<div v-click-hide class="absolute z-10 right-5">
  <img class="w-100 dark:hidden block" src="/images/architecture-services.png" /> 
  <img class="w-100 hidden dark:block" src="/images/architecture-services-dark.png" /> 
</div>
<div v-after class="absolute z-10 right-15 bottom-15">
  <img class="w-70 dark:hidden block" src="/images/architecture-db-to-frontend.png" /> 
  <img class="w-70 hidden dark:block" src="/images/architecture-db-to-frontend-dark.png" /> 
</div>

- DeployData-Service stellt API-Schnittstelle bereit
- Request-Query sorgt für passenden Funktionsaufruf
```javascript
`/api/data/${props.website_id}/${props.user_id}/${props.tile}/${props.indicator}/calculate`
```

- Datenbankabfrage mit Prisma unter Berücksichtigung des Zeitraums
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
