# Datenschutzerklärung für FlexStock

**Gültig ab:** Version 1.1.0  
**Letzte Aktualisierung:** 27. Oktober 2026

[English version below](#privacy-policy-for-flexstock)

---

## 1. Verantwortlicher

**Entwicklerin:** Kathrin Osswald (KaOsCode)  
**App:** FlexStock  
**Package:** com.kaoscode.flexstock  
**Kontakt:** siehe [Abschnitt 9](#9-kontakt)

---

## 2. Datenschutz auf einen Blick

FlexStock ist eine Inventar-App, die **offline arbeitet**. Ihre Daten bleiben auf Ihrem Gerät.

- ✅ **Lokale Speicherung:** Alle Inventardaten liegen nur auf Ihrem Gerät.
- ✅ **Kein Konto, keine Cloud:** Wir betreiben keine Server und erhalten keine Ihrer Daten.
- ✅ **Keine Werbung, keine Analyse- oder Tracking-Dienste, keine In-App-Käufe.**
- ℹ️ **Einzige Ausnahme:** Beim Scannen eines Barcodes wird die Barcode-Nummer an öffentliche Produktdatenbanken gesendet (siehe [Abschnitt 4](#4-produktsuche-per-barcode)).

---

## 3. Lokal gespeicherte Daten

Die App speichert ausschließlich auf Ihrem Gerät, in einer SQLite-Datenbank und im privaten App-Speicher:

- **Artikel:** Name, Menge, Barcode, Kategorie, Lagerort sowie Ihre eigenen Felder (z. B. Ablaufdatum, Preis, Notizen)
- **Fotos**, die Sie aufnehmen oder aus der Galerie auswählen
- **Kategorien, Lagerorte, eigene Felder und die Einkaufsliste**
- **Zwischengespeicherte Produktinfos** aus der Barcode-Suche, damit derselbe Barcode nicht erneut abgefragt werden muss
- **Einstellungen:** Sprache, Design, Foto-Qualität, Uhrzeit für Erinnerungen

Diese Daten verlassen Ihr Gerät nur, wenn Sie selbst ein **Backup oder einen CSV-Export** erstellen und teilen. Wohin die Datei geht (z. B. Google Drive, E-Mail), entscheiden Sie über den Teilen-Dialog von Android.

Ist auf Ihrem Gerät die **Android-Datensicherung** (Google One) aktiviert, kann Android die App-Daten verschlüsselt in Ihrem Google-Konto sichern und bei einem Gerätewechsel wiederherstellen. Das steuern Sie in den Android-Einstellungen; FlexStock hat darauf keinen Zugriff.

Wenn Sie die App deinstallieren, werden alle lokal gespeicherten Daten gelöscht.

---

## 4. Produktsuche per Barcode

Wenn Sie einen Barcode scannen oder eingeben, fragt die App nacheinander folgende öffentliche Datenbanken ab, bis ein Produkt gefunden wird:

| Dienst | Betreiber |
|--------|-----------|
| Open Food Facts, Open Products Facts, Open Beauty Facts | Open Food Facts (gemeinnütziger Verein, Frankreich) |
| Open Library | Internet Archive (USA) |
| Google Books | Google (USA/Irland) |
| UPCitemdb | UPCitemdb (USA) |
| Wikidata | Wikimedia Foundation (USA) |
| Icecat | Icecat N.V. (Niederlande) |

- **Gesendet wird nur die Barcode-Nummer.** Name, Fotos oder andere Inventardaten werden nie übertragen.
- Wie bei jedem Internetabruf sehen die Dienste dabei technisch Ihre **IP-Adresse**. Das gilt auch, wenn die App ein Produktbild von dort anzeigt.
- Die Verbindungen sind verschlüsselt (HTTPS).
- **Rechtsgrundlage:** Art. 6 Abs. 1 lit. b DSGVO. Die Abfrage erfolgt nur, weil Sie die Produktsuche aktiv nutzen.
- **Wenn Sie das nicht möchten:** Legen Sie Artikel ohne Barcode-Scan an. Alle anderen Funktionen arbeiten ohne Internet.

Die Barcode-Erkennung selbst erfolgt **auf dem Gerät** (Google ML Kit). Das Kamerabild wird nicht hochgeladen. ML Kit kann laut Google anonyme technische Nutzungs- und Diagnosedaten (z. B. Gerätetyp, Leistung) an Google senden.

---

## 5. Berechtigungen

| Berechtigung | Wozu |
|--------------|------|
| **Kamera** | Barcodes scannen und Artikelfotos aufnehmen |
| **Fotos/Medien** | Bilder aus der Galerie auswählen |
| **Internet** | Produktsuche per Barcode (siehe Abschnitt 4) |
| **Benachrichtigungen** | Erinnerungen an Ablaufdaten und Mindestbestände |
| **Exakte Wecker, Start nach Neustart** | Erinnerungen zur gewählten Uhrzeit und auch nach einem Neustart zustellen |

Alle Erinnerungen werden lokal auf dem Gerät geplant, ohne Server. Sie können jede Berechtigung in den Android-Einstellungen entziehen. Die übrigen Funktionen bleiben nutzbar.

---

## 6. Bewertung im Play Store

Die App kann Sie gelegentlich über den offiziellen Dialog von Google Play um eine Bewertung bitten. Der Dialog wird von Google Play angezeigt und verarbeitet. FlexStock erfährt nicht, ob und wie Sie bewerten. Es gilt die [Datenschutzerklärung von Google](https://policies.google.com/privacy).

---

## 7. Ihre Rechte

Sie haben nach der DSGVO das Recht auf Auskunft, Berichtigung, Löschung, Einschränkung der Verarbeitung, Datenübertragbarkeit und Widerspruch sowie das Recht auf Beschwerde bei einer Datenschutz-Aufsichtsbehörde.

Da wir keine Daten von Ihnen erhalten, können Sie die meisten Rechte direkt in der App ausüben: Daten bearbeiten oder löschen, per Backup exportieren oder die App deinstallieren. Für Anfragen an die oben genannten Datenbanken wenden Sie sich bitte an deren Betreiber.

---

## 8. Kinder

FlexStock richtet sich nicht gezielt an Kinder und erhebt wissentlich keine Daten von Kindern.

---

## 9. Kontakt

📧 **E-Mail:** kaos-code@outlook.com  
🏢 **Entwicklerin:** Kathrin Osswald

---

## 10. Änderungen und frühere Versionen

Wenn sich die App ändert, passen wir diese Erklärung an und aktualisieren das Datum oben.

**Versionen vor 1.1.0** zeigten Werbung über Google AdMob, das dafür die Werbe-ID und Geräteinformationen verarbeitete, und boten einen optionalen Kauf über Google Play Billing an. Beides wurde mit Version 1.1.0 entfernt. Bitte aktualisieren Sie die App.

---
---

# Privacy Policy for FlexStock

**Valid from:** version 1.1.0  
**Last updated:** October 27, 2026

---

## 1. Controller

**Developer:** Kathrin Osswald (KaOsCode)  
**App:** FlexStock  
**Package:** com.kaoscode.flexstock  
**Contact:** see [section 9](#9-contact)

---

## 2. Privacy at a glance

FlexStock is an inventory app that **works offline**. Your data stays on your device.

- ✅ **Local storage:** All inventory data is stored only on your device.
- ✅ **No account, no cloud:** We run no servers and receive none of your data.
- ✅ **No ads, no analytics or tracking services, no in-app purchases.**
- ℹ️ **Only exception:** When you scan a barcode, the barcode number is sent to public product databases (see [section 4](#4-product-lookup-by-barcode)).

---

## 3. Data stored locally

The app stores data only on your device, in an SQLite database and in its private app storage:

- **Items:** name, quantity, barcode, category, location and your own fields (e.g. expiry date, price, notes)
- **Photos** you take or pick from the gallery
- **Categories, locations, custom fields and the shopping list**
- **Cached product info** from barcode lookups, so the same barcode does not have to be looked up again
- **Settings:** language, theme, photo quality, reminder time

This data only leaves your device if you create and share a **backup or CSV export** yourself. You choose the destination (e.g. Google Drive, email) in Android's share dialog.

If **Android backup** (Google One) is turned on for your device, Android may back up the app data encrypted to your Google account and restore it when you switch devices. You control this in Android settings; FlexStock has no access to it.

Uninstalling the app deletes all locally stored data.

---

## 4. Product lookup by barcode

When you scan or enter a barcode, the app queries the following public databases one after another until a product is found:

| Service | Operator |
|---------|----------|
| Open Food Facts, Open Products Facts, Open Beauty Facts | Open Food Facts (non-profit association, France) |
| Open Library | Internet Archive (USA) |
| Google Books | Google (USA/Ireland) |
| UPCitemdb | UPCitemdb (USA) |
| Wikidata | Wikimedia Foundation (USA) |
| Icecat | Icecat N.V. (Netherlands) |

- **Only the barcode number is sent.** Names, photos or other inventory data are never transmitted.
- As with any internet request, these services technically see your **IP address**. This also applies when the app shows a product image hosted by them.
- Connections are encrypted (HTTPS).
- **Legal basis:** Art. 6(1)(b) GDPR. The request only happens because you actively use the product lookup.
- **If you don't want this:** Add items without scanning. All other features work without internet.

Barcode recognition itself happens **on the device** (Google ML Kit). The camera image is not uploaded. According to Google, ML Kit may send anonymous technical usage and diagnostic data (e.g. device type, performance) to Google.

---

## 5. Permissions

| Permission | Purpose |
|------------|---------|
| **Camera** | Scan barcodes and take item photos |
| **Photos/media** | Pick images from the gallery |
| **Internet** | Product lookup by barcode (see section 4) |
| **Notifications** | Reminders for expiry dates and minimum stock |
| **Exact alarms, run at startup** | Deliver reminders at the chosen time, also after a restart |

All reminders are scheduled locally on the device, without a server. You can revoke any permission in Android settings. The remaining features stay available.

---

## 6. Rating on the Play Store

The app may occasionally ask you for a rating through Google Play's official dialog. The dialog is shown and processed by Google Play. FlexStock does not learn whether or how you rate it. [Google's privacy policy](https://policies.google.com/privacy) applies.

---

## 7. Your rights

Under the GDPR you have the right of access, rectification, erasure, restriction of processing, data portability and objection, as well as the right to lodge a complaint with a data protection supervisory authority.

Since we receive no data from you, you can exercise most rights directly in the app: edit or delete data, export it via backup, or uninstall the app. For requests concerning the databases listed above, please contact their operators.

---

## 8. Children

FlexStock is not directed at children and does not knowingly collect data from children.

---

## 9. Contact

📧 **Email:** kaos-code@outlook.com  
🏢 **Developer:** Kathrin Osswald

---

## 10. Changes and earlier versions

When the app changes, we update this policy and the date above.

**Versions before 1.1.0** showed ads via Google AdMob, which processed the advertising ID and device information for this purpose, and offered an optional purchase via Google Play Billing. Both were removed in version 1.1.0. Please update the app.
