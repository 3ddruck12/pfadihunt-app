# Pfadihunt — Android-App

GPS-Tracking-App für die Outdoor-Schnitzeljagd **Pfadihunt**. Hunter und Spieler senden Live-Positionen an den Spielleiter-Server.

## Download

**[Pfadihunt APK herunterladen](https://github.com/3ddruck12/pfadihunt-app/releases/latest/download/pfadihunt.apk)**

Stabile URL (für QR-Codes):

```
https://github.com/3ddruck12/pfadihunt-app/releases/latest/download/pfadihunt.apk
```

## Voraussetzungen

- Android 8+ (API 26)
- Standortberechtigung (genau)
- Benachrichtigungen (Android 13+) für Hintergrund-Tracking
- Kamera nur für QR-Scan bei der Registrierung

## Installation (Sideloading)

1. APK auf dem Smartphone herunterladen
2. Unter **Einstellungen → Sicherheit** die Installation aus unbekannten Quellen für den Browser erlauben
3. APK öffnen und installieren
4. App starten und Registrierungs-QR vom Spielleiter scannen (oder Server-URL + Code eingeben)

Ausführliche Anleitung: [docs/install.md](docs/install.md)

## Nach der Installation

Der Spielleiter legt im Web-Panel einen Tracker an und zeigt einen **Registrierungs-QR-Code**. In der App:

1. QR-Code scannen **oder** Server-URL + Code (`GPS-XXXX-XXXX`) eingeben
2. **Tracking starten** — eine dauerhafte Benachrichtigung hält GPS aktiv

## Berechtigungen & Akku

Unter **Einstellungen → Apps → Pfadihunt → Akku** die Akkuoptimierung deaktivieren, damit Tracking bei ausgeschaltetem Display zuverlässig läuft.

## Quellcode

Der Anwendungsquellcode wird im privaten Entwicklungs-Repository gepflegt. Bei Bedarf kann der Quellcode gemäß GPL-3.0 beim Projektverantwortlichen angefordert werden.

## Lizenz

Die App wird unter der [GNU GPL v3](LICENSE) verteilt.
