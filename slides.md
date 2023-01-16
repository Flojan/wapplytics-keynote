---
theme: apple-basic
class: text-left
highlighter: shiki
lineNumbers: false
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
drawings:
  persist: false
css: windicss
fonts:
  provider: 'none'
title: Website-Analyse-Plattform
layout: intro
hideInToc: true
routerMode: 'history'
---

# Website-Analyse-Plattform
Bachelor-Arbeit 


<div class="absolute bottom-10">
  <span class="font-700">
    Florian Schmidt // 30.01.2023
  </span>
</div>

<!-- <div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div> -->

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->
<style>
h1 {
  @apply font-regular
}  
</style>

---
title: Inhalt
hideInToc: true
---
# Inhalt 
<Toc listClass="list-disc" />

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<!--
Here is another comment.
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

---
title: Einführung in das Thema
hideInToc: true
---
# Einführung in das Thema
## Ziel mit passenden Key Performance Indikatoren

- kontinuierliche Erfolgskontrolle
- Analyse-Tool enthält viele verschiedene Performance Indikatoren
- Key Performance Indikator tragen zur Zielerreichung bei 
### Perfomance Indikatoren

<h4 class="absolute left-20 bottom-55" v-click>Seitenaufrufe</h4>
<h4 class="absolute left-60 bottom-60" v-click>Aktive User</h4>
<h4 class="absolute left-90 bottom-35" v-click>Unterschiedliche Nutzer</h4>
<h4 class="absolute left-130 bottom-50" v-click>Traffic-Quellen</h4>
<h4 class="absolute left-100 bottom-65" v-click>Absprungrate</h4>
<h4 class="absolute left-30 bottom-20" v-click>Durchschnittliche Verweildauer</h4>
<h4 class="absolute left-45 bottom-40 " v-click>Nutzerpfade</h4>
<h4 class="absolute left-160 bottom-25" v-click>Standorte</h4>
<h4 class="absolute left-170 bottom-55" v-click>Geräteinformationen</h4>

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
<div v-click class="flex justify-between mt-2 mb-6">
  <span class="flex w-full justify-center">100 %</span> 
  <span class="flex w-full justify-center">30 %</span> 
  <span class="flex w-full justify-center">23 %</span> 
  <span class="flex w-full justify-center">14 %</span> 
</div>

### Page-Tagging-Methode
- JavaScript Code, welcher beim Aufruf der Website ausgeführt wird
- Verzicht auf Cookies oder sonstiges speichern auf dem Gerät des Nutzers möglich
- Kein expliziter Zugriff auf das Gerät des Nutzers
<!-- zwei Möglichkeiten diese Methode umzusetzen -->

---
title: Tracking ohne Einwilligung
hideInToc: true
---
# Tracking ohne Einwilligung
## ohne Personenbezug
- Daten die automatisch beim Aufruf mitgeliefert werden
- Bsp. IP-Adresse, Referrer, UserAgent
- Referrer & UserAgent stellen keinen Personenbezug dar
- IP-Adresse muss zuvor erst anonymisiert werden
- Generierung eines Hashwertes
<!-- Falls die Website-Analyse nicht ohne Personenbezug stattfinden kann, bietet die DSGVO, die Möglichkeit, die Einwilligung zu umgehen  -->

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



---
title: Aufbau der Plattform
hideInToc: false
---
# Aufbau der Plattform
---
title: Technischer Ablauf
hideInToc: false
---
# Technischer Ablauf
---
title: Tech-Stack
hideInToc: false
---
# Tech-Stack
---
title: Fazit und Ausblick
hideInToc: false
---
# Fazit und Ausblick



