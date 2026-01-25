# Datenschutzerklärung für FlexStock

**Gültig ab:** 25. Januar 2026  
**Letzte Aktualisierung:** 25. Januar 2026

---

## 1. Verantwortlicher

**Entwickler:** Kathrin Osswald  
**App Name:** FlexStock  
**Package:** com.kaoscode.flexstock

---

## 2. Datenschutz auf einen Blick

FlexStock ist eine Offline-Inventarverwaltungs-App, die **keine Daten an Server oder Cloud-Dienste sendet**. Alle Ihre Daten bleiben lokal auf Ihrem Gerät gespeichert.

### Wichtigste Punkte:
- ✅ **100% Offline** - Keine Cloud-Synchronisation
- ✅ **Lokale Speicherung** - Alle Daten auf Ihrem Gerät (SQLite)
- ✅ **Keine Datensammlung** - Wir sammeln keine persönlichen Informationen
- ✅ **Keine Server-Kommunikation** - Außer für optionale Features
- ✅ **Jederzeit löschbar** - Sie haben volle Kontrolle

---

## 3. Welche Daten werden erfasst?

### A. Daten, die lokal auf Ihrem Gerät gespeichert werden

Die App speichert folgende Daten **ausschließlich lokal** auf Ihrem Gerät in einer SQLite-Datenbank:

- **Inventar-Artikel**
  - Artikel-Name, Beschreibung, Barcode
  - Kategorie, Menge, Lagerort
  - Preis, Ablaufdatum, Notizen
  - Fotos (Base64 codiert)

- **Kategorien** - Selbst erstellte Kategorien

- **Orte** - Selbst definierte Lagerorte

- **Custom Fields** - Von Ihnen erstellte benutzerdefinierte Felder

- **App-Einstellungen**
  - Dark Mode Einstellung
  - Sprache
  - Premium-Status (lokal gespeichert)

### B. Daten, die an externe APIs gesendet werden (Optional)

Wenn Sie die **Barcode-Scanner-Funktion** nutzen, werden folgende externe Services automatisch genutzt:

| Service | Daten | Zweck | Datenschutz |
|---------|-------|-------|-------------|
| **OpenFoodFacts** | Barcode-Nummer | Produkt-Informationen abrufen | Community-Projekt, GDPR-konform |
| **ISBN API** | ISBN-Nummer | Buchdetails abrufen | GDPR-konform |
| **Wikidata** | Barcode/ISBN | Zusätzliche Infos | Open-Source, GDPR-konform |

**Hinweis:** Diese API-Lookups können nicht deaktiviert werden, wenn Sie die Barcode-Scanner-Funktion nutzen. Ihre Barcode-Nummern werden an diese Services gesendet, um Produkt-Informationen zu abrufen.

**Wenn Sie diese nicht möchten:** Sie können einfach die Scanner-Funktion nicht nutzen und Artikel manuell erstellen.

### C. Daten, die wir NICHT erfassen

Wir sammeln und speichern **NICHT**:
- ❌ Ihren Namen oder E-Mail
- ❌ Ihren Standort (GPS)
- ❌ Ihre Kontakte
- ❌ Ihre Aktivitätsprotokollierung
- ❌ Ihr Suchverlauf außerhalb der App
- ❌ Biometrische Daten
- ❌ Telefonnummer
- ❌ Kalender oder Ereignisse (außer lokal erstellten Ablaufdaten)

---

## 4. Google AdMob (Werbung)

### Werbeanzeigen in der kostenlosen Version

Die kostenlose Version zeigt Werbung über **Google AdMob**. Google sammelt dabei:

- **Anonyme Werbe-ID** (nicht personenbezogen)
- **Geräteinformationen** (OS, Gerättyp)
- **App-Nutzung** (Impressionen, Klicks)

**Sie können dies verhindern:**
- Kaufen Sie die Premium-Version (€2,99) → Werbung wird komplett deaktiviert
- Die App funktioniert auch ohne Werbung im kostenlosen Modus

**Mehr Info:** [Google Privacy Policy](https://policies.google.com/privacy)

---

## 5. In-App-Käufe

### Premium-Version (€2,99)

- **Produkt:** Werbefreie Nutzung
- **Zahlungsabwicklung:** Google Play Billing
- **Daten:** Transaktionen werden von Google verwaltet
- **Speicherung:** Premium-Status wird lokal auf Ihrem Gerät gespeichert

**Hinweis:** Wir erhalten keine Zahlungsdaten. Alle Transaktionen werden über Google Play abgewickelt.

**Rückgaberecht:** Google Play bietet ein 15-Minuten-Rückgaberecht auf In-App-Käufe.

---

## 6. Berechtigungen

### Warum die App diese Berechtigungen braucht:

| Berechtigung | Grund |
|--------------|-------|
| **Kamera** | Zum Machen von Fotos von Artikeln und Barcode-Scanning |
| **Speicher** | Zum Zugriff auf Galerie-Bilder und Backup-Export |
| **Internet** | Für Google AdMob (Werbung) und optionale Barcode-Lookups |
| **Benachrichtigungen** | Für Ablaufdatum-Erinnerungen |

**Keine versteckten Berechtigungen:**
- Wir fragen NICHT nach: Standort, Kontakte, Kalender, SMS, Telefon, etc.
- Sie haben volle Kontrolle - alle Berechtigungen sind optional und können in Android-Einstellungen deaktiviert werden

---

## 7. Datensicherheit

### Wie wir Ihre Daten schützen:

1. **Lokale Speicherung** - Daten bleiben auf Ihrem Gerät
2. **Android-Berechtigungssystem** - App ist von anderen Apps isoliert
3. **Keine Verschlüsselung von Nutzerdaten** - SQLite ist Standard (aber on-device)
4. **HTTPS** - Für externe API-Calls (OpenFoodFacts, etc.)
5. **Keine Hardcodung von Secrets** - API-Keys sind nicht sichtbar

### Datenverlust vermeiden:

- **Backup-Funktion:** Exportieren Sie Ihre Daten als JSON-Datei
- **Wiederherstellung:** Importieren Sie Backup jederzeit
- **Sicherung:** Speichern Sie Backups in Cloud-Storage Ihrer Wahl (OneDrive, Google Drive, etc.)

---

## 8. Datenspeicherung & -aufbewahrung

### Wie lange werden Daten gespeichert?

- **Lokal:** Solange bis Sie die App deinstallieren oder Daten manuell löschen
- **Google AdMob:** Gemäß [Google Privacy Policy](https://policies.google.com/privacy) (üblicherweise 90 Tage aggregiert)
- **Zahlungsdaten:** Gemäß Google Play-Richtlinie

### Datenträger:

- **Speicherort:** Interner App-Storage auf Ihrem Android-Gerät
- **Zugriff:** Nur FlexStock und das Android-System können auf diese Daten zugreifen

---

## 9. Ihre Rechte (GDPR)

Als EU-Bürger haben Sie folgende Rechte:

| Recht | Wie Sie es nutzen |
|----|----|
| **Recht auf Auskunft** | Kontaktieren Sie uns - wir haben keine persönlichen Daten |
| **Recht auf Löschung** | Deinstallieren Sie die App - alle Daten werden gelöscht |
| **Recht auf Datenportabilität** | Nutzen Sie die Backup-Export-Funktion |
| **Recht auf Widerspruch** | Deaktivieren Sie Werbung in den Einstellungen |
| **Recht auf Berichtigung** | Sie können alle Daten direkt in der App bearbeiten |

**Da wir keine persönlichen Daten sammeln, können die meisten GDPR-Anfragen sofort erfüllt werden.**

---

## 10. Drittanbieter und externe Links

### Externe Services:

1. **Google AdMob** - Werbeplattform
2. **OpenFoodFacts** - Produkt-Datenbank (Community)
3. **ISBN API** - Buch-Informationen
4. **Wikidata** - Allgemeine Informationen

**Datenschutz:** Diese Services haben ihre eigenen Datenschutzerklärungen. Wir sind nicht verantwortlich für deren Datenschutzpraktiken, aber wir nutzen nur vertrauenswürdige, etablierte Services.

---

## 11. Änderungen an dieser Datenschutzerklärung

Wir können diese Datenschutzerklärung jederzeit aktualisieren. Änderungen werden mit "Letzte Aktualisierung" gekennzeichnet.

**Beim nächsten App-Start werden Sie benachrichtigt, wenn sich diese Erklärung wesentlich ändert.**

---

## 12. Kontakt

**Für Fragen zum Datenschutz:**

📧 **E-Mail:** kathrin@kaoscode.com  
🏢 **Entwickler:** Kathrin Osswald  
🌐 **Website:** https://kaoscode.com (falls vorhanden)

**Antwortzeit:** Normalerweise innerhalb von 7 Arbeitstagen

---

## 13. Spezifische Informationen für verschiedene Länder

### EU/DSGVO:
- FlexStock ist vollständig DSGVO-konform
- Keine Datentransfer außer Ihrem Gerät

### USA/CCPA:
- Keine Datenverkäufe oder Weitergabe

### Australien/Privacy Act:
- Alle lokale Speicherung, GDPR-konform

---

## 14. Zusammenfassung

**Das Wichtigste:**

✅ **Ihre Daten bleiben privat** - 100% auf Ihrem Gerät  
✅ **Wir sammeln nichts über Sie** - Keine E-Mail, Name, Standort  
✅ **Volle Kontrolle** - Löschen Sie Daten, wenn Sie möchten  
✅ **Optional werbefrei** - Premium für €2,99  
✅ **GDPR-konform** - Für EU-Bürger  
✅ **Transparent** - Sie wissen genau, was die App tut

---

**FlexStock respektiert Ihre Privatsphäre. Das ist uns wichtig.** 🔒

---

*Diese Datenschutzerklärung ist in Deutsch und kann ins Englische übersetzt werden.*

*Alle Zeiten in UTC+1 (CET)*

**Gültig für FlexStock Version 1.0.0 und später**

---

---

# Privacy Policy for FlexStock

**Valid from:** January 25, 2026  
**Last Updated:** January 25, 2026

---

## 1. Responsible Party

**Developer:** Kathrin Osswald  
**App Name:** FlexStock  
**Package:** com.kaoscode.flexstock

---

## 2. Privacy at a Glance

FlexStock is an offline inventory management app that **does not send data to servers or cloud services**. All your data remains stored locally on your device.

### Key Points:
- ✅ **100% Offline** - No cloud synchronization
- ✅ **Local Storage** - All data on your device (SQLite)
- ✅ **No Data Collection** - We do not collect personal information
- ✅ **No Server Communication** - Except for optional features
- ✅ **Always Deletable** - You have full control

---

## 3. What Data is Collected?

### A. Data stored locally on your device

The app stores the following data **exclusively locally** on your device in a SQLite database:

- **Inventory Items**
  - Item name, description, barcode
  - Category, quantity, storage location
  - Price, expiration date, notes
  - Photos (Base64 encoded)

- **Categories** - Your custom categories

- **Locations** - Your custom storage locations

- **Custom Fields** - Custom fields you create

- **App Settings**
  - Dark mode setting
  - Language
  - Premium status (locally stored)

### B. Data sent to external APIs

When you use the **barcode scanner function**, the following external services are automatically used:

| Service | Data | Purpose | Privacy |
|---------|------|---------|---------|
| **OpenFoodFacts** | Barcode number | Retrieve product information | Community project, GDPR-compliant |
| **ISBN API** | ISBN number | Retrieve book details | GDPR-compliant |
| **Wikidata** | Barcode/ISBN | Additional information | Open-source, GDPR-compliant |

**Note:** These API lookups cannot be disabled when using the barcode scanner function. Your barcode numbers are sent to these services to retrieve product information.

**If you don't want this:** You can simply not use the scanner function and create items manually.

### C. Data we do NOT collect

We do NOT collect and store:
- ❌ Your name or email
- ❌ Your location (GPS)
- ❌ Your contacts
- ❌ Your activity log
- ❌ Your search history outside the app
- ❌ Biometric data
- ❌ Phone number
- ❌ Calendar or events (except locally created expiration dates)

---

## 4. Google AdMob (Advertising)

### Advertisements in the free version

The free version displays advertisements through **Google AdMob**. Google collects:

- **Anonymous advertising ID** (not personally identifiable)
- **Device information** (OS, device type)
- **App usage** (impressions, clicks)

**You can prevent this:**
- Purchase the Premium version (€2.99) → Advertising is completely disabled
- The app also works without advertising in free mode

**More info:** [Google Privacy Policy](https://policies.google.com/privacy)

---

## 5. In-App Purchases

### Premium Version (€2.99)

- **Product:** Ad-free usage
- **Payment Processing:** Google Play Billing
- **Data:** Transactions are managed by Google
- **Storage:** Premium status is stored locally on your device

**Note:** We do not receive payment data. All transactions are processed through Google Play.

**Right of withdrawal:** Google Play offers a 15-minute refund window for in-app purchases.

---

## 6. Permissions

### Why the app needs these permissions:

| Permission | Reason |
|-----------|--------|
| **Camera** | To take photos of items and barcode scanning |
| **Storage** | To access gallery images and backup export |
| **Internet** | For Google AdMob (advertising) and optional barcode lookups |
| **Notifications** | For expiration date reminders |

**No hidden permissions:**
- We do NOT ask for: Location, contacts, calendar, SMS, phone, etc.
- You have full control - all permissions are optional and can be disabled in Android settings

---

## 7. Data Security

### How we protect your data:

1. **Local Storage** - Data remains on your device
2. **Android Permission System** - App is isolated from other apps
3. **No Encryption of User Data** - SQLite is standard (but on-device)
4. **HTTPS** - For external API calls (OpenFoodFacts, etc.)
5. **No Hardcoded Secrets** - API keys are not visible

### Preventing Data Loss:

- **Backup Function:** Export your data as a JSON file
- **Restore:** Import backups anytime
- **Secure Storage:** Save backups to cloud storage of your choice (OneDrive, Google Drive, etc.)

---

## 8. Data Storage & Retention

### How long is data stored?

- **Locally:** Until you uninstall the app or manually delete data
- **Google AdMob:** According to [Google Privacy Policy](https://policies.google.com/privacy) (typically 90 days aggregated)
- **Payment Data:** According to Google Play policy

### Storage Location:

- **Location:** Internal app storage on your Android device
- **Access:** Only FlexStock and the Android system can access this data

---

## 9. Your Rights (GDPR)

As an EU citizen, you have the following rights:

| Right | How to Use It |
|----|----|
| **Right to Information** | Contact us - we have no personal data |
| **Right to Deletion** | Uninstall the app - all data is deleted |
| **Right to Data Portability** | Use the backup export function |
| **Right to Object** | Disable advertising in settings |
| **Right to Rectification** | You can edit all data directly in the app |

**Since we do not collect personal data, most GDPR requests can be fulfilled immediately.**

---

## 10. Third Parties and External Links

### External Services:

1. **Google AdMob** - Advertising platform
2. **OpenFoodFacts** - Product database (Community)
3. **ISBN API** - Book information
4. **Wikidata** - General information

**Privacy:** These services have their own privacy policies. We are not responsible for their privacy practices, but we only use trusted, established services.

---

## 11. Changes to this Privacy Policy

We may update this privacy policy at any time. Changes will be marked with "Last Updated".

**You will be notified of significant changes the next time you start the app.**

---

## 12. Contact

**For privacy questions:**

📧 **Email:** kathrin@kaoscode.com  
🏢 **Developer:** Kathrin Osswald  
🌐 **Website:** https://kaoscode.com (if available)

**Response Time:** Usually within 7 business days

---

## 13. Country-Specific Information

### EU/GDPR:
- FlexStock is fully GDPR-compliant
- No data transfer outside your device

### USA/CCPA:
- No data sales or sharing

### Australia/Privacy Act:
- All local storage, GDPR-compliant

---

## 14. Summary

**The Most Important:**

✅ **Your data stays private** - 100% on your device  
✅ **We collect nothing about you** - No email, name, location  
✅ **Full control** - Delete data whenever you want  
✅ **Optionally ad-free** - Premium for €2.99  
✅ **GDPR-compliant** - For EU citizens  
✅ **Transparent** - You know exactly what the app does

---

**FlexStock respects your privacy. This matters to us.** 🔒

---

*This privacy policy is available in German and English.*

*All times in UTC+1 (CET)*

**Valid for FlexStock version 1.0.0 and later**
