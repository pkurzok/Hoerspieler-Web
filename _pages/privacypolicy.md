---
layout: page
title: Datenschutzerklärung
include_in_header: false
---

**Stand:** 13. September 2026

Diese Erklärung beschreibt, welche personenbezogenen Daten bei der Nutzung dieser Website
(**Teil A**) und der App **Hörspieler** (**Teil B**) verarbeitet werden, zu welchen Zwecken das
geschieht, auf welcher Rechtsgrundlage, an wen Daten weitergegeben werden und welche Rechte Ihnen
zustehen.

## 1. Verantwortlicher und Kontakt

Verantwortlicher im Sinne der Datenschutz-Grundverordnung (DSGVO) ist:

```
Peter Kurzok Photography
c/o MDC#990
Welserstraße 3
87463 Dietmannsried
Deutschland
```

E-Mail: <!--email_off-->[hoerspieler@peterkurzok.de](mailto:hoerspieler@peterkurzok.de)<!--/email_off-->

Ein Datenschutzbeauftragter ist nicht bestellt, da die gesetzlichen Voraussetzungen dafür nicht
vorliegen. Bitte richten Sie alle Anliegen zum Datenschutz an die oben genannte Adresse.

## 2. Überblick

Hörspieler ist eine iOS-App, mit der Kinder Hörspiele und Hörbücher aus Apple Music hören können.
Sie richtet sich ausdrücklich an Kinder und wird in aller Regel von einem Elternteil eingerichtet.

Es gibt **keinen eigenen Server** des Anbieters, auf dem Ihre Daten gespeichert werden. Das
bedeutet aber **nicht**, dass keine Daten übertragen werden: Die App nutzt Dienste Dritter, an die
Daten übermittelt werden. Welche das sind, steht vollständig in Abschnitt 6.

Der überwiegende Teil Ihrer Daten — Favoriten, zuletzt gehörte Alben, Wiedergabepositionen und alle
Einstellungen — bleibt auf dem Gerät und wird, sofern Sie iCloud nutzen, ausschließlich in Ihre
eigene private iCloud synchronisiert.

Diese Fassung ersetzt die Erklärung vom 3. Januar 2024 vollständig. Sie beschreibt sämtliche
Dienste, an die tatsächlich Daten übermittelt werden; ältere Fassungen waren in diesem Punkt nicht
mehr zutreffend.

---

# Teil A – Nutzung der Website

## 3. Hosting, Auslieferung und Server-Logs

Diese Website wird als statische Seite über **GitHub Pages** (GitHub, Inc., 88 Colin P Kelly Jr
Street, San Francisco, CA 94107, USA) bereitgestellt und über das Content-Delivery-Network von
**Cloudflare** (Cloudflare, Inc., 101 Townsend St, San Francisco, CA 94107, USA) ausgeliefert.

Beim Aufruf einer Seite werden technisch zwingend Daten übertragen und in Server-Logs verarbeitet,
insbesondere:

* die IP-Adresse des anfragenden Geräts,
* Datum und Uhrzeit des Zugriffs,
* die aufgerufene Adresse,
* der übermittelte Browsertyp (User-Agent) und die Referrer-URL.

*Zweck:* technisch fehlerfreie Auslieferung, Sicherheit und Abwehr von Angriffen.
*Rechtsgrundlage:* Art. 6 Abs. 1 lit. f DSGVO — berechtigtes Interesse an einem sicheren und
verfügbaren Angebot.

**Es werden keine Cookies gesetzt, keine Zählpixel eingebunden, keine Reichweitenmessung
durchgeführt und keine Formulare angeboten.** Eine Analyse Ihres Nutzungsverhaltens findet auf
dieser Website nicht statt.

## 4. Von Dritten nachgeladene Inhalte

Die Seiten binden einige Bestandteile von fremden Servern ein. Beim Laden dieser Bestandteile wird
Ihre IP-Adresse technisch zwingend an den jeweiligen Anbieter übertragen — auch dann, wenn Sie mit
dem betreffenden Anbieter sonst nichts zu tun haben.

| Eingebundener Inhalt | Anbieter | Übermittelte Daten |
| --- | --- | --- |
| jQuery (JavaScript-Bibliothek) von `ajax.googleapis.com` | Google Ireland Ltd. / Google LLC, USA | IP-Adresse, User-Agent, Referrer |
| Font Awesome (Symbolschriftart) von `use.fontawesome.com` | Fonticons, Inc., USA (ausgeliefert über Fastly) | IP-Adresse, User-Agent, Referrer |
| Abruf der App-Store-Angaben über `itunes.apple.com/lookup` | Apple Inc., One Apple Park Way, Cupertino, CA 95014, USA | IP-Adresse, User-Agent |

*Zweck:* Darstellung der Seite sowie Anzeige aktueller App-Store-Angaben (Name, Preis, Symbol).
*Rechtsgrundlage:* Art. 6 Abs. 1 lit. f DSGVO — berechtigtes Interesse an einer funktionsfähigen
und einheitlich gestalteten Darstellung.

Zusätzlich enthält die Seite ein sogenanntes *Smart App Banner*
(`<meta name="apple-itunes-app">`). Dieses wird von iOS selbst ausgewertet; die Anfrage an Apple
geht dabei von Ihrem Gerät aus, nicht von dieser Website.

Diese Einbindungen wären technisch vermeidbar, indem die Dateien selbst ausgeliefert werden.
Solange sie bestehen, werden sie hier offengelegt.

---

# Teil B – Nutzung der App

## 5. Verarbeitungen in der App im Einzelnen

### 5.1 Daten, die das Gerät nicht verlassen

Folgende Daten werden ausschließlich lokal auf Ihrem Gerät gespeichert und **nicht** an den
Anbieter übermittelt:

* Favoriten (gemerkte Interpreten) und zuletzt gehörte Alben samt Wiedergabeposition,
* sämtliche Einstellungen (Suche, Filter, Sprachausgabe, Demomodus, Ein- und Ausschalter für
  Statistik und Absturzberichte),
* die Kindersicherung: das eingestellte Tages- und Wochenlimit, die bereits gehörte Zeit des
  laufenden Tages und der laufenden Woche, eine gegebenenfalls erteilte Freigabe (längstens bis
  Mitternacht) sowie — falls gesetzt — der Eltern-PIN. Der PIN wird **nicht im Klartext** gespeichert, sondern
  nur als kryptografische Prüfsumme mit Zufallswert (SHA-256 mit Salt); die eingegebenen Ziffern
  verlassen das Gerät zu keiner Zeit und werden auch lokal nicht aufbewahrt,
* der Zwischenspeicher für Albumcover und für erzeugte Sprachausgabe-Dateien,
* der lokale Suchindex (Spotlight) sowie Hinweise der App.

Beim Löschen der App werden diese Daten vom Gerät entfernt.

### 5.2 Apple Music / MusicKit

Die App greift auf Ihr Apple-Music-Konto zu, um Inhalte zu suchen, abzuspielen und Cover
darzustellen. Dazu benötigt sie Ihre Freigabe für „Medien & Apple Music“, die iOS separat abfragt.
Suchbegriffe, Wiedergabevorgänge, der Status Ihres Abonnements und Coveranfragen werden dabei an
**Apple** übermittelt.

*Zweck:* Kernfunktion der App.
*Rechtsgrundlage:* Art. 6 Abs. 1 lit. b DSGVO — Erfüllung des Nutzungsvertrags; ohne diese
Verarbeitung ist die App funktionslos.

Für die Verarbeitung durch Apple gilt zusätzlich die Datenschutzerklärung von Apple.

### 5.3 Synchronisierung über iCloud / CloudKit

Wenn Sie auf Ihrem Gerät bei iCloud angemeldet sind, werden Favoriten, zuletzt gehörte Alben und
Wiedergabepositionen über **Apple iCloud (CloudKit)** in Ihre **private** iCloud-Datenbank
synchronisiert, damit sie auf Ihren weiteren Geräten zur Verfügung stehen. Der Anbieter hat auf
diese Datenbank **keinen Zugriff**.

*Zweck:* geräteübergreifende Nutzung.
*Rechtsgrundlage:* Art. 6 Abs. 1 lit. b DSGVO.

Sie können die Synchronisierung jederzeit unterbinden, indem Sie iCloud für Hörspieler in den
iOS-Systemeinstellungen deaktivieren.

### 5.4 Käufe über den App Store (StoreKit)

Für In-App-Käufe (Pro-Funktionen, freiwillige Unterstützung) wird **Apple StoreKit** verwendet. Der
Kaufvorgang selbst läuft vollständig bei Apple; der Anbieter erhält keine Zahlungsdaten. Die App
liest lediglich aus, ob ein Kauf vorliegt und mit welcher App-Version die App ursprünglich erworben
wurde (`originalAppVersion`) — Letzteres, um Bestandskunden die Pro-Funktionen dauerhaft zu
erhalten.

*Zweck:* Abwicklung von Käufen, Bestandsschutz.
*Rechtsgrundlage:* Art. 6 Abs. 1 lit. b DSGVO.

### 5.5 Sprachausgabe

Die App kann Interpreten- und Albumtitel vorlesen, damit sich auch Kinder zurechtfinden, die noch
nicht lesen können. Dafür stehen zwei Verfahren zur Verfügung:

* **Apple-Sprachausgabe (lokal):** arbeitet vollständig auf dem Gerät. Es wird nichts übertragen.
* **Google Cloud Text-to-Speech (Voreinstellung):** Der **vorzulesende Titel** — also der Name des
  Interpreten oder des Albums — wird zusammen mit Sprache und gewünschtem Stimmgeschlecht an
  **Google** (Google LLC, 1600 Amphitheatre Parkway, Mountain View, CA 94043, USA) übertragen, das
  daraus eine Audiodatei erzeugt. Diese Datei wird auf dem Gerät zwischengespeichert, sodass
  derselbe Titel nicht erneut übertragen wird.

*Zweck:* Vorlesefunktion.
*Rechtsgrundlage:* Art. 6 Abs. 1 lit. b DSGVO.

**Sie können die Übertragung vollständig vermeiden**, indem Sie unter *Einstellungen ›
Sprachausgabe* die Apple-Sprachausgabe wählen.

### 5.6 Nutzungsstatistik (Mixpanel)

*Zweck:* Zu erkennen, welche Funktionen der App tatsächlich genutzt werden, um Entwicklung und
Verbesserung darauf auszurichten.

*Verarbeitete Daten:* Bezeichnungen ausgelöster Ereignisse (z. B. „Einstellungen geöffnet“,
„Favorit hinzugefügt“) samt zugehöriger technischer Merkmale (etwa welches Sprachausgabe-Verfahren
verwendet wurde, ob ein Filter aktiv ist, die Anzahl der Favoriten), die ursprünglich gekaufte
App-Version sowie eine **gerätegebundene Kennung** (die von Apple vergebene *Vendor-ID*), die die
Ereignisse eines Geräts zusammenführt.

Zur Kindersicherung wird ausschließlich übermittelt, **ob** ein Tages- oder Wochenlimit ein- oder
ausgeschaltet wurde, **welches** der beiden es war, ob ein PIN gesetzt ist, und dass eine Freigabe
genutzt wurde — ohne Angabe, ob für den Rest des Tages oder für einige Minuten. **Nicht übermittelt** werden die eingestellte Dauer, die tatsächlich
gehörte Zeit und der PIN selbst — wie lange ein Kind hören darf, ist eine Erziehungsentscheidung
und keine technische Angabe über die App.

**Diese Kennung ist pseudonym, nicht anonym.** Sie ist keinem Namen, keiner E-Mail-Adresse und
keinem Konto zugeordnet — die App kennt nichts dergleichen —, bleibt aber eine personenbezogene
Angabe im Sinne der DSGVO. Sie wird zurückgesetzt, sobald Sie alle Apps dieses Anbieters von Ihrem
Gerät entfernen.

**Nicht übermittelt werden Inhalte:** weder Suchbegriffe noch die Namen der Interpreten oder Alben,
die Sie hören. Ein früher mitgesendeter vorgelesener Titel wurde entfernt.

*Empfänger:* Mixpanel, Inc., 1 Front Street, San Francisco, CA 94111, USA. Die Daten werden an das
**europäische Rechenzentrum** (`api-eu.mixpanel.com`) gesendet und dort gespeichert.

*Rechtsgrundlage:* Art. 6 Abs. 1 lit. f DSGVO — berechtigtes Interesse. Die Abwägung: Der Anbieter
hat ein berechtigtes Interesse daran zu erkennen, welche Funktionen genutzt werden, weil sich eine
App ohne diese Kenntnis nicht sinnvoll weiterentwickeln lässt. Dem stehen keine überwiegenden
Interessen entgegen, weil ausschließlich technische Nutzungsereignisse und eine zurücksetzbare
Gerätekennung verarbeitet werden — keine Inhalte, keine Kontaktdaten und keine Verknüpfung mit
Daten Dritter —, weil die Verarbeitung in der EU stattfindet und weil ihr **jederzeit und ohne
Nachteil widersprochen** werden kann.

**Widerspruch / Abschalten:** *Einstellungen › Rechtliches › Datenanalyse & Absturzberichte ›
Datenanalyse erlauben*. Ab dem Ausschalten werden keine weiteren Ereignisse übermittelt.

### 5.7 Absturzberichte (Sentry)

*Zweck:* Fehler und Abstürze zu erkennen und zu beheben.

*Verarbeitete Daten:* Zeitpunkt des Absturzes, Gerätemodell, Betriebssystem- und App-Version, die
technische Aufrufkette (Stack Trace) sowie die letzten technischen Schritte in der App davor
(*Breadcrumbs*).

Die Übermittlung der IP-Adresse und personenbezogener Zusatzangaben ist im Programmcode
ausdrücklich abgeschaltet (`sendDefaultPii = false`). Hörhistorie und Favoriten sind nicht Teil
eines Absturzberichts.

*Empfänger:* Functional Software, Inc. (Sentry), 45 Fremont Street, San Francisco, CA 94105, USA.
Die Daten werden an die **europäische Region** (`ingest.de.sentry.io`, Rechenzentrum in
Deutschland) gesendet.

*Rechtsgrundlage:* Art. 6 Abs. 1 lit. f DSGVO — berechtigtes Interesse an einer stabilen,
fehlerfreien App. Da ausschließlich technische Diagnosedaten ohne Inhalts- und Kontaktbezug
verarbeitet werden, die IP-Adresse nicht übermittelt wird und ein Widerspruch jederzeit möglich
ist, überwiegen keine entgegenstehenden Interessen.

**Widerspruch / Abschalten:** *Einstellungen › Rechtliches › Datenanalyse & Absturzberichte ›
Absturzberichte senden*. Die Abschaltung wirkt sofort, nicht erst beim nächsten Start.

### 5.8 Sicherung und Wiederherstellung

Sie können Ihre Favoriten und Ihren Verlauf als Datei exportieren und wieder einspielen. Dieser
Vorgang wird ausschließlich von Ihnen ausgelöst; die Datei wird an dem von Ihnen gewählten Ort
gespeichert. Der Anbieter erhält sie nicht.

*Rechtsgrundlage:* Art. 6 Abs. 1 lit. b DSGVO.

### 5.9 Hinweis auf andere Apps (Kickstart Exchange)

*Zweck:* In der kostenlosen Version wird am unteren Ende der Übersicht **eine einzelne Karte**
angezeigt, die auf eine andere App unabhängiger Entwickler hinweist. Sie hilft, die Entwicklung
dieser App zu finanzieren.

**Wer sie sieht:** ausschließlich Nutzerinnen und Nutzer **ohne** Pro-Version. Wer Pro gekauft hat
oder aus einem früheren Kauf über Bestandsschutz verfügt, sieht keine Karte — und das Gerät nimmt
dann **überhaupt keine Verbindung** zu diesem Dienst auf.

*Verarbeitete Daten:* der Schlüssel dieser App beim Dienst, die App-Kennung (Bundle-ID), Plattform,
App- und Build-Version, die Version des eingebundenen Bausteins sowie — nur in den über den App
Store ausgelieferten Fassungen — der von Apple signierte Kaufnachweis **der App selbst** (er belegt
dem Dienst, dass die anfragende App echt ist; er betrifft die App, nicht Ihre Käufe). Beim Abruf
einer Karte kommt das **Land Ihres App-Store-Kontos** hinzu, etwa „Deutschland", damit nur Apps
gezeigt werden, die dort erhältlich sind. Ob eine Karte gesehen oder angetippt wurde, wird als Zahl
zurückgemeldet.

**Nicht übermittelt werden:** keine Werbe-ID, keine Nutzer- oder Gerätekennung, kein Standort und
keine Inhalte — weder Suchbegriffe noch die Namen der Interpreten oder Alben, die Sie hören. Der
Dienst vermittelt zwischen **Apps**, nicht zwischen Personen; es entsteht kein Profil, und es findet
kein anbieterübergreifendes Tracking statt. Deshalb fragt die App auch nicht nach einer
Tracking-Erlaubnis: es gibt nichts zu verfolgen.

*Empfänger:* Hudson Heavy Industries Ltd, 37 Great Pulteney Street, Bath, BA2 4DA, Vereinigtes
Königreich (Handelsregisternummer 11883499), Betreiberin von *Kickstart Exchange*
(`api.kickstart.tools`). Die Auslieferung erfolgt nach Angabe des Anbieters über das Netz von
Cloudflare.

*Rechtsgrundlage:* Art. 6 Abs. 1 lit. f DSGVO — berechtigtes Interesse. Die Abwägung: Der Anbieter
hat ein berechtigtes Interesse daran, die kostenlose Version zu finanzieren, ohne dafür Daten über
die Nutzerinnen und Nutzer zu erheben. Dem stehen keine überwiegenden Interessen entgegen, weil
ausschließlich Angaben über die **App** übermittelt werden und keine einzige Angabe über die Person
davor — keine Kennung, kein Standort, keine Inhalte —, weil daraus kein Profil entstehen kann und
weil die Anzeige durch den Kauf der Pro-Version dauerhaft entfällt.

**Abschalten:** Die Pro-Version entfernt die Karte vollständig; ab dann werden keine Daten mehr an
diesen Dienst übermittelt. Ein Widerspruch nach Art. 21 DSGVO ist unabhängig davon jederzeit unter
der in Abschnitt 1 genannten Adresse möglich.

---

## 6. Empfängerübersicht

| Empfänger | Bereich | Daten | Zweck | Rechtsgrundlage |
| --- | --- | --- | --- | --- |
| Cloudflare, Inc. (USA) | Website | IP-Adresse, Zugriffsdaten | Auslieferung, Sicherheit | Art. 6 (1) f |
| GitHub, Inc. (USA) | Website | IP-Adresse, Server-Logs | Hosting | Art. 6 (1) f |
| Google LLC (USA) | Website | IP-Adresse, User-Agent | Auslieferung von jQuery | Art. 6 (1) f |
| Fonticons, Inc. (USA) | Website | IP-Adresse, User-Agent | Auslieferung der Symbolschrift | Art. 6 (1) f |
| Apple Inc. (USA) | Website | IP-Adresse | Abruf der App-Store-Angaben | Art. 6 (1) f |
| Apple Inc. (USA) | App | Suchbegriffe, Wiedergabe, Abo-Status, Coveranfragen | Apple Music / MusicKit | Art. 6 (1) b |
| Apple Inc. (USA) | App | Favoriten, Verlauf, Wiedergabepositionen | Synchronisierung über Ihre private iCloud | Art. 6 (1) b |
| Apple Inc. (USA) | App | Kaufvorgänge, ursprüngliche App-Version | Käufe, Bestandsschutz | Art. 6 (1) b |
| Google LLC (USA) | App | vorzulesender Titel, Sprache, Stimmgeschlecht | Sprachausgabe (abschaltbar) | Art. 6 (1) b |
| Mixpanel, Inc. (EU-Rechenzentrum) | App | Ereignisnamen, technische Merkmale, Vendor-ID | Nutzungsstatistik (widersprechbar) | Art. 6 (1) f |
| Functional Software, Inc. – Sentry (EU-Region) | App | Absturz- und Diagnosedaten | Stabilität (widersprechbar) | Art. 6 (1) f |
| Hudson Heavy Industries Ltd – Kickstart Exchange (Vereinigtes Königreich) | App | App-Kennung, Versionen, Kaufnachweis der App, Land des App-Store-Kontos, Einblendungs- und Klickzahlen | Hinweis auf andere Apps (entfällt mit Pro) | Art. 6 (1) f |

**Es werden keine Daten über Sie zu Werbezwecken weitergegeben.** Seit Version 1.5.1 zeigt die
kostenlose Version zwar einen Hinweis auf eine andere App (Abschnitt 5.9) — dafür werden aber
ausschließlich Angaben über **diese App** übermittelt und keine einzige über die Person, die sie
benutzt. Es werden keine Daten verkauft. Es findet kein anbieterübergreifendes Tracking statt; die
Gerätekennung aus Abschnitt 5.6 wird nicht mit Daten Dritter zusammengeführt und erreicht den
Werbedienst nicht.

## 7. Übermittlung in Drittländer

Einige der genannten Empfänger haben ihren Sitz in den **USA**. Für diese Übermittlungen gilt
Art. 44 ff. DSGVO:

* **Apple, Google, Cloudflare und GitHub (Microsoft)** sind unter dem *EU-US Data Privacy Framework*
  zertifiziert bzw. stützen die Übermittlung ergänzend auf **Standardvertragsklauseln** nach
  Art. 46 Abs. 2 lit. c DSGVO.
* **Mixpanel:** Die Daten dieser App werden in der **EU** verarbeitet und gespeichert
  (`api-eu.mixpanel.com`). Für unterstützende Zugriffe aus den USA bestehen
  Standardvertragsklauseln.
* **Sentry:** Die Daten dieser App werden in der **EU-Region** (Rechenzentrum in Deutschland)
  verarbeitet. Für unterstützende Zugriffe aus den USA bestehen Standardvertragsklauseln.
* **Kickstart Exchange** hat seinen Sitz im **Vereinigten Königreich**. Für das Vereinigte
  Königreich hat die Europäische Kommission einen **Angemessenheitsbeschluss** nach Art. 45 DSGVO
  erlassen; die Übermittlung bedarf daher keiner zusätzlichen Garantien. Die Auslieferung erfolgt
  nach Angabe des Anbieters über das Netz von Cloudflare; in welchem Land die Daten dabei gespeichert
  werden, gibt der Anbieter nicht an.

In den USA besteht nach derzeitigem Stand kein Schutzniveau, das dem der EU vollständig entspricht;
insbesondere lässt sich ein Zugriff durch US-Behörden nicht in jedem Fall ausschließen. Die
Übermittlungen zu Mixpanel und Sentry können Sie in der App abschalten (Abschnitte 5.6 und 5.7);
die Übermittlung an Google für die Sprachausgabe können Sie durch Wahl der Apple-Sprachausgabe
vermeiden (Abschnitt 5.5).

## 8. Speicherdauer

* **Auf dem Gerät gespeicherte Daten** bleiben erhalten, bis Sie sie in der App löschen oder die
  App entfernen.
* **iCloud-Daten** bleiben bestehen, bis Sie sie löschen oder die Synchronisierung beenden.
* **Absturzberichte** werden nur so lange aufbewahrt, wie sie zur Fehlersuche nützlich sind, und
  anschließend von Sentry automatisch gelöscht. Maßgeblich ist die im Sentry-Projekt eingestellte
  Aufbewahrungsfrist; sie liegt bei höchstens **90 Tagen** ab Eingang des Berichts.
* **Nutzungsstatistik** wird nur so lange aufbewahrt, wie sie für die Auswertung von
  Nutzungsverläufen über mehrere App-Versionen hinweg erforderlich ist, und anschließend von
  Mixpanel automatisch gelöscht. Maßgeblich ist die im Mixpanel-Projekt eingestellte
  Aufbewahrungsfrist.
* **Angaben zum Hinweis auf andere Apps** (Abschnitt 5.9) werden vom Anbieter nach eigener Angabe
  rund **30 Tage** aufbewahrt. Tagesbezogene Summen je App-Paar (App-Kennungen, Datum, Plattform,
  Land, Anzahl der Einblendungen und Klicks) werden ohne feste Löschfrist für Auswertungen
  aufbewahrt; sie enthalten keinen Bezug zu einer Person.
* **Server-Logs** von Cloudflare und GitHub werden nach den dortigen, kurzen Fristen gelöscht.

Die jeweils aktuell eingestellten Fristen teilen wir Ihnen auf Anfrage unter der in Abschnitt 1
genannten Adresse mit.

Nach einem Widerspruch werden keine weiteren Daten erhoben; bereits übermittelte Daten werden nach
Ablauf der jeweiligen Frist gelöscht. Auf Verlangen veranlassen wir die Löschung früher, siehe
Abschnitt 10.

## 9. Kinder

Diese App richtet sich an Kinder. Deshalb gilt hier besondere Zurückhaltung:

* Es gibt **kein Benutzerkonto**, keine Registrierung und keine Anmeldung.
* Es werden **keine Kontaktdaten** erhoben — weder Name noch E-Mail-Adresse, Telefonnummer oder
  Anschrift.
* In der kostenlosen Version wird **eine einzelne Karte** angezeigt, die auf eine andere App
  hinweist (Abschnitt 5.9). Sie steht am unteren Ende der Übersicht, unterbricht nichts, blinkt
  nicht, öffnet von sich aus nichts und ist nur zu sehen, wenn man bis dorthin scrollt. Es gibt
  **keine Werbe-IDs**, kein Profil und kein anbieterübergreifendes Tracking — an den Dienst wird
  keine einzige Angabe über das Kind übermittelt. Ein Antippen führt in den App Store, wo ein Kauf
  wie immer die Bestätigung über das Apple-Konto erfordert. Mit der **Pro-Version entfällt die
  Karte vollständig**.
* Es gibt keine Chat-, Kommentar- oder sonstige Kommunikationsfunktion.
* Die Einstellungen der App sind durch eine **Rechenaufgabe** geschützt — oder, wenn Sie einen
  eigenen **PIN** festgelegt haben, durch diesen —, damit Kinder sie nicht selbst verändern
  können. Käufe erfordern zusätzlich die Bestätigung über das Apple-Konto.
* Sie können eine **tägliche und eine wöchentliche Hörzeit** festlegen. Die dafür nötige Zählung
  findet vollständig auf dem Gerät statt; weder die eingestellte Dauer noch die gehörte Zeit werden
  an den Anbieter oder an Dritte übermittelt.

Die Entscheidung über die Nutzung der App und über die in den Abschnitten 5.6, 5.7 und 5.9
beschriebenen Verarbeitungen trifft der Inhaber der elterlichen Verantwortung (vgl. Art. 8 DSGVO). Wenden Sie
sich bitte an die in Abschnitt 1 genannte Adresse, wenn Sie die Löschung von Daten Ihres Kindes
verlangen möchten.

## 10. Ihre Rechte

Sie haben gegenüber dem Verantwortlichen folgende Rechte:

* **Auskunft** über die zu Ihnen verarbeiteten Daten (Art. 15 DSGVO),
* **Berichtigung** unrichtiger Daten (Art. 16 DSGVO),
* **Löschung** (Art. 17 DSGVO),
* **Einschränkung der Verarbeitung** (Art. 18 DSGVO),
* **Datenübertragbarkeit** (Art. 20 DSGVO),
* **Widerruf** einer erteilten Einwilligung mit Wirkung für die Zukunft (Art. 7 Abs. 3 DSGVO).

### Widerspruchsrecht nach Art. 21 DSGVO

**Sie haben das Recht, aus Gründen, die sich aus Ihrer besonderen Situation ergeben, jederzeit der
Verarbeitung Ihrer Daten zu widersprechen, die auf Grundlage von Art. 6 Abs. 1 lit. f DSGVO
erfolgt.** Das betrifft die Nutzungsstatistik (5.6), die Absturzberichte (5.7) und die
Verarbeitungen beim Betrieb der Website (Teil A).

Für die App können Sie diesen Widerspruch unmittelbar selbst ausüben, ohne uns zu kontaktieren:

> **Einstellungen › Rechtliches › Datenanalyse & Absturzberichte**
> — dort *Datenanalyse erlauben* bzw. *Absturzberichte senden* ausschalten.

Im Übrigen genügt eine formlose Nachricht an
<!--email_off-->[hoerspieler@peterkurzok.de](mailto:hoerspieler@peterkurzok.de)<!--/email_off-->. Zur Bearbeitung Ihres Anliegens
benötigen wir keine Anmeldedaten; teilen Sie uns bitte mit, welche Verarbeitung Sie betrifft.

### Beschwerderecht nach Art. 77 DSGVO

Unabhängig davon können Sie sich bei einer Datenschutz-Aufsichtsbehörde beschweren, insbesondere
bei der Behörde Ihres gewöhnlichen Aufenthaltsorts, Ihres Arbeitsplatzes oder des Orts des
mutmaßlichen Verstoßes. Für den Verantwortlichen zuständig ist:

```
Bayerisches Landesamt für Datenschutzaufsicht (BayLDA)
Promenade 18
91522 Ansbach
Deutschland
https://www.lda.bayern.de
```

## 11. Datensicherheit

Die Verbindungen zu dieser Website und zu allen genannten Diensten sind durch
Transportverschlüsselung (TLS/HTTPS) geschützt. Bitte beachten Sie, dass keine Übertragung über das
Internet und keine elektronische Speicherung vollständig sicher sein kann.

## 12. Links zu anderen Websites

Diese Website und die App enthalten Verweise auf fremde Angebote (etwa den App Store). Für deren
Inhalte und Datenverarbeitung ist der jeweilige Anbieter verantwortlich; die vorliegende Erklärung
gilt dafür nicht.

## 13. Änderungen dieser Erklärung

Diese Erklärung wird angepasst, sobald sich die beschriebenen Verarbeitungen ändern — insbesondere,
wenn ein Dienst hinzukommt oder wegfällt. Maßgeblich ist jeweils die hier veröffentlichte Fassung
mit dem oben genannten Stand.
