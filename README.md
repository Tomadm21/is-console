# IS Console

Impressum-Scraper Standalone für deutsche B2B-Lead-Generierung.

## Voraussetzungen
- **macOS 13+** oder **Linux** (Ubuntu/Debian/Fedora/Arch)
- Internet beim ersten Start (für Setup)
- Anthropic-Account ([claude.ai](https://claude.ai/login))

## Installation (macOS)

1. **Download** [aus dem latest-Release](https://github.com/Tomadm21/is-console/releases/latest):
   - `IS-Console-0.1.2-arm64.dmg` (Apple Silicon, M1/M2/M3/M4)
   - `IS-Console-0.1.2-x64.dmg` (Intel-Macs)
   - `Setup.command`
2. **DMG öffnen, App in Programme-Ordner ziehen**
3. **Setup.command doppelklicken** (Terminal öffnet sich, installiert Python/Node/Claude-CLI + Login). Dauer: ~5-10 min beim ersten Mal.
4. **App starten** mit Rechtsklick → "Öffnen" (nicht doppelklick — wegen Quarantäne-Flag des Browsers).

Falls "Image beschädigt": im Terminal:
```
xattr -cr "/Applications/IS Console.app"
```

## Installation (Linux)

1. Download `IS-Console-0.1.2-x86_64.AppImage` und `setup-linux.sh`
2. Setup ausführen:
   ```
   bash setup-linux.sh
   ```
3. App starten:
   ```
   chmod +x IS-Console-0.1.2-x86_64.AppImage
   ./IS-Console-0.1.2-x86_64.AppImage
   ```

## Erste Schritte
1. App starten → "manuell starten" → "Impressum LeadGen"
2. URL-Liste einfügen ODER xlsx hochladen
3. Run starten → fertig in `~/Downloads/impressum-leadgen-*.xlsx`

## Fragen?
[github.com/Tomadm21/is-console/issues](https://github.com/Tomadm21/is-console/issues)