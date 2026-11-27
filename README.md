# Kleiderschrank – KI-gestützter digitaler Kleiderschrank

Ein Seminarprojekt unserer Vierergruppe: eine App, in der man die eigene Kleidung fotografiert, eine KI sie automatisch erkennt und einsortiert und daraus passende Outfits für Anlass, Wetter und Stil vorschlägt. Vorgeschlagen werden nur Kleidungsstücke, die man wirklich besitzt.

## Projektstand

| Phase | Inhalt | Status |
| --- | --- | --- |
| Konzept | Produkt- und Entwicklungsplan | Entwurf, wartet auf Abstimmung |
| Phase 0 | Einrichtung (Next.js, Supabase, Vercel) | Offen |
| Phase 1 | Design-System und Klick-Entwürfe | Offen |
| Phase 2 | Konto und Datenbank | Offen |
| Phase 3 | Foto-Upload und KI-Erkennung | Offen |
| Phase 4 | Kleiderschrank und Filter | Offen |
| Phase 5 | Onboarding und Profil | Offen |
| Phase 6 | Wetter und Outfit-Generator | Offen |
| Phase 7 | Austauschen, Speichern, Favoriten | Offen |
| Phase 8 | Feinschliff und Test | Offen |

## Dokumente

- [Produkt- und Entwicklungsplan](docs/produktplan.md): Konzept, Zielgruppen, Funktionen, MVP, User Journey, Seitenstruktur, Design, Technik, Datenstruktur und Phasen.
- [Architektur-Skizze](docs/architektur.png)

## Geplante Technik

- **Frontend:** Next.js (React, TypeScript) mit Tailwind CSS, als mobile Web-App (PWA)
- **Backend, Datenbank, Login, Bilder:** Supabase
- **KI:** ein multimodales Sprachmodell für Bilderkennung und Outfit-Vorschläge (Anbieter noch offen)
- **Wetter:** Open-Meteo
- **Veröffentlichung:** Vercel

## Wie wir mit GitHub arbeiten

- Der Hauptstand liegt auf dem Zweig `main`.
- Neue Inhalte (Pläne oder Code) kommen als **Pull Request**. Ihr seht dort genau, was sich ändert, und übernehmt es mit dem grünen Knopf „Merge pull request“.
- Geheime Schlüssel (z. B. für die KI) kommen nie ins Repository, sondern in eine lokale Datei `.env.local` und in die Einstellungen von Vercel.
