# Arbeitsregeln für Claude in diesem Repository

Dieses Repository enthält ausschließlich **generische QM-Vorlagen** für die Futtermittelbranche (Heimtierfutter). Es ist ein Pilot zur Dokumentenlenkung mit Versionierung und Vier-Augen-Freigabe.

## Harte Regeln

1. **Keine realen Firmendaten.** Keine Chargennummern, Lieferantennamen, Reklamationsfälle, Auditberichte, Preise, Personennamen oder interne Kennzahlen. Platzhalter in eckigen Klammern verwenden, z. B. `[Lieferant]`, `[Chargennummer]`.
2. **Keine Zugangsdaten.** Keine Passwörter, API-Keys oder Tokens im Repository.
3. **Keine erfundenen Rechtsinhalte.** Rechtsverweise nur mit Vorschrift und Artikel. Wortlaut und Fristen immer gegen die Primärquelle (EUR-Lex, nationale Rechtsquellen) prüfen lassen. Unsichere Stellen mit `[PRÜFEN]` markieren.
4. **Änderungen nur per Pull Request.** Kein direkter Push auf `main`. Freigabe durch die fachlich verantwortliche Person (Vier-Augen-Prinzip).
5. **Entwürfe sind Entwürfe.** Die fachliche Verantwortung für Inhalt und Freigabe liegt bei der Qualitätsmanagerin bzw. dem Qualitätsmanager.

## Struktur

- `sops/` – Standardarbeitsanweisungen
- `vorlagen/` – Formblätter, Protokolle, Checklisten
- `regulatorik/` – Verzeichnis relevanter Rechtsgrundlagen mit Quellenangabe
- `.github/` – Pull-Request-Vorlage und spätere Workflows

## Namenskonvention

- Dateinamen: Kleinbuchstaben, Bindestriche, keine Umlaute (`rueckruf-sop.md`)
- Jedes Dokument beginnt mit einem Kopfblock: Titel, Dokumentennummer, Version, Status (`Entwurf` / `Freigegeben`), Verantwortlich, Gültig ab
- Dokumentennummern: `SOP-001`, `FB-001` (Formblatt), `REG-001` usw., fortlaufend
- Versionierung: `v0.x` für Entwürfe, `v1.0` ab erster Freigabe; jede Änderung mit Eintrag in der Änderungshistorie

## Stil

- Sprache: Deutsch, sachlich, präzise
- Verantwortlichkeiten über Rollen benennen, nicht über Personen
- Quellen am Ende des Dokuments auflisten
