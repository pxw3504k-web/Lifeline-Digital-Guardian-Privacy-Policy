# Privacy Policy for Lifeline SOS

**Last Updated:** [2026.01.25]
**Developer:** [pan]
**Contact:** [pxw3504k@gmail.com]

This Privacy Policy explains how the **Lifeline SOS** mobile application (“App”) collects, uses, stores, and protects your personal information. By installing or using the App, you consent to the practices described below.

The Lifeline SOS App is designed as a personal safety tool. While we prioritize local data storage, **we utilize specific secure cloud services (Google Firebase) solely to enable critical emergency features**, such as sending automatic SOS emails and storing emergency evidence. We do not sell your data to third parties.

---

## 1. Information We Collect

The App accesses or processes data primarily when you actively use specific features.

### a) Location Information
* **When collected:** When you manually activate the SOS function, when an automated inactivity alert is triggered, or when you use the "Check-in" feature.
* **Type of data:** Precise GPS coordinates (latitude/longitude).
* **Purpose:** To generate a map link included in your emergency SMS and **Email alerts**.
* **Cloud Transmission:** During an SOS event, your location data is securely transmitted to our cloud backend (Firebase) to trigger the automated email dispatch.

### b) Contact Information
* **When collected:** When you add or manage emergency contacts within the App.
* **Type of data:** Names, phone numbers, and **email addresses**.
* **Purpose:**
    1.  To enable one-tap calling and SMS alerts.
    2.  To send **automated emergency emails** via our cloud service.
    3.  To send a **verification/notification email** to your contacts informing them that you have added them.
* **Note:** We do not access your entire address book. We only process the specific contacts you manually select or input.

### c) Audio & Media (Emergency Evidence)
* **When collected:** Only when an SOS event is triggered (if this feature is enabled in settings).
* **Type of data:** Audio recordings of the device's surroundings.
* **Purpose:** To serve as evidence of the emergency situation.
* **Cloud Transmission:** Audio files are encrypted and uploaded to our secure cloud storage (Firebase Storage) to generate a download link, which is included in the emergency email sent to your contacts.

### d) Device & Usage Data
The App **does not** collect browsing history or unnecessary usage statistics. We may collect anonymous crash logs (via Firebase Crashlytics) to help us fix stability issues, which you can opt-out of in settings.

---

## 2. How We Use Your Information

Your data is used **solely for emergency response and app functionality**:
* To transmit your live location and status to your trusted contacts via SMS and **Email**.
* To store emergency evidence (audio) in the cloud temporarily for retrieval by your contacts.
* To notify your contacts that they have been added to your safety network.
* To authenticate your device with our cloud servers to prevent abuse.

**We never use your data for advertising, profiling, or commercial purposes.**

---

## 3. Data Storage and Security

* **Local Storage:** Your settings, contact list, and preferences are stored locally on your device.
* **Cloud Storage (Firebase):**
    * **Emergency Emails:** Data required to send emails (recipient address, location link) is processed by Google Firebase Cloud Functions.
    * **Evidence:** Audio recordings are stored in Google Firebase Storage.
* **Security:** All data transmitted between your device and our cloud servers is encrypted using **SSL/TLS**. Cloud data is protected by Google's industry-standard security infrastructure.
* **Data Retention:** Emergency data on our servers is retained only as long as necessary to fulfill the emergency function or until you request deletion.

---

## 4. Data Sharing and Disclosure

We **do not sell, rent, or share** your personal information with advertisers or unauthorized third parties.

**We share data only in the following scenarios:**
1.  **With Your Emergency Contacts:**
    * Your location, audio evidence, and status are shared with the people *you* designated.
2.  **With Service Providers (Infrastructure):**
    * We use **Google Firebase** (provided by Google LLC) as our backend infrastructure to host the database, cloud functions, and file storage required for the App to function. Google processes this data strictly in accordance with our instructions and their privacy terms.

---

## 5. Third-Party Services

The Lifeline SOS App integrates with the following third-party services to provide core functionality:

* **Google Firebase (Firestore, Cloud Functions, Storage):** Used for backend logic, database, and file storage. [Google Privacy Policy](https://policies.google.com/privacy)
* **Google Maps API:** Used to display your location and generate map links.
* **Firebase Crashlytics (Optional):** Used to report app crashes and improve stability.

---

## 6. Your Rights

As a user, you have the following rights:
* **Access & Review:** View all emergency contacts and settings stored in the App.
* **Edit or Delete:** Remove any contact or disable SOS features at any time.
* **Revoke Permissions:** Disable location, microphone, SMS, or internet permissions via your device settings (note: this may disable core SOS features).
* **Data Deletion:** You may request the deletion of your cloud-stored data (such as emergency logs) by contacting us. Uninstalling the App stops all future data collection.

---

## 7. Children’s Privacy

The App is not intended for users under 13 years old. We do not knowingly collect data from children.

---

## 8. Changes to This Policy

We may update this Privacy Policy to reflect changes in the App (e.g., new cloud features) or legal requirements. The updated policy will be posted here with a new “Last Updated” date.

---

## 9. Contact Us

If you have questions about this Privacy Policy or how your data is handled, please contact us:
**Email:** [pxw3504k@gmail.com]

We respond to all privacy-related inquiries within 7 business days.
