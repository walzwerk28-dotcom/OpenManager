Phase 1 – Kernablauf der Karriere fertigstellen
1. Dashboard und Matchcenter

Priorität: sehr hoch

Ziel: Der Spieler kann vom Dashboard aus zuverlässig bis zum Spieltag fortfahren und ein Match starten.

Aufgaben:

„Fortfahren“ bis zum nächsten wichtigen Ereignis
Matchcenter im Dashboard anbinden
Buttonzustände:
bis zum Spiel fortfahren
Spieltag starten
Match läuft
kein Spiel geplant
Matchcenter mit:
Gegner
Logos
Formationen
Aufstellungen
Verletzungen
Sperren
Taktikübersicht
Auswahl:
3D ansehen
sofort simulieren
Ergebnisbildschirm
nach dem Spiel nächstes Fixture laden

Fertig, wenn:

Ein kompletter Ablauf funktioniert:

Dashboard
→ Fortfahren
→ Spieltag
→ Matchcenter
→ Match
→ Ergebnis
→ Tabelle aktualisiert
→ zurück zum Dashboard
2. Karriere-Zeit und Ereignisse

Priorität: sehr hoch

Ziel: Jeder Karrieretag verarbeitet alle Systeme korrekt.

Aufgaben:

zentraler CareerTimeAdvanceService
tägliche Verarbeitung von:
Spielplan
Transfers
Scouting
Verletzungen
Sperren
Training
Finanzen
Verträgen
Nachrichten
wichtige Ereignisse stoppen das Fortfahren
Sicherheitslimit gegen Endlosschleifen
Doppelklickschutz
deterministische Verarbeitung

Fertig, wenn:

Manuelles tägliches Fortfahren und automatisches Fortfahren erzeugen bei gleichem Spielstand dieselben Ergebnisse.

Phase 2 – Scouting vollständig einbauen
3. Scouting-Datenmodell

Priorität: hoch

Aufgaben:

Scouts mit:
Fähigkeiten
Potenzialbeurteilung
Regionenkenntnis
Status
aktuellem Auftrag
Scoutingaufträge:
Spieler
Verein
Liga
Region
Auftragsdauer
Kosten
Fortschritt pro Karrieretag
abgeschlossene Berichte speichern
4. Kenntnisstufen

Aufgaben:

unbekannt
Basisdaten
Teilbericht
vollständiger Bericht
Stärke als Schätzbereich
Potenzial nur als Text oder Bereich
Marktwertschätzung
Stärken
Schwächen
Risiken
Scoutempfehlung
5. Scouting-UI

Aufgaben:

fehlerhaftes Mini-Layout reparieren
Scoutliste
laufende Aufträge
Spielersuche
Berichtpanel
Beobachtungsliste
abgeschlossene Berichte
Historie
Verbindung zur Transferzentrale

Fertig, wenn:

Ein Spieler kann beobachtet werden, nach mehreren Karrieretagen erscheint ein Bericht, und die Transferzentrale zeigt anschließend bessere Informationen.

Phase 3 – Transfers spielbar machen
6. Transfermarkt

Priorität: hoch

Aufgaben:

Spielersuche
Filter
Scoutingstatus
Marktwert
Vertrag
Transferstatus
Shortlist
eigene Abgänge
Filterzustände klar anzeigen
exaktes Potenzial fremder Spieler nicht anzeigen
7. Transferverhandlungen

Aufgaben:

Ablöseangebot
Raten
Boni
Weiterverkaufsbeteiligung
Leihe
Kaufoption
Kaufpflicht
Gehaltsbeteiligung
Gegenangebote
Fristen
Annahme und Ablehnung
8. Vertragsverhandlungen

Aufgaben:

Gehalt
Vertragsdauer
Rolle im Team
Handgeld
Bonuszahlungen
Ausstiegsklausel
Spielerinteresse
Beraterforderungen
9. Transferabschluss

Aufgaben:

Budget abbuchen
Spieler dem neuen Verein zuordnen
Kader aktualisieren
Vertrag erstellen
Transferhistorie
Posteingangsmeldung
SaveGame aktualisieren

Fertig, wenn:

Ein fremder Spieler kann gescoutet, gekauft, vertraglich verpflichtet und im eigenen Kader angezeigt werden.

Phase 4 – Training, Fitness und Entwicklung
10. Trainingsansicht

Priorität: mittel bis hoch

Aufgaben:

Wochenplan
Trainingsschwerpunkte
Intensität
Regeneration
individuelle Entwicklung
Positions- und Rollentraining
Standardsituationen
Trainerzuweisung
11. Auswirkungen

Aufgaben:

Fitness
Müdigkeit
Verletzungsrisiko
Moral
Form
Attributentwicklung
Rollenvertrautheit
taktische Eingespieltheit
12. Spielerentwicklung

Aufgaben:

Alterung
Potenzial
Entwicklungsrate
Einsatzzeit
Trainingsqualität
Persönlichkeit
Verletzungen
Form
Positionslernen

Fertig, wenn:

Spieler entwickeln sich über Wochen und Monate nachvollziehbar und unterschiedlich.

Phase 5 – Finanzen und Vorstand
13. Finanzsystem

Priorität: mittel

Aufgaben:

Transferbudget
Gehaltsbudget
Einnahmen
Ausgaben
Spieltagseinnahmen
Prämien
Gehälter
Transferzahlungen
Scoutingkosten
Trainingskosten
Monatsabschluss
14. Vorstand

Aufgaben:

Saisonziele
Finanzziele
Jugendziele
Transfererwartungen
Vertrauen
Managerbewertung
Warnungen
Entlassungsrisiko
15. Sponsoren und Stadion

Später:

Sponsorenverträge
Stadionkapazität
Ticketpreise
Infrastruktur
Trainingsgelände
Jugendakademie
Phase 6 – Liga, Wettbewerbe und Saisonablauf
16. Ligaübersicht

Priorität: mittel

Aufgaben:

vollständige Tabelle
Formtabelle
Heim- und Auswärtstabelle
Spielplan
Ergebnisse
Torjäger
Vorlagen
Karten
Spielerbewertungen
17. Saisonlogik

Aufgaben:

Saisonstart
Spieltage
Winterpause
Transferfenster
Saisonende
Aufstieg
Abstieg
Meister
Qualifikation
neue Saison erzeugen
18. Pokalwettbewerbe

Später:

K.-o.-Runden
Auslosung
Verlängerung
Elfmeterschießen
Pokalprämien
Phase 7 – Jugend und Nachwuchs
19. Jugendbereich

Priorität: mittel bis niedrig

Aufgaben:

Jugendkader
Jugendspieler generieren
Jugendtrainer
Nachwuchsscouting
Entwicklung
Profivertrag anbieten
Ausleihe
Vereinsphilosophie
20. Nachwuchsjahrgang

Aufgaben:

jährliche Jugendaufnahme
regionale Talente
verstecktes Potenzial
Persönlichkeiten
unterschiedliche Entwicklungsverläufe
Phase 8 – Matchsimulation weiter vertiefen
21. Statistische Balance

Priorität: dauerhaft

Aufgaben:

regelmäßig 1.000 bis 10.000 Spiele testen
Tore
Schüsse
Ballbesitz
Passquote
Karten
Abseits
Heimvorteil
starke gegen schwache Teams
taktische Unterschiede
22. Matchereignisse

Aufgaben:

Ballverluste
Zweikämpfe
Standards
Ecken
Freistöße
Elfmeter
Verletzungen
Karten
Wechsel
Nachspielzeit
23. Spielerwechsel

Aufgaben:

Bank
Wechselzeitpunkte
Fitness
Verletzung
taktische Wechsel
automatische KI-Wechsel
Wechsel im Matchcenter
Phase 9 – Match3D weiter verbessern
24. Optik

Priorität: nach den Managementsystemen

Aufgaben:

bessere Trikots
Rückennummern
unterschiedliche Spielergrößen
bessere Stadien
Zuschauer
Werbebanden
Wetter
Tageszeiten
Schatten
Tornetze
25. Animationen

Aufgaben:

bessere Ballannahmen
Kopfbälle
Tacklings
Grätschen
Zweikämpfe
Jubel
Enttäuschung
Verletzungen
Standards
Torwartanimationen
26. Kamera und Präsentation

Aufgaben:

TV-Kamera
taktische Kamera
Seitenlinie
Hintertor
Wiederholungen
Tor-Replay
Highlight-Modus
Match-Kommentar

Wichtig: Match3D weiterhin nur als Darstellung der bestehenden Simulation behandeln.

Phase 10 – KI-Vereine
27. Transfer-KI

Aufgaben:

Kaderbedarf erkennen
Spieler kaufen
verkaufen
verleihen
Verträge verlängern
Budget einhalten
realistische Angebote
28. Taktik-KI

Aufgaben:

Formation nach Kader
Rollen
Gegneranpassung
Führung verteidigen
Rückstand aufholen
Wechsel
29. Kaderplanung

Aufgaben:

Alter
Stärke
Potenzial
Vertrag
Position
Ausländerregeln
Registrierung
Jugendförderung
Phase 11 – Speichern, Stabilität und Werkzeuge
30. SaveGame

Priorität: dauerhaft

Prüfen:

Karriere
Kader
Taktiken
Transfers
Scouting
Verträge
Finanzen
Verletzungen
Spielplan
Tabellen
Nachrichten
laufende Aufträge
31. Editor-Werkzeuge

Aufgaben:

Club-Editor
Spieler-Editor
Liga-Editor
Formationseditor
Rollen-Editor
Logo-Validator
SaveGame-Inspector
Balance-Tests
Datenvalidierung
32. Fehlerbehandlung

Aufgaben:

keine NullReferenceExceptions
fehlende Logos abfangen
fehlende Prefabs abfangen
ungültige Spieler-IDs melden
doppelte Club-IDs erkennen
unvollständige Aufstellungen verhindern
Phase 12 – Audio, Einstellungen und Veröffentlichung
33. Audio
Menümusik
Button-Sounds
Stadionkulisse
Torjubel
Pfiffe
Publikum
Matchereignisse
34. Einstellungen
Lautstärke
Auflösung
Vollbild
UI-Skalierung
Grafikqualität
Matchgeschwindigkeit
Kameramodus
Sprache
35. Abschluss
Tutorial
neue Karriere
Schwierigkeitsgrad
Managererstellung
Clubauswahl
Credits
Build für Windows
Bugtests
Performanceprüfung
