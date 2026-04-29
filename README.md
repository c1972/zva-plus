# Zertifizierte Verhaltensanalyse (ZVA+)

<img width="400" height="260" alt="logo-400x260" src="https://github.com/user-attachments/assets/1c38abc0-886f-4571-9dec-b9a1c9f26f04" />

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

### Übersicht der häufig gestellten Fragen (FAQ)

*   [Welche Zertifizierung ist gemeint?](#welche-zertifizierung-ist-gemeint)
*   [Wie viel Zeit muss ich einplanen?](#wie-viel-zeit-muss-ich-einplanen)
*   [Wo kann ich das ausprobieren?](#wo-kann-ich-das-ausprobieren)
*   [Wie wird Prompt-Injection oder "Gaming the System" verhindert?](#wie-wird-prompt-injection-oder-gaming-the-system-verhindert)
*   [Ist das nicht nur ein glorifizierter Chatbot?](#ist-das-nicht-nur-ein-glorifizierter-chatbot)
*   [Warum ein 11k-Zeichen Prompt und kein Fine-Tuning?](#warum-ein-11k-zeichen-prompt-und-kein-fine-tuning)
*   [Warum wird eine dedizierte Hardware-Lösung angestrebt?](#warum-wird-eine-dedizierte-hardware-lösung-angestrebt)
*   [Wie geht das System mit "False Positives" um?](#wie-geht-das-system-mit-false-positives-um)
*   [Ersetzt ZVA+ den menschlichen Recruiter?](#ersetzt-zva-den-menschlichen-recruiter)
*   [Was passiert bei einem Verbindungsabbruch während der Datenerhebung?](#was-passiert-bei-einem-verbindungsabbruch-während-der-datenerhebung)
*   [Wie wird die Objektivität der KI sichergestellt (Bias)?](#wie-wird-die-objektivität-der-ki-sichergestellt-bias)

#### Welche Zertifizierung ist gemeint?

> Aktuell ist ZVA+ ein technisches Framework zur Messung kognitiver Konsistenz. Mein Ziel ist jedoch eine wissenschaftliche Validierung in Zusammenarbeit mit Universitäten und psychologischen Fakultäten. Angestrebt wird eine Zertifizierung nach DIN SPEC oder Standards für KI-gestützte Eignungsdiagnostik. Das benötigte Kapital dient primär dazu, diese wissenschaftliche Begleitforschung und die entsprechende Normierung zu finanzieren.

#### Wie viel Zeit muss ich einplanen?

> Die Dauer hängt nicht von einer festen Zeit ab, sondern von der Datenerhebung während des Gesprächs. Um eine präzise Analyse zu ermöglichen, führt das System den Nutzer durch etwa 10 bis 20 Gesprächsrunden. Je ausführlicher und substanzieller deine Antworten ausfallen, desto schneller erreicht die KI die notwendige Datendichte für den finalen Report.

#### Wo kann ich das ausprobieren?

> Du kannst das System sofort testen, indem du den Prompt aus dem Repository kopierst und in ein LLM deiner Wahl einfügst. Empfohlen werden Gemini (Google), ChatGPT (OpenAI) oder Claude (Anthropic). Für die höchste Präzision ist die Abo-Version von Claude oder das kostenlose Gemini ideal. Claude ist aktuell am stärksten bei komplexer Logik, in der kostenlosen Version jedoch stark limitiert. ChatGPT funktioniert ohne Anmeldung, bietet im Gratis-Modell jedoch eine geringere Antwortqualität. Den vollständigen Prompt einfügen, absenden und den Anweisungen der KI folgen, bis der Abschluss-Code generiert wird. Datenschutz: Der gesamte Dialog bleibt privat. Es findet keine zentrale Speicherung statt. Der generierte Abschluss-Code ist anonymisiert und enthält lediglich technische Metadaten wie das verwendete Modell und den Umfang der Analyse.

#### Wie wird Prompt-Injection oder "Gaming the System" verhindert?

> Hier muss strikt zwischen der aktuellen Test-Umgebung und dem finalen Deployment unterschieden werden:
> 
> ##### Sicherheit durch Architektur (Finales System):
> ZVA+ ist darauf ausgelegt, auf dedizierter Hardware in einer kontrollierten Umgebung zu laufen. In diesem Szenario hat der Nutzer keinen direkten Zugriff auf das KI-Modell oder die System-Instruktionen. Eine klassische Prompt-Injection über das Eingabefeld wird durch die interne Logik-Prüfung der 11.600 Zeichen abgefangen, die Eingaben strikt als Daten und nicht als Befehle interpretiert.
> 
> ##### Abwehr von Manipulation (Inhaltsebene):
> Das System ist darauf programmiert, Ausweichmanöver, hohle Floskeln und manipulative Antwortmuster zu erkennen. Wer versucht, das System "auszutricksen", erreicht keine vollständige Datendichte. Das System verweigert in solchen Fällen die vollständige abschließende Analyse und gibt stattdessen einen Hinweis auf mangelnde Konsistenz oder Substanz aus.
> 
> ##### Hinweis zu Tests auf öffentlichen Systemen:
> Die Tests auf Plattformen wie ChatGPT oder Gemini dienen lediglich der Demonstration der Logik. Da der Nutzer hier den System-Prompt selbst einfügt, handelt es sich technisch gesehen um eine "offene" Umgebung. Eine vollständige Sicherheit gegen Manipulation der System-Ebene ist bauartbedingt nur auf autarker, lokaler Hardware möglich, bei der System-Logik und Nutzer-Input physisch und softwareseitig getrennt bleiben.

#### Ist das nicht nur ein glorifizierter Chatbot?

> Ein Chatbot will unterhalten oder helfen. ZVA+ will diagnostizieren. Der Unterschied liegt im Monitoring: Das System führt im Hintergrund eine Schatten-Analyse der Argumentationskette und der Konsistenz, während der User vorne nur den Dialog sieht.

#### Warum ein 11k-Zeichen Prompt und kein Fine-Tuning?

> Ein Fine-Tuning macht das Modell starr. Die massive Instruktionslogik ermöglicht es, das Verhalten der KI in Echtzeit zu steuern und auf logische Brüche zu reagieren, ohne die Generalisierungsfähigkeit des zugrunde liegenden LLMs zu verlieren. Es ist **Dynamic Engineering** statt Static Training.

#### Warum wird eine dedizierte Hardware-Lösung angestrebt?

> ZVA+ ist kein SaaS-Produkt (Software as a Service). Im professionellen Recruiting und in der Diagnostik ist Vertraulichkeit das höchste Gut. Öffentliche Cloud-KIs speichern Daten oft zu Trainingszwecken. Eine autarke Hardware-Lösung stellt sicher, dass sensible Analysedaten das Haus des Kunden niemals verlassen. Zudem erlaubt nur eigene Hardware die volle Kontrolle über die Modell-Parameter (Temperature, Top-P), was für die Reproduzierbarkeit der Analyseergebnisse essenziell ist.

#### Wie geht das System mit "False Positives" um?

> Jede KI-gestützte Analyse unterliegt einer gewissen Fehlertoleranz. ZVA+ minimiert diese durch das interne Konsistenz-Monitoring. Widerspricht sich das Modell in seiner Bewertung oder erkennt es logische Lücken in der eigenen Argumentationskette, wird kein Zertifikat ausgestellt, sondern ein Re-Evaluations-Modus aktiviert. Das System ist darauf getrimmt, im Zweifel eher eine Analyse zu verwerfen, als eine ungenaue Zertifizierung zu erteilen.

#### Ersetzt ZVA+ den menschlichen Recruiter?

> Nein. ZVA+ ist ein Vorfilter-Instrument, das die Spreu vom Weizen trennt. Es entlastet Recruiter von der ersten, oft fehleranfälligen Phase der Vorauswahl. Das System liefert eine fundierte, datenbasierte Entscheidungsgrundlage für das persönliche Gespräch. Es ersetzt nicht das menschliche Urteilsvermögen, sondern objektiviert die kognitive Vorqualifikation.

#### Was passiert bei einem Verbindungsabbruch während der Datenerhebung?

> Da ZVA+ auf einer Gesprächslogik basiert, ist der Fortschritt statusabhängig. In der finalen Implementierung wird ein Session-Management implementiert, das den Fortschritt lokal zwischenspeichert. Bei den aktuellen Tests auf öffentlichen Systemen (ChatGPT/Gemini) führt ein Abbruch der Session meist zum Datenverlust, weshalb eine stabile Umgebung für den Test empfohlen wird.

#### Wie wird die Objektivität der KI sichergestellt (Bias)?

> KI-Modelle können Vorurteile aus ihren Trainingsdaten übernehmen. ZVA+ wirkt dem entgegen, indem es sich rein auf logische Konsistenz und argumentative Tiefe konzentriert, statt auf sozio-kulturelle Merkmale. Durch die 11.600 Zeichen Instruktionslogik wird die KI gezwungen, rein analytisch zu agieren und rhetorische Blendgranaten oder biografische "Halo-Effekte" (positive Vorurteile) zu ignorieren.

[↑ Zur Übersicht](#übersicht-der-häufig-gestellten-fragen-faq)
