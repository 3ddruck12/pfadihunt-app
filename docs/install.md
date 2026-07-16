# Pfadihunt-App installieren (Android)

## Schritt 1: APK herunterladen

Öffne auf dem Smartphone:

https://github.com/3ddruck12/pfadihunt-app/releases/latest/download/pfadihunt.apk

Oder scanne den Download-QR-Code im Spielleiter-Web-Panel.

## Schritt 2: Installation erlauben

Android blockiert APKs außerhalb des Play Store standardmäßig.

- Beim Download: **Trotzdem herunterladen** bestätigen
- Bei der Installation: **Aus dieser Quelle installieren** für Chrome/Firefox/Dateimanager erlauben

## Schritt 3: App installieren

Tippe auf die heruntergeladene `pfadihunt.apk` und folge den Dialogen.

Play Protect kann bei unbekannten Apps warnen — das ist bei Sideloading normal.

### Signaturkonflikt beim Update

Meldung *„App-Signaturkonflikt … deinstallieren und erneut installieren“*:

1. Alte Pfadihunt-App **deinstallieren** (Einstellungen → Apps → Pfadihunt → Deinstallieren)
2. APK **neu herunterladen** und installieren

Das passiert einmalig, wenn zuvor eine Test-APK mit anderer Signatur installiert war. Ab Release-Builds mit festem Keystore funktionieren Updates ohne Deinstallation.

## Schritt 4: Mit dem Spiel verbinden

1. Spielleiter legt im Admin-Panel einen **Smartphone-Tracker** an
2. **Registrierungs-QR** in der Pfadihunt-App scannen
3. **Tracking starten**

Der Einmalcode ist 24 Stunden gültig und funktioniert nur auf einem Gerät.

## Updates

Neue Versionen erscheinen unter [Releases](https://github.com/3ddruck12/pfadihunt-app/releases). APK erneut herunterladen und installieren (Update über bestehende Installation).
