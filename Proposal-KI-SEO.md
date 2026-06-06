## KI-unterstützte Suchmaschinenoptimierung (SEO) – "SmartSEO"

**Bachelor-Projekt im Studiengang Wirtschaftsinformatik**
Hochschule Fulda · Sommersemester 2026

| Feld | Angabe |
|---|---|
| Projekttitel | KI-unterstützte Suchmaschinenoptimierung (SmartSEO) |
| Auftraggeber | ACO Passavant GmbH |
| Branche | Entwässerungstechnik |
| Methodik | PRINCE2 |
| Werkzeuge | n8n, OpenProject, KI-API (LLM) |
| Bearbeitungszeitraum | Sommersemester 2026 |

---

## 1. Ausgangslage und Problemstellung

Suchmaschinen wie Google sind heute der wichtigste Weg, über den neue Kunden ein Unternehmen finden. Wer bei einer Suche nicht weit oben steht, wird oft gar nicht gesehen. Studien zeigen seit Jahren: Die meisten Klicks gehen an die ersten drei bis fünf Treffer. Alles darunter bekommt nur wenig Aufmerksamkeit.

Für die ACO Passavant GmbH ist das ein klares Problem. Das Unternehmen ist in der Entwässerungstechnik tätig. Bei wichtigen Suchbegriffen wie "Entwässerungstechnik" stehen aktuell andere Anbieter und Fach-Portale weiter oben. Beispiele für solche Wettbewerber im Suchergebnis sind Baustoffwissen, Liga Deutschland, Bounetz und Mali. ACO hat also gute Produkte, aber zu wenig Sichtbarkeit in der Online-Suche.

Klassische Suchmaschinenoptimierung (SEO) ist die Antwort darauf. Sie verbessert Inhalte, Technik und Struktur einer Webseite, damit sie besser gefunden wird. Das Problem: Gute SEO ist aufwendig. Man muss viele Keywords prüfen, Texte schreiben, die Technik kontrollieren und ständig nachbessern. Für ein kleines Team ist das viel Handarbeit.

Genau hier setzt dieses Projekt an. Es prüft, wie Künstliche Intelligenz (KI) diese Handarbeit unterstützen kann. Die Idee: Eine KI hilft dabei, Keywords zu finden, Texte vorzuschlagen und Inhalte zu bewerten. So soll die SEO-Arbeit schneller und mit weniger Aufwand möglich werden.

---

## 2. Zielsetzung

Das Ziel des Projekts ist ein funktionierender, teilweise automatisierter Arbeitsablauf (Workflow), der die SEO-Arbeit für ACO Passavant mit Hilfe von KI unterstützt.

Dabei geht es nicht um eine fertige, perfekte Software. Es geht um einen erprobten Prototyp ("Proof of Concept"), der im realen Umfeld getestet wird. Das Projekt soll zeigen, ob und wie KI in der Praxis bei SEO einen echten Mehrwert bringt.

Die Hauptziele im Überblick:

- Einen automatisierten Workflow aufbauen, der KI-Vorschläge für SEO erzeugt (Keywords, Texte, Optimierungs-Hinweise).
- Die Sichtbarkeit von ACO Passavant bei wichtigen Suchbegriffen messbar verbessern, vor allem beim Hauptkeyword "Entwässerungstechnik" und bei 15 bis 25 Long-Tail-Keywords.
- Den Nutzen von KI für SEO sachlich bewerten: Wo hilft sie, wo nicht?
- Eine wiederverwendbare Lösung schaffen, die ACO auch nach Projektende weiter nutzen kann.

Wichtig: Wir messen einen Zusammenhang zwischen den Maßnahmen und der Sichtbarkeit. Ein sicherer Ursache-Wirkungs-Beweis ist im Rahmen eines Semesters kaum möglich, weil viele äußere Faktoren (z. B. Google-Updates, Wettbewerber) mitspielen. Das ist also Zusammenhang, nicht Ursache.

---

## 3. Forschungs- und Leitfragen

Das Projekt will folgende Fragen beantworten:

1. Wie kann ein KI-gestützter Workflow den SEO-Prozess für ein mittelständisches Industrieunternehmen sinnvoll unterstützen?
2. Bei welchen SEO-Aufgaben (Keyword-Recherche, Texterstellung, technische Prüfung) bringt KI den größten Nutzen?
3. Wie verlässlich und konsistent sind die KI-Vorschläge? Wie viel menschliche Prüfung ist nötig?
4. Lässt sich nach den Maßnahmen eine Verbesserung der Sichtbarkeit messen (z. B. Rankings, Klicks, Impressionen)?

---

## 4. Theoretischer Hintergrund und Stand der Technik

Das Projekt baut auf drei Themenfeldern auf.

**Suchmaschinenoptimierung (SEO).** SEO umfasst alle Maßnahmen, die eine Webseite in den unbezahlten ("organischen") Suchergebnissen nach oben bringen. Man unterscheidet meist drei Bereiche: On-Page (Inhalte, Keywords, Struktur), Technical SEO (Ladezeit, Aufbau, Indexierung) und Off-Page (Verlinkungen von anderen Seiten). Grundlage ist immer die Keyword-Recherche: Welche Begriffe geben Nutzer in die Suche ein?

**Künstliche Intelligenz und große Sprachmodelle.** Moderne Sprachmodelle (Large Language Models, LLM) können Texte verstehen und erzeugen. Für SEO sind sie interessant, weil sie Keyword-Ideen liefern, Textentwürfe schreiben und Inhalte bewerten können. Die Schwäche: Sie können Fehler machen oder unpassende Vorschläge liefern. Deshalb braucht es immer eine menschliche Kontrolle.

**Automatisierung von Arbeitsabläufen.** Mit Werkzeugen wie n8n lassen sich einzelne Schritte zu einem festen Ablauf verbinden. Daten werden geholt, an die KI geschickt und die Ergebnisse weitergeleitet. So entsteht aus vielen Einzelschritten ein wiederholbarer Prozess.

Neu an diesem Projekt ist die Verbindung dieser drei Felder zu einem praktischen, getesteten Workflow für einen echten Auftraggeber.

---

## 5. Methodisches Vorgehen

Das Projekt arbeitet nach der Methode **PRINCE2**. PRINCE2 ist eine bekannte Methode für Projektmanagement. Sie teilt ein Projekt in klare Phasen und legt feste Rollen, Aufgaben und Kontrollpunkte fest. Das passt gut zu einem Team-Projekt mit Auftraggeber, weil jeder seine Verantwortung kennt und der Fortschritt regelmäßig geprüft wird.

Die Steuerung des Projekts läuft über **OpenProject**. Dort werden Aufgaben, Termine und der Status verwaltet. Ein Lenkungsausschuss (mit Vertretern von ACO und Hochschule) prüft den Fortschritt in festen Sitzungen (PSG-Sitzungen / Projektstatus-Berichte).

Der praktische Teil läuft in mehreren Schritten ab:

1. **Analyse:** Ist-Zustand der ACO-Sichtbarkeit prüfen, Keywords und Wettbewerber erfassen.
2. **Konzeption:** Aufbau des Workflows planen, KI-Einsatz festlegen, Kennzahlen (KPIs) definieren.
3. **Realisierung:** Workflow in n8n bauen und mit der KI-API verbinden.
4. **Test:** Workflow mit echten Inhalten testen und die Ergebnisse prüfen.
5. **Auswertung:** Wirkung messen und bewerten, Empfehlungen ableiten.

---

## 6. Technische Umsetzung

Die Lösung besteht aus drei technischen Bausteinen, die zusammenarbeiten.

**n8n** ist das Herzstück. n8n ist ein Werkzeug für Workflow-Automatisierung. Es verbindet die einzelnen Schritte: Es holt Daten (z. B. zu Keywords), schickt sie an die KI, nimmt die Antwort entgegen und leitet sie weiter. Das Hosting läuft in der EU (Hetzner), damit der Datenschutz gewahrt bleibt.

Die **KI-API** liefert die eigentlichen Vorschläge. Ein Sprachmodell erzeugt Keyword-Ideen, Textentwürfe und Bewertungen. Die KI-Vorschläge werden nicht blind übernommen, sondern immer von Menschen geprüft.

**OpenProject** dient der Projektsteuerung. Hier laufen Aufgaben, Termine und der Status zusammen.

Wo eine offizielle Schnittstelle (API) fehlt, wird eine einfache Lösung wie ein Webhook genutzt. Das Projekt soll bewusst einfach bleiben (kein Over-Engineering), weil es ein Studierenden-Projekt mit begrenzter Zeit ist.

---

## 7. Arbeitspakete (AP)

Die Arbeit ist in fünf Arbeitspakete aufgeteilt. Jedes Paket hat eine verantwortliche Person und eine Deadline.

| AP | Inhalt | Verantwortlich | Deadline |
|---|---|---|---|
| AP1 | n8n (Workflow-Automatisierung) | Eugen | 15.05.2026 |
| AP2 | OpenProject (Steuerung) | Homan | 15.05.2026 |
| AP3 | Konzeption | Yuting | 15.05.2026 |
| AP4 | Realisierung | Stefan | 15.06.2026 |
| AP5 | Test | Djuy | 30.06.2026 |

---

## 8. Zeitplan und Meilensteine

| Meilenstein | Inhalt | Zeitpunkt |
|---|---|---|
| M1 | Initiierung | Anfang Mai 2026 |
| M2 | Setup | Mitte Mai 2026 |
| M3 | Konzeption | Mitte Mai 2026 |
| M4 | Workflow fertig | Mitte Juni 2026 |
| M5 | Testlauf | Ende Juni 2026 |
| M6 | OpenProject (laufend) | gesamtes Projekt |
| M7 | Abschluss / Präsentation | 17.07.2026 |

---

## 9. Erwartete Ergebnisse und Kennzahlen (KPIs)

Am Ende soll das Projekt liefern:

- einen lauffähigen, KI-gestützten SEO-Workflow in n8n;
- eine Auswertung, wie gut die KI-Vorschläge in der Praxis sind;
- eine messbare Aussage zur Sichtbarkeit von ACO bei den Ziel-Keywords;
- eine Empfehlung, wie ACO die Lösung weiter nutzen kann.

Zur Messung dienen Kennzahlen, zum Beispiel:

- **Ranking-Position** für das Hauptkeyword und die Long-Tail-Keywords.
- **Impressionen und Klicks** (z. B. aus der Google Search Console).
- **Anzahl der von der KI erzeugten und übernommenen Vorschläge.**
- **Aufwand** (Zeit) im Vergleich zur reinen Handarbeit.

Auch hier gilt: Eine bessere Sichtbarkeit zeigt einen Zusammenhang mit den Maßnahmen. Sie ist kein endgültiger Ursache-Beweis, weil äußere Einflüsse mitwirken.

---

## 10. Risiken

Die größten Risiken sind aktuell:

- **Zeitplan zu optimistisch.** Die Phasen sind eng getaktet. Verzögerungen in einem AP können das ganze Projekt verschieben. Gegenmaßnahme: Puffer einplanen, Fortschritt eng über OpenProject verfolgen.
- **Inkonsistente KI-Vorschläge.** Die KI liefert nicht immer gleich gute Ergebnisse. Gegenmaßnahme: feste Prüf-Schritte durch Menschen, klare Vorgaben (Prompts) und Stichproben.

Weitere mögliche Risiken sind Google-Updates während der Laufzeit, Datenschutz-Fragen und technische Probleme bei den Schnittstellen.

---

## 11. Abgrenzung (was das Projekt nicht leistet)

Damit der Rahmen klar bleibt, grenzt sich das Projekt bewusst ab:

- Es entsteht **keine fertige Marktsoftware**, sondern ein erprobter Prototyp.
- Es wird **keine bezahlte Werbung (SEA)** behandelt, sondern nur die organische Suche.
- Es wird **kein vollständiger Umbau** der ACO-Webseite vorgenommen.
- Die KI **ersetzt nicht den Menschen**, sondern unterstützt ihn.

---

## 12. Nutzen des Projekts

Für ACO Passavant entsteht ein konkreter Mehrwert: bessere Sichtbarkeit und ein Werkzeug, das die SEO-Arbeit erleichtert. Für das Team und den Studiengang Wirtschaftsinformatik verbindet das Projekt drei aktuelle Themen – SEO, KI und Automatisierung – in einem realen Auftrag. So wird gezeigt, wie betriebswirtschaftlicher Nutzen und Informationstechnik praktisch zusammenkommen.

