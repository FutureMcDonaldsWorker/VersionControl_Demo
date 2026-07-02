# 🎯 Git & Versionskontrolle – Ada-Schulung

Dieses Repository dient als Live-Demo-Projekt für die praktische Ada-Unterweisung zu Git, Branches und Versionskontrolle in Visual Studio Code.

---

## 📌 Lernziele

| Lernziel | Umsetzung |
|----------|-----------|
| **Kognitiv** | Verstehen, was ein Branch ist und warum man ihn nutzt |
| **Psychomotorisch** | Branch in VS Code erstellen, auschecken, committen & pushen |
| **Affektiv** | Bewusstsein für saubere Teamarbeit entwickeln |

---

## 🎯 Was ist ein Branch?

Ein Branch ist eine unabhängige Kopie des Projekts, in der neue Funktionen entwickelt oder Fehler behoben werden können, ohne den Hauptcode (main) zu beeinflussen. Nach der Fertigstellung kann der Branch in main integriert werden.

### Warum Branches nutzen?

- **Sicherheit:** Hauptcode bleibt stabil
- **Parallelarbeit:** Mehrere Personen arbeiten an verschiedenen Features gleichzeitig
- **Übersichtlichkeit:** Änderungen sind logisch organisiert
- **Qualitätskontrolle:** Code-Reviews vor Integration möglich

---

## 🎯 Standardablauf (Visual Studio Code)

1. **Branch erstellen & auschecken** – Neuen Branch erstellen und zu diesem wechseln
2. **Datei ändern** – Änderungen vornehmen und speichern
3. **Committen** – Änderungen mit aussagekräftiger Nachricht speichern
4. **Pushen** – Änderungen auf GitHub hochladen

---

## 📋 Branch-Naming-Konventionen

Um Branches übersichtlich zu halten, verwenden wir Präfixe:

- `feature/...` – Neue Funktionen (z.B. `feature/login-form`)
- `fehlerbehebung/...` – Fehlerbeheberungen (z.B. `fehlerbehebung/passwort-reset`)
- `dokumentation/...` – Dokumentation (z.B. `dokumentation/readme-update`)
- `test/...` – Tests (z.B. `test/unit-tests`)

---

## 💬 Gute Commit-Nachrichten

Eine gute Commit-Nachricht beschreibt **WAS** geändert wurde und **WARUM**:

| ✅ Gut | ❌ Schlecht |
|--------|-----------|
| `funktion: login-formular hinzufuegen` | `aktualisiert` |
| `fehler: passwort-validierung korrigieren` | `fix` |
| `dokumentation: setup-anleitung erweitern` | `geaendert` |

---

## 👉 Übungsaufgaben

Siehe: [AUFGABEN.md](AUFGABEN.md)

---

**Plattform:** GitHub  
**Werkzeug:** Visual Studio Code
