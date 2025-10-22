# Eversicht | ClaroApp

**Eversicht** ist Ihr privater Assistent zur umfassenden Verwaltung von Verträgen, Abonnements und Garantien. Die App hilft Ihnen dabei, den Überblick über Ihre Kündigungsfristen und monatlichen Kosten zu behalten, und legt dabei größten Wert auf **Datenschutz und Sicherheit**.

## ✨ Hauptfunktionen

* **Vertrags- & Garantieverwaltung:** Erfassen Sie alle Details Ihrer Verträge, Abonnements und Produktgarantien.
* **Intelligente Fristenberechnung:** Automatische Berechnung des nächsten Kündigungsstichtags, basierend auf Laufzeit, Kündigungsfrist und Kündigungsregeln (Monats-/Quartals-/Jahresende).
* **Kostenanalyse:** Dashboard-Widgets zur Visualisierung der monatlichen Gesamtkosten nach Kategorien (Donut-Chart).
* **Dokumentenscanner (OCR):** Nutzt **lokale Apple-Frameworks (Vision/NaturalLanguage)**, um Dokumente (Verträge, Belege) direkt auf dem Gerät zu scannen und relevante Daten (Firmennamen, Daten, Beträge, Vertragsnummern) automatisch zu extrahieren.
* **Brief-Generator:** Erstellung von fertigen, versandbereiten **Kündigungsschreiben** und allgemeinen Briefvorlagen als PDF, personalisiert mit Ihren und den Firmendaten.
* **iCloud (CloudKit) Sync:** Sichere, private Synchronisierung der Daten zwischen Ihren Geräten über Ihr persönliches iCloud-Konto.
* **Premium-Modell:** Freischaltung unlimitierter Einträge via In-App-Abonnement (**Eversicht+**).

## 🛡️ Datenschutz & Sicherheit – Privacy by Design

Der Schutz Ihrer sensiblen Informationen ist die höchste Priorität der App-Architektur.

| Aspekt | Implementierung |
| :--- | :--- |
| **Datenspeicherung** | Alle privaten Daten (Vertragsdetails, Dokumente, Notizen) werden **ausschliesslich lokal** auf Ihrem Gerät und in Ihrem **privaten iCloud-Konto (CloudKit)** gespeichert. |
| **Zugriff durch Entwickler** | Der Entwickler hat **zu keinem Zeitpunkt** Zugriff auf Ihre Vertrags- oder Garantiedaten. |
| **Dokumentenanalyse** | Die **OCR-Texterkennung** zur Datenextraktion erfolgt vollständig **auf Ihrem Gerät** mithilfe von Apple Vision. Es werden keine gescannten Dokumente an einen Server gesendet. |

## 🛠️ Technische Details (für Entwickler)

* **Plattform:** iOS / SwiftUI
* **Persistenz:** Swift `Codable` mit lokalem Cache und **CloudKit** für die Synchronisation.
* **KI/ML-Frameworks:** `Vision`, `VisionKit`, `NaturalLanguage` für die lokale Dokumentenanalyse.
* **Zusatz-Frameworks:** `Charts` (für die Kostenanalyse), `PDFKit`, `MapKit`, `StoreKit`.
* **Fokus:** **Modernes SwiftUI-Design** mit Dark Mode/Light Mode-Unterstützung und benutzerdefinierten Farbthemen.

---
