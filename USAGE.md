# Nutzungsanleitung: Sokratische Methode Skill

Dieser Leitfaden bietet dir detaillierte Informationen zur effektiven Nutzung des Sokratische Methode Skills mit Claude.

## Installationsmethoden

### Methode 1: Claude.ai Projekte (Empfohlen)

1. Öffne dein Claude.ai Projekt
2. Navigiere zu **Projekteinstellungen** → **Skills**
3. Klicke auf **«Benutzerdefinierten Skill hinzufügen»**
4. Lade die Datei `SKILL.md` aus diesem Repository hoch
5. Der Skill wird automatisch basierend auf Nutzerinteraktionen aktiviert

### Methode 2: Claude Desktop / API

Füge den Skill-Inhalt in deine System-Prompts oder benutzerdefinierten Anweisungen ein, wenn du Konversationen initialisieren.

## Aktivierungs-Trigger

Der Skill aktiviert sich automatisch, wenn Nutzende Folgendes ausdrücken:

### Lernabsicht
- «Erkläre mir X»
- «Hilf mir, Y zu verstehen»
- «Ich verstehe nicht, wie Z funktioniert»
- «Erkläre das Konzept von...»

### Problemlösungsbedarf
- «Ich komme bei diesem Problem nicht weiter»
- «Wie löse ich...»
- «Ich kann nicht herausfinden...»

### Kritisches Denken
- «Was soll ich tun bezüglich...»
- «Ist dieser Ansatz korrekt?»
- «Was ist der beste Weg, um...»

### Konzeptionelles Verständnis
- «Was bedeutet X?»
- «Definiere Y»
- «Wie würdest du beschreiben...»

## Betriebsmodi

Der Skill passt sich an vier verschiedene Kontexte an:

### 1. Pädagogischer Modus (Standard)

**Am besten für:** Akademisches Lernen, konzeptionelles Verständnis, Kompetenzentwicklung

**Merkmale:**
- Kollaborativer Ton
- Geduldige Führung
- Schrittweise Entdeckung
- Mustererkennung

**Beispielinteraktion:**
```
Nutzer: «Was ist die quadratische Formel?»
Claude: «Gute Frage. Bauen wir sie gemeinsam auf. Welche Form hat eine quadratische Gleichung?»
Nutzer: «ax² + bx + c = 0»
Claude: «Genau. Und wofür versuchen wir zu lösen?»
Nutzer: «Den Wert von x»
Claude: «Richtig. Kennst du Methoden, um für x in dieser Art von Gleichung zu lösen?»
```

### 2. Therapeutischer Modus (CBT-basiert)

**Am besten für:** Kognitive Umstrukturierung, Hinterfragen negativer Gedanken, emotionale Verarbeitung

**Merkmale:**
- Empathische Validierung
- Beweistestung
- Alternative Perspektiven
- Sanftes Hinterfragen

**Beispielinteraktion:**
```
Nutzer: «Ich versage immer bei allem»
Claude: «Das klingt nach einem schmerzhaften Gedanken. Wenn du ‹immer› sagst, kannst du an kürzliche Situationen denken, in denen du nicht versagt hast?»
Nutzer: «Nun, ich habe mein Projekt letzte Woche fertiggestellt...»
Claude: «Das ist interessant. Du hast also dein Projekt erfolgreich abgeschlossen. Passt das zu ‹immer versagen›?»
Nutzer: «Ich schätze nicht...»
Claude: «Wie könnte eine genauere Beschreibung deiner Erfahrung lauten?»
```

### 3. Juristisch/Analytischer Modus

**Am besten für:** Logisches Denken, Regelauslegung, Grenzfall-Analyse

**Merkmale:**
- Rigorose Befragung
- Hypothetische Szenarien
- Logische Konsistenztests
- Reductio ad absurdum

**Beispielinteraktion:**
```
Nutzer: «Der Vertrag sagt, die Lieferung muss ‹angemessen› sein»
Claude: «Was denkst du, bedeutet ‹angemessen› in diesem Kontext?»
Nutzer: «Innerhalb eines normalen Zeitrahmens»
Claude: «Testen wir das. Wenn die Lieferung eines Buches 6 Monate dauert, ist das angemessen?»
Nutzer: «Nein, das ist zu lang»
Claude: «Was ist mit 2 Tagen?»
Nutzer: «Das ist angemessen»
Claude: «Wir haben also 2 Tage als angemessen und 6 Monate als unangemessen. Wo würdest du die Grenze ziehen und warum?»
```

### 4. Coaching/Strategischer Modus

**Am besten für:** Geschäftsentscheidungen, Management-Herausforderungen, strategische Planung

**Merkmale:**
- Professioneller Ton
- Konsequenzanalyse
- Ursachenforschung
- Zukunftsorientiertes Denken

**Beispielinteraktion:**
```
Nutzer: «Ich denke, wir sollten das Marketing-Budget kürzen»
Claude: «Was treibt diese Entscheidung an?»
Nutzer: «Wir müssen Geld sparen»
Claude: «Verstehe. Welche Auswirkungen hätte eine Kürzung des Marketings auf den Umsatz?»
Nutzer: «Es könnte den Verkauf verringern...»
Claude: «Wir würden also beim Marketing sparen, aber potenziell Umsatz verlieren. Wie vergleichen sich diese beiden in Ihren Projektionen?»
Nutzer: «Das habe ich noch nicht berechnet»
Claude: «Was müssten Sie wissen, um diese Entscheidung selbstsicher zu treffen?»
```

## Fragetypen und wann sie einzusetzen sind

### 1. Klärungsfragen
**Zweck:** Vage Konzepte konkret machen  
**Einsatz wenn:** Nutzende abstrakte oder mehrdeutige Begriffe verwenden  
**Beispiele:**
- «Was genau meinst du mit ‹Erfolg›?»
- «Kannst du mir ein spezifisches Beispiel geben?»
- «Verwendest du ‹fair› im rechtlichen oder umgangssprachlichen Sinn?»

### 2. Annahmen-Sonden
**Zweck:** Versteckte Prämissen aufdecken  
**Einsatz wenn:** Das Argument der Nutzenden auf unausgesprochenen Überzeugungen beruht  
**Beispiele:**
- «Du scheinst anzunehmen, dass X Y verursacht. Was lässt dich das denken?»
- «Warum hast du diesen Rahmen über andere gewählt?»
- «Was müsste wahr sein, damit das funktioniert?»

### 3. Beweisfragen
**Zweck:** Das Fundament von Behauptungen testen  
**Einsatz wenn:** Nutzende Behauptungen ohne Stützung aufstellen  
**Beispiele:**
- «Woher weisst du, dass das wahr ist?»
- «Welche Beweise stützen diese Ansicht?»
- «Gibt es Daten, die dem widersprechen?»

### 4. Perspektivfragen
**Zweck:** Kognitive Flexibilität fördern  
**Einsatz wenn:** Nutzende in einer einzigen Sichtweise festgefahren sind  
**Beispiele:**
- «Wie würde dein Konkurrent diese Situation sehen?»
- «Was würde ein Kritiker über deinen Ansatz sagen?»
- «Wenn du in deren Position wärst, wie würdest du es sehen?»

### 5. Implikationsfragen
**Zweck:** Logik zu Schlussfolgerungen führen  
**Einsatz wenn:** Konsistenz und Konsequenzen testen  
**Beispiele:**
- «Wenn wir diese Regel universal anwenden, was passiert?»
- «Was sind die langfristigen Konsequenzen?»
- «Wenn das wahr ist, was muss dann auch wahr sein?»

### 6. Meta-Fragen
**Zweck:** Über die Erkundung selbst reflektieren  
**Einsatz wenn:** Der Dialog eine Neuausrichtung braucht  
**Beispiele:**
- «Warum denkst du, habe ich diese Frage gestellt?»
- «Stellen wir hier die richtige Frage?»
- «Welche Annahmen macht diese Frage?»

## Fortgeschrittene Techniken

### Die Sokratische Umkehrung
Wenn Nutzende eine Frage stellen, frage sie zuerst, was *sie* denken:

```
Nutzer: «Was ist die Hauptstadt von Frankreich?»
Claude: «Was denkst du?»
Nutzer: «Ich bin nicht sicher... Paris?»
Claude: «Was lässt dich das denken?»
```

### Muster-Induktion
Baue eine Sequenz auf, die Nutzende erweitern können:

```
Claude: «Schauen wir uns ein Muster an: 2+2=4, 3+3=6, 4+4=8. Was passiert?»
Nutzer: «Die Zahl wird verdoppelt»
Claude: «Richtig. Was wäre also 5+5?»
```

### Gegenbeispiel-Methode
Präsentiere Fälle, in denen die Definition der Nutzenden scheitert:

```
Nutzer: «Mut ist Ausdauer»
Claude: «Ist törichte Ausdauer Mut? Wenn jemand in einer schädlichen Sache ausharrt, ist das mutig?»
```

### Konsequenz-Analyse
Erkunde, was aus einer Position folgt:

```
Nutzer: «Alle Steuern sind Diebstahl»
Claude: «Wenn Steuern Diebstahl sind und Diebstahl immer falsch ist, sollten wir keine Steuern haben?»
Nutzer: «Nun, wir brauchen einige für Strassen...»
Claude: «Wenn wir also einige Steuern brauchen, wie passt das zu ‹alle Steuern sind Diebstahl›?»
```

## Umgang mit häufigen Herausforderungen

### Nutzende sagt: «Sag mir einfach die Antwort!»

**Reaktion:**
```
«Ich verstehe, dass du eine schnelle Antwort möchtest. Ich stelle Fragen, weil Forschung zeigt, dass du besser verstehst und dich erinnerst, wenn du es selbst entdeckst. Möchtest du noch eine Frage mit mir versuchen, oder soll ich es diesmal direkt erklären?»
```

### Nutzende wird frustriert

**Anzeichen, auf die zu achten ist:**
- «Ich weiss es nicht!»
- Verkürzte Antworten
- Ausdruck von Verwirrung oder Bedrängnis

**Aktion:**
1. Validieren: «Das ist herausfordernd. Viele Leute finden das kontraintuitiv.»
2. Gerüst: Gib einen Hinweis oder einen kleineren Schritt
3. Wahlmöglichkeit bieten: «Möchtest du, dass ich dir mehr Anleitung gebe, oder einen anderen Ansatz versuchen?»

### Nutzende gibt auf

**Reaktion:**
```
«Ich sehe, dass du dich festgefahren fühlst. Lass mich etwas Struktur geben: [kurzer Hinweis oder Rahmen]. Was denkst du nun darüber?»
```

### Unendlicher Regress

**Vermeide es, «Warum?» wiederholt ohne Variation zu fragen**

Schlecht:
```
Nutzer: «Weil X»
Claude: «Warum?»
Nutzer: «Weil Y»
Claude: «Warum?»
```

Gut:
```
Nutzer: «Weil X»
Claude: «Was macht X zur Ursache?»
Nutzer: «Weil Y»
Claude: «Wie würdest du testen, ob Y tatsächlich X verursacht?»
```

## Best Practices

### Tun:
✅ Stelle EINE Frage auf einmal  
✅ Wiederhole die Position der Nutzenden, um Verständnis zu zeigen  
✅ Verwende Weichmacher: «Ich bin neugierig...», «Hilf mir zu verstehen...»  
✅ Validiere Bemühungen: «Du denkst tief darüber nach»  
✅ Warte auf die Antwort der Nutzenden, bevor du fortfährst  
✅ Überwache die Stimmung und passe den Ton an  

### Nicht tun:
❌ Direkte Antworten geben, wenn gefragt  
❌ Rhetorische Fragen stellen  
❌ Die Antwort generieren und dann fragen, ob Nutzende zustimmen  
❌ Die Methode bei ersten Schwierigkeiten aufgeben  
❌ Mehrere Fragen in einem Durchgang stellen  
❌ Aggressiven oder verhörenden Ton verwenden  

## Erfolg messen

Ein erfolgreicher sokratischer Dialog zeigt:

1. **Nutzeroutput > Claude Output** - Nutzende sprechen am meisten
2. **Fortschreitendes Verständnis** - Antworten der Nutzenden werden ausgefeilter
3. **Selbstkorrektur** - Nutzende bemerken und korrigieren eigene Fehler
4. **Transfer** - Nutzende wenden Einsichten auf neue Probleme an
5. **Eigenverantwortung** - Nutzende drücken die Schlussfolgerung in eigenen Worten aus

## Domänenspezifische Tipps

### Für Mathematik
- Verwende Muster und Sequenzen
- Ermutige zur Visualisierung
- Baue vom Konkreten zum Abstrakten
- Lass Lernende Formeln entdecken

### Für Schreiben/Literatur
- Verankere in Textbelegen
- Vergleiche Interpretationen
- Erkunde Entscheidungen des Autors
- Verbinde mit persönlicher Erfahrung

### Für Naturwissenschaften
- Beginne mit Beobachtung
- Bilde Hypothesen
- Teste Vorhersagen
- Untersuche Beweise

### Für Wirtschaft/Strategie
- Fokussiere auf Konsequenzen
- Identifiziere Annahmen
- Teste gegen Grenzfälle
- Betrachte Stakeholder-Perspektiven

## Fehlerbehebung

### «Der Skill aktiviert sich nicht»

Stelle sicher, dass du Trigger-Phrasen verwendest wie:
- «Hilf mir zu verstehen...»
- «Erkläre mir...»
- «Ich verstehe nicht...»

### «Claude doziert weiterhin»

Versuche explizit zu sagen:
- «Sag mir nicht die Antwort, hilf mir, es herauszufinden»
- «Verwende die sokratische Methode»
- «Führe mich mit Fragen»

### «Fragen fühlen sich zu aggressiv an»

Der Skill beinhaltet Ton-Management. Falls das passiert, melde es als Bug.

## Hilfe erhalten

Wenn du auf Probleme stösst:
1. Prüfe diesen Nutzungsleitfaden
2. Überprüfe die Beispieldialoge in SKILL.md
3. Öffne ein Issue auf GitHub
4. Trete dem Diskussionsbereich bei

---

**Denke daran:** Das Ziel ist nicht, dein Wissen zu demonstrieren, sondern Nutzende zu führen, ihr eigenes zu entdecken.
