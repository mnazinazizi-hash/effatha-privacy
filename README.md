
# Privacy Policy for Effatha

**Effective Date:** October 31, 2026  
**Last Updated:** October 31, 2026

Effatha ("we," "our," or "us"), operated by Stephen Maingi Ngugi, is committed to protecting your privacy. This Privacy Policy explains how your personal information is collected, used, disclosed, and safeguarded when you use our mobile application, **Effatha** (Package Name: `com.sancta.scriptura`).

By using the Effatha mobile application, you agree to the collection and use of information in accordance with this Privacy Policy.

---

## 1. Information We Collect

We collect information directly from you when you interact with the app, as well as automatically through essential app operations and third-party API integrations.

### A. Personal Information You Provide
* **Account Information:** When you register or sign in using Supabase Auth or Google Sign-In, we collect your email address, full name, display name, profile photo (optional), and country.
* **User Content & App Activity:** We store your saved Bible verses, highlights, custom notes, prayer completion history, reading progress, and reminder preferences.
* **Feedback & Support Messages:** If you send us feedback through the app, your message and support details are processed to assist you.
* **AI Queries ("Ask" Feature):** Questions submitted via our AI Scripture assistant ("Ask") and relevant conversation context are processed to generate response text.

### B. Information Automatically Collected & Caching
* **Local Storage & Caching:** To provide seamless offline access and session state management, Effatha caches data locally on your device via `AsyncStorage` and an SQLite storage adapter. This includes local profile snapshots, saved verses, notes, settings, temporary offline API caches, and encrypted/persisted session tokens.
* **API Telemetry & Identifiers:** To serve Bible text content and fulfill licensing guidelines, API.Bible automatically receives session identifiers and generated device tokens (FUMS telemetry) associated with Bible content requests.

---

## 2. Device Permissions Required

Effatha requests access to specific device features to enable core functional capabilities:

* **Microphone & Speech Recognition (`RECORD_AUDIO`, `MODIFY_AUDIO_SETTINGS`):** Used strictly when you choose to use voice features or speech recognition within the app. Audio data is used in real time and is not sold or repurposed.
* **Notifications & Exact Alarms (`POST_NOTIFICATIONS`, `SCHEDULE_EXACT_ALARM`):** Used to send local prayer, Scripture, and daily reminder notifications configured by you.
* **Photo Library:** Used exclusively if you choose to upload or update your custom profile picture.

*Note: Camera access is explicitly disabled within our media selectors, and Effatha does not track or collect your real-time physical GPS location.*

---

## 3. How We Use Your Information

We use the collected information for the following purposes:
* To create, authenticate, and maintain your account state across app sessions.
* To synchronize your saved verses, highlights, prayer logs, and custom preferences across devices via our backend database.
* To generate personalized AI responses via our Scripture context processing services.
* To send user-scheduled local prayer reminders and notification alerts.
* To process user feedback, resolve bugs, and deliver customer support.

---

## 4. Third-Party Services & Integrations

Effatha integrates with select, trusted third-party service providers to handle specialized app functionality:

* **Supabase (Backend Infrastructure):** Used for database management, account authentication, cloud edge functions, and secure user data synchronization.
* **Google Sign-In / Google Identity Services:** Used as an optional third-party authentication method for quick account login.
* **DeepSeek API:** Powers our AI Scripture assistant ("Ask") feature. Query text and relevant biblical context are sent to generate AI-driven responses.
* **API.Bible (BSB & Content Providers):** Delivers licensed Bible text and processes required FUMS session telemetry.
* **Resend:** Processes user feedback form submissions and routes administrative support emails.
* **Expo Infrastructure (EAS / Updates):** Provides over-the-air update services and app delivery infrastructure.

*Effatha does NOT include third-party advertising SDKs (e.g., AdMob), behavioral tracking networks, or commercial telemetry suites (e.g., Firebase Analytics, Sentry, or PostHog).*

---

## 5. Data Security & Storage

We implement administrative and technical security controls to safeguard your data. Authentication sessions are managed securely through Supabase Auth, and API communication with edge servers is transmitted via HTTPS/SSL encryption. 

While we use industry-standard precautions, no method of transmission over the internet or electronic local storage is 100% secure. You are responsible for maintaining the confidentiality of your login credentials.

---

## 6. User Rights, Account Deletion & Retention

* **Data Access & Updates:** You can view, edit, or delete your saved notes, highlights, and profile preferences directly inside the app settings.
* **Account Deletion:** You can request the complete deletion of your account and associated cloud data directly within the app settings via Supabase Auth integration, or by contacting support.
* **Guest Mode:** If you use Effatha without logging in, your preferences, reading history, and notes remain stored locally on your device's memory.

---

## 7. Children's Privacy

Effatha does not knowingly collect personal identifiable information from children under 13 years of age. If you believe that a child has provided us with personal information without parental consent, please contact us immediately so that we can take necessary steps to remove the data.

---

## 8. Changes to This Privacy Policy

We may update our Privacy Policy from time to time. Any changes will be posted within the app or on the hosted Privacy Policy link, and the "Last Updated" date at the top will be updated accordingly.

---

## 9. Contact Us

If you have any questions, feedback, or concerns regarding this Privacy Policy or data privacy in Effatha, please contact us at:

* **Support & Privacy Email:** choicedev5@gmail.com
* **Developer/Operator:** Stephen Maingi Ngugi
