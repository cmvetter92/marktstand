# Marktstand

Tages-App für Marktstände (Weihnachtsmarkt, Streetfood-Märkte), aktuell OG und MM: Packliste aus dem Abendbestand, Aufbau, Schließen, Bestand, Feierabend, Hauptlager mit Nachschub und Wareneingang, Schichtplan.

- Reine Web-App (eine `index.html`), läuft auf GitHub Pages, aufs Handy legbar.
- Daten: Firebase Cloud Firestore, anonyme Anmeldung im Hintergrund, kein Login für das Team.
- Zugang über den Team-Link `…/?t=<Team-Code>`; das Gerät merkt sich den Code.
- Sicherheitsregeln: `firestore.rules`.
