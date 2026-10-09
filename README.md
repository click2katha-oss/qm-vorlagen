# qm-vorlagen

Generische Vorlagen für ein Qualitätsmanagementsystem in der Futtermittelbranche (Heimtierfutter). Das Repository dient als Pilot für Dokumentenlenkung mit Versionierung und Freigabe per Pull Request.

> **Wichtig:** Hier liegen keine realen Unternehmensdaten. Siehe `CLAUDE.md` für die verbindlichen Arbeitsregeln.

## Struktur

| Ordner | Inhalt |
|---|---|
| `sops/` | Standardarbeitsanweisungen (z. B. Rückruf) |
| `vorlagen/` | Formblätter, Protokolle, Checklisten |
| `regulatorik/` | Verzeichnis relevanter Rechtsgrundlagen mit Quellen |
| `.github/` | Pull-Request-Vorlage, spätere Workflows |

## Arbeitsweise

1. Neuen Branch anlegen (`feature/<thema>`).
2. Dokument erstellen oder ändern, Kopfblock und Änderungshistorie pflegen.
3. Pull Request eröffnen, Checkliste in der PR-Vorlage abarbeiten.
4. Freigabe durch die verantwortliche Person, danach Merge in `main`.

Der Stand auf `main` gilt als freigegeben. Frühere Stände sind über die Versionshistorie nachvollziehbar.
