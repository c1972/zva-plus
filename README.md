# Zertifizierte Verhaltensanalyse (ZVA+)
## Die Inversion des Recruitings: Effizienz statt Zufall

### Problem

Weltweit investieren Unternehmen enorme Ressourcen, um geeignete Mitarbeiter zu finden. Doch jede Einstellung bleibt ein Versuch – bis sich in der Praxis zeigt, ob der neue Mitarbeiter wirklich zur Aufgabe und zum Team passt. Selbst modernste Recruiting-Tools prüfen nur Lebensläufe oder Körpersprache – nicht den mentalen Stil, die kognitive Konsistenz oder die Belastbarkeit einer Person. Das Resultat: Fehlbesetzungen, hohe Fluktuation und Produktivitätsverluste. Herkömmliches Recruiting ist ein ineffizientes, teures Trial-and-Error-System.

### Lösung

- Statt dass Unternehmen Bewerber prüfen, lassen sich Bewerber präventiv zertifizieren – durch eine KI-basierte Verhaltensanalyse, die objektiv und unbestechlich misst, wie jemand denkt, reagiert und Probleme löst.
- Die Analyse basiert auf einer etwa 45 - 90 minütigen Interaktion mit einem spezialisierten Large Language Model (LLM). Aus diesem unstrukturierten Dialog leitet das System präzise kognitive Marker ab – etwa Systematik, Stressresistenz, Konfliktverhalten oder Autonomiepräferenz.
- Das Ergebnis ist ein standardisiertes, KI-validiertes Persönlichkeitsprofil, das Unternehmen eine fundierte, faktenbasierte Einstellungsentscheidung ermöglicht.

### Geschäftsmodell

1. Bewerber bezahlen für ihre ZVA+-Zertifizierung, um ihre Marktchancen signifikant zu erhöhen.
2. Unternehmen zahlen Lizenzgebühren für den Zugang zu einem geprüften, hochqualitativen Kandidatenpool.

So entsteht ein umgekehrter Cashflow mit doppeltem Nutzen: Bewerber gewinnen Glaubwürdigkeit, Arbeitgeber sparen Kosten und Fehlentscheidungen.

### FAQ

**Welche Zertifizierung ist gemeint?**

Aktuell ist ZVA+ ein technisches Framework zur Messung kognitiver Konsistenz. Mein Ziel ist jedoch eine wissenschaftliche Validierung in Zusammenarbeit mit Universitäten und psychologischen Fakultäten. Angestrebt wird eine Zertifizierung nach DIN SPEC oder Standards für KI-gestützte Eignungsdiagnostik. Das benötigte Kapital dient primär dazu, diese wissenschaftliche Begleitforschung und die entsprechende Normierung zu finanzieren.

**Wie viel Zeit muss ich einplanen?**

Die Dauer hängt nicht von einer festen Zeit ab, sondern von der Datenerhebung während des Gesprächs. Um eine präzise Analyse zu ermöglichen, führt das System den Nutzer durch etwa 10 bis 20 Gesprächsrunden. Je ausführlicher und substanzieller deine Antworten ausfallen, desto schneller erreicht die KI die notwendige Datendichte für den finalen Report.

**Wo kann ich das ausprobieren?**

Du kannst das System sofort testen, indem du den Prompt aus dem Repository kopierst und in ein LLM deiner Wahl einfügst. Empfohlen werden Gemini (Google), ChatGPT (OpenAI) oder Claude (Anthropic). Für die höchste Präzision ist die Abo-Version von Claude oder das kostenlose Gemini ideal. Claude ist aktuell am stärksten bei komplexer Logik, in der kostenlosen Version jedoch stark limitiert. ChatGPT funktioniert ohne Anmeldung, bietet im Gratis-Modell jedoch eine geringere Antwortqualität. Den vollständigen Prompt einfügen, absenden und den Anweisungen der KI folgen, bis der Abschluss-Code generiert wird. Datenschutz: Der gesamte Dialog bleibt privat. Es findet keine zentrale Speicherung statt. Der generierte Abschluss-Code ist anonymisiert und enthält lediglich technische Metadaten wie das verwendete Modell und den Umfang der Analyse.

**Wie wird Prompt-Injection oder "Gaming the System" verhindert?**

Hier muss strikt zwischen der aktuellen Test-Umgebung und dem finalen Deployment unterschieden werden:

#### Sicherheit durch Architektur (Finales System):
ZVA+ ist darauf ausgelegt, auf dedizierter Hardware in einer kontrollierten Umgebung zu laufen. In diesem Szenario hat der Nutzer keinen direkten Zugriff auf das KI-Modell oder die System-Instruktionen. Eine klassische Prompt-Injection über das Eingabefeld wird durch die interne Logik-Prüfung der 11.600 Zeichen abgefangen, die Eingaben strikt als Daten und nicht als Befehle interpretiert.

#### Abwehr von Manipulation (Inhaltsebene):
Das System ist darauf programmiert, Ausweichmanöver, hohle Floskeln und manipulative Antwortmuster zu erkennen. Wer versucht, das System "auszutricksen", erreicht keine vollständige Datendichte. Das System verweigert in solchen Fällen die vollständige abschließende Analyse und gibt stattdessen einen Hinweis auf mangelnde Konsistenz oder Substanz aus.

#### Hinweis zu Tests auf öffentlichen Systemen:
Die Tests auf Plattformen wie ChatGPT oder Gemini dienen lediglich der Demonstration der Logik. Da der Nutzer hier den System-Prompt selbst einfügt, handelt es sich technisch gesehen um eine "offene" Umgebung. Eine vollständige Sicherheit gegen Manipulation der System-Ebene ist bauartbedingt nur auf autarker, lokaler Hardware möglich, bei der System-Logik und Nutzer-Input physisch und softwareseitig getrennt bleiben.

