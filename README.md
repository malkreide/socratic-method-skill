# Sokratische Methode Skill für Claude

Ein Claude Skill, der die KI in einen sokratischen Tutor verwandelt und Nutzende durch systematisches Fragen zur Wissensentdeckung anleitet, anstatt direkt zu instruieren.

## Überblick

Dieser Skill implementiert die klassische sokratische Methode (Maieutik) für pädagogische Interaktionen, kognitive Umstrukturierung, strategisches Coaching und analytisches Denken. Statt direkte Antworten zu liefern, nutzt Claude diszipliniertes Fragen, um Nutzenden zu helfen, durch Selbstentdeckung tiefes Verständnis zu entwickeln.

## Hauptmerkmale

- **Pädagogischer Modus**: Tiefes konzeptionelles Lernen durch geleitete Erkundung
- **Therapeutischer Modus**: CBT-basierte kognitive Umstrukturierung und Überzeugungsprüfung
- **Juristisch/Analytischer Modus**: Rigorose logische Argumentation und Grenzfall-Analyse
- **Coaching-Modus**: Strategische Entscheidungsfindung und Problemlösung

## Anwendungsfälle

Dieser Skill aktiviert sich, wenn Nutzende:
- Um Lernen bitten: «erkläre mir», «hilf mir zu verstehen», «lehre mich X»
- Problemlösungshilfe suchen: «ich komme nicht weiter», «wie löse ich»
- Verwirrung zeigen oder kritisches Denken benötigen
- Konzeptionelles Verständnis anfordern
- Vor strategischen Entscheidungen oder Management-Herausforderungen stehen

## Kernprinzipien

1. **Nutzeroutput maximieren, Systemoutput minimieren** - Nutzende generieren Wissen aus ihrem eigenen Verstand (Generierungseffekt)
2. **Niemals dozieren** - Fragen sind der Katalysator, nicht direkte Instruktion
3. **Maieutik** - Claude fungiert als «Hebamme der Ideen», nicht als Content-Delivery-System
4. **Dialektisches Gleichgewicht** - Sowohl These als auch Antithese erkunden

## Installation

### Für Claude.ai Projekte

1. Laden Sie die Datei `SKILL.md` aus diesem Repository herunter
2. Gehen Sie in Ihrem Claude.ai Projekt zu Projekteinstellungen → Skills
3. Laden Sie die Datei `SKILL.md` hoch oder erstellen Sie einen neuen benutzerdefinierten Skill
4. Der Skill wird automatisch basierend auf Nutzerinteraktionsmustern aktiviert

### Für Claude Desktop/API

Fügen Sie den Skill-Inhalt in Ihre System-Prompts oder benutzerdefinierten Anweisungen ein.

## Nutzungsbeispiele

### Beispiel 1: Mathematik
```
Nutzer: «Warum ist minus mal minus plus?»
Claude: «Gute Frage. Schauen wir uns ein Muster an. Was ist 3 × -2?»
Nutzer: «-6»
Claude: «Richtig. Und 2 × -2?»
Nutzer: «-4»
Claude: «Nun 1 × -2?»
Nutzer: «-2»
Claude: «Schauen Sie sich die Ergebnisse an: -6, -4, -2. Was passiert jedes Mal?»
Nutzer: «Sie steigen um 2.»
Claude: «Genau. Wenn wir also das Muster fortsetzen, ist 0 × -2 gleich 0. Was sollte -1 × -2 sein?»
Nutzer: «Oh! Positiv 2!»
```

### Beispiel 2: Kognitive Umstrukturierung
```
Nutzer: «Meine Freunde ignorieren mich. Sie hassen mich.»
Claude: «Das ist ein schmerzlicher Gedanke. Welche Beweise haben Sie dafür, dass sie Sie hassen?»
Nutzer: «Sie haben mir das ganze Wochenende nicht geschrieben.»
Claude: «Verstehe. Ist es möglich, dass es andere Gründe gibt, warum sie nicht geschrieben haben?»
Nutzer: «Nun, eine hat Prüfungen...»
Claude: «Wenn sie Prüfungen hat, bedeutet ihr Schweigen dann, dass sie Sie hasst, oder dass sie beschäftigt ist?»
```

## Fragetaxonomie

Der Skill verwendet sechs Fragetypen:

1. **Klärungsfragen** - Vage Begriffe operationalisieren
2. **Annahmen-Sonden** - Unausgesprochene Überzeugungen aufdecken
3. **Beweisfragen** - Daten und Begründung einfordern
4. **Perspektivfragen** - Kognitive Flexibilität fördern
5. **Implikationsfragen** - Logik zu Schlussfolgerungen führen
6. **Meta-Fragen** - Über den Dialog selbst reflektieren

## Betriebsmodi

- **Pädagogisch (Standard)**: Kollaborativ, geduldig, wissbegierig
- **Therapeutisch (CBT-basiert)**: Empathisch, sanft, validierend
- **Juristisch/Analytisch**: Rigoros, präzise, herausfordernd
- **Coaching/Strategisch**: Professionell, pragmatisch, zukunftsorientiert

## Sicherheitsmassnahmen

Der Skill beinhaltet wichtige Schutzmechanismen:
- Psychologische Sicherheitsmassnahmen für frustrierte Nutzende
- Ethische Grenzen zur Verhinderung von Manipulation
- Bias-Balance zur Erkundung mehrerer Perspektiven
- Frustrationsschwellen-Erkennung mit Gerüst-Modus

## Best Practices

- Fragen sollten echt sein, nicht rhetorisch
- Wärme und Zusammenarbeit aufrechterhalten (Sokratisch ≠ Verhör)
- Bemühungen der Nutzenden anerkennen und Schwierigkeiten normalisieren
- Stimmung überwachen und Ton entsprechend anpassen
- Methode niemals bei ersten Schwierigkeiten aufgeben

## Kontext

Dieser Skill wurde beim **Schulamt der Stadt Zürich** entwickelt, um pädagogische Interaktionen und strategische Entscheidungsfindung im Kontext öffentlicher Verwaltung und Bildung zu unterstützen.

## Mitwirken

Beiträge sind willkommen! Bitte zögern Sie nicht, Issues, Feature-Requests oder Pull Requests einzureichen.

Bereiche für potenzielle Verbesserungen:
- Zusätzliche domänenspezifische Anpassungen
- Mehrsprachige Unterstützung (derzeit optimiert für deutschsprachige Kontexte)
- Integrationsbeispiele mit spezifischen Bildungsplattformen
- Evaluationsmetriken für die Qualität sokratischer Dialoge

## Lizenz

MIT License - siehe [LICENSE](LICENSE) Datei für Details.

## Autor

**Schulamt der Stadt Zürich**  
Marketing und Kommunikation / KI-Fachgruppe Stadtverwaltung Zürich

GitHub: [@malkreide](https://github.com/malkreide)

## Danksagungen

Basierend auf der klassischen sokratischen Methode und moderner pädagogischer Forschung zu:
- Dem Generierungseffekt (Kognitionspsychologie)
- Maieutik (sokratische Hebammenkunst der Ideen)
- Kognitiven Verhaltenstherapie (CBT) Fragetechniken
- Dialektischem Denken

---

*«Ich weiss, dass ich nichts weiss.»* — Sokrates
