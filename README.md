# MOBIQ-Dokumentation

Die Produktdokumentation des erfundenen ERP-Herstellers MOBIQ (Musterhaus Software GmbH), Stand **vor** Release 26.4. Sie ist also so veraltet, wie sie es nach dem Release ohne neuraldoc wäre.

| Ordner | Entspricht | Inhalt |
|---|---|---|
| `confluence/` | Confluence Cloud REST v2 | 4 Bereiche, 33 Seiten im Storage-Format; `storage/*.xml` lesbar formatiert, `page_meta.json` mit Labels (Doku-Art) und Anhängen |
| `dokumente/` | SharePoint / Microsoft Graph | 7 Dateien (Word, Excel, PDF) unter `files/`, `driveItems.json` und der extrahierte Text in `extracted.json` |

Teil des Evaluationsdatensatzes: Code in `mobiq-code`, Datenbank in `mobiq-db`, Generator, Tickets und Lösung in `mobiq`. Nicht von Hand ändern, sondern im Repository `mobiq` neu erzeugen (`node generate.mjs && node publish.mjs`).

Alle Firmen, Personen und Inhalte sind erfunden.
