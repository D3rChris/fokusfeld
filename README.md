# Fokusfeld

**Browserbasiertes Training bei Gesichtsfeldausfällen – visuelle Exploration, Sakkaden- und Blicktraining**

Fokusfeld ist eine kostenlose, browserbasierte Trainingsanwendung für Menschen mit Einschränkungen des Gesichtsfeldes. Die Anwendung stellt verschiedene Übungen zur Verfügung, mit denen unter anderem visuelle Exploration, Blicksteuerung, Sakkaden und Hand-Auge-Koordination trainiert werden können.

Die Anwendung läuft vollständig im Webbrowser und benötigt weder Installation noch Benutzerkonto oder Server.

> **Wichtiger Hinweis:** Fokusfeld ist kein Medizinprodukt, kein diagnostisches Verfahren und keine klinisch validierte Therapieanwendung. Die Anwendung ersetzt keine ärztliche, therapeutische oder rehabilitative Behandlung.

---

## Hintergrund des Projekts

Fokusfeld entstand aus persönlichen Erfahrungen während einer dreiwöchigen Rehabilitationsmaßnahme.

Während dieser Zeit lernte ich verschiedene Trainingsmethoden und Übungen für Gesichtsfeldausfälle und die visuelle Exploration kennen. Aus diesen Erfahrungen entstand die Idee, eine frei zugängliche browserbasierte Trainingsmöglichkeit zu entwickeln, die ohne spezielle Software oder kostenpflichtige Plattform genutzt werden kann.

Die Anwendung wurde mit Unterstützung von **OpenAI ChatGPT und Codex** entwickelt. Inhalte, Trainingsabläufe und Bedienkonzept basieren unter anderem auf meinen persönlichen Erfahrungen mit verschiedenen Übungen während der Rehabilitation.

Im Verlauf der Entwicklung wurde die Anwendung außerdem Therapeuten gezeigt und deren Rückmeldungen wurden teilweise in die Weiterentwicklung einbezogen.

**Dieses Feedback stellt ausdrücklich keine klinische Prüfung oder medizinische Validierung der Anwendung dar.**

---

## Trainingsarten

Fokusfeld enthält derzeit sechs verschiedene Trainingsbereiche:

### 1. Grenzzonen-Stimulation

Bei zentraler Fixation erscheinen Lichtreize im peripheren Gesichtsfeld. Dabei können unter anderem Reizdauer und weitere Parameter angepasst werden.

### 2. Blicksprung-Exploration

Trainiert gezielte Blicksprünge in Richtung des betroffenen Gesichtsfeldes. Angezeigte Ziele müssen erkannt und entsprechend beantwortet werden.

### 3. Figur-Hintergrund-Suche

Ein Symbol wird innerhalb eines visuellen Musters dargestellt und muss lokalisiert bzw. einer Bildschirmseite zugeordnet werden.

### 4. Optokinetischer Reiz-Scan (OKN)

Bewegte visuelle Muster erzeugen einen kontinuierlichen visuellen Reiz, während eine zentrale Fixation beibehalten wird.

### 5. VOR-Fixationstraining

Training zur Aufrechterhaltung der visuellen Fixation während rhythmischer Kopfbewegungen. Die Anwendung kann dabei eine zeitliche bzw. akustische Orientierung vorgeben.

### 6. Hand-Auge-Zieltippen

Auf dem Bildschirm erscheinende Ziele werden mit Maus oder Touch-Eingabe getroffen. Dabei können unter anderem Reaktionszeit und Treffergenauigkeit ausgewertet werden.

---

## Individuelle Einstellungen

Verschiedene Parameter des Trainings können angepasst werden, beispielsweise:

- betroffenes Gesichtsfeld (links/rechts)
- Betrachtungsabstand
- Bildschirmgröße
- Punkt- bzw. Zielgröße
- Reizdauer
- Helligkeit
- trainingsabhängige Parameter

Durch die Angabe von Bildschirmgröße und Betrachtungsabstand können Darstellungen an die jeweilige Trainingssituation angepasst werden.

---

## Trainingsauswertung

Fokusfeld kann abhängig von der jeweiligen Übung verschiedene Werte erfassen und darstellen, beispielsweise:

- Anzahl der Trainingsdurchgänge
- Trainingsdauer
- Trefferquote
- Reaktionszeit
- Fixationsfehler
- räumliche Trefferverteilung

Die Ergebnisse dienen ausschließlich der persönlichen Orientierung innerhalb der Anwendung.

Sie stellen **keine medizinische Messung oder diagnostische Beurteilung des Gesichtsfeldes** dar.

---

## Datenschutz

Fokusfeld benötigt kein Benutzerkonto und keinen zentralen Server zur Speicherung der Trainingsdaten.

Trainingsdaten und Einstellungen werden lokal im Browser des verwendeten Geräts gespeichert.

Dadurch können beispielsweise bisherige Trainingseinheiten und Einstellungen beim nächsten Aufruf wieder zur Verfügung stehen.

Beim Löschen der Browserdaten können diese lokal gespeicherten Informationen verloren gehen.

---

## Verwendung

Fokusfeld ist als einfache Webanwendung aufgebaut.

Die Anwendung kann direkt über die bereitgestellte GitHub-Pages-Version verwendet werden.

Alternativ kann das Repository heruntergeladen und die Datei

`index.html`

lokal in einem modernen Webbrowser geöffnet werden.

Für die eigentliche Trainingsanwendung ist keine Installation erforderlich.

---

## Medizinischer Hinweis

Fokusfeld wurde **nicht klinisch validiert** und ist **kein Medizinprodukt**.

Die Anwendung dient nicht zur:

- Diagnose von Gesichtsfeldausfällen
- Bestimmung oder Vermessung eines Gesichtsfelddefekts
- Beurteilung eines Krankheitsverlaufs
- Entscheidung über medizinische oder therapeutische Maßnahmen
- Ersetzung einer professionellen Rehabilitation oder Therapie

Insbesondere können die innerhalb der Anwendung dargestellten Ergebnisse nicht mit einer professionellen Gesichtsfeldmessung, beispielsweise einer Perimetrie, gleichgesetzt werden.

Das Training sollte im Sitzen und in einer sicheren Umgebung durchgeführt werden.

Bei Müdigkeit, Schwindel, Kopfschmerzen, Übelkeit, visueller Überlastung oder anderem Unwohlsein sollte das Training beendet bzw. pausiert werden.

Bei Unsicherheit sollte die Verwendung mit dem behandelnden Arzt, Therapeuten oder Rehabilitationsteam abgestimmt werden.

---

## Technischer Hintergrund

Fokusfeld wurde als browserbasierte Anwendung mit HTML, CSS und JavaScript entwickelt.

Ein wesentliches Ziel des Projekts ist eine möglichst geringe technische Einstiegshürde:

- keine Installation
- kein Benutzerkonto
- kein Backend erforderlich
- lokale Speicherung der Trainingsdaten
- Bedienung per Maus, Tastatur oder Touch
- Nutzung auf unterschiedlichen Bildschirmgrößen

Die Entwicklung erfolgte mit Unterstützung von **OpenAI ChatGPT und Codex**.

Der Einsatz KI-gestützter Entwicklungswerkzeuge stellt keine medizinische oder wissenschaftliche Validierung der Anwendung dar.

---

## Projektstatus

Fokusfeld ist ein frei verfügbares Open-Source-Projekt in aktiver Entwicklung.

Fehler, unvollständige Funktionen oder ungeeignete Trainingsparameter können trotz sorgfältiger Entwicklung nicht ausgeschlossen werden.

Hinweise, Fehlerberichte und Verbesserungsvorschläge sind willkommen.

---

## Lizenz

Fokusfeld ist freie Open-Source-Software und wird unter der
**GNU General Public License Version 3 (GPLv3)** veröffentlicht.

Das bedeutet unter anderem:

- Fokusfeld darf kostenlos verwendet werden.
- Der Quellcode darf eingesehen und verändert werden.
- Veränderte Versionen dürfen weitergegeben werden.
- Auch eine kommerzielle Nutzung ist grundsätzlich erlaubt.
- Bei der Weitergabe gelten die Bedingungen der GPLv3.
- Weitergegebene bzw. abgeleitete Versionen müssen ebenfalls unter den
  Bedingungen der GPL zugänglich gemacht werden.

Die Urheberschaft des ursprünglichen Projekts bleibt erhalten.

Copyright © 2026 Christian Sontheimer

Die vollständigen Lizenzbedingungen befinden sich in der Datei [`LICENSE`](LICENSE).

---

## Autor

**Christian Sontheimer**

Konzeption und Entwicklung von Fokusfeld  
mit Unterstützung von OpenAI ChatGPT und Codex.

---

## Beiträge zum Projekt

Fehlerberichte, Verbesserungsvorschläge und fachliches Feedback sind ausdrücklich willkommen.

Dafür können die Issues und weiteren Funktionen dieses GitHub-Repositories verwendet werden.

Insbesondere Rückmeldungen aus Therapie, Rehabilitation, Forschung und von Betroffenen können bei der Weiterentwicklung des Projekts hilfreich sein.
