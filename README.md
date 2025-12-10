# Privacy Policy for Nutrition Mate
**Effective Date:** 2025  
**Developer:** CG Software Solutions LLC  

Nutrition Mate ("the App," "we," "our," or "us") is a mobile application designed to assist users with nutritional tracking and related features. We are committed to protecting your privacy and ensuring that any data collected is handled responsibly and transparently. This Privacy Policy explains what information the App collects, how it is used, how it is stored, and the rights available to users.

By using Nutrition Mate, you consent to the practices described in this Privacy Policy.

---

## 1. Information We Collect
Nutrition Mate collects only the minimum data necessary to operate its features, improve performance, ensure stability, and serve non-personalized advertisements. We do **not** collect personally identifiable information such as your name, email address, phone number, or physical address.

### 1.1 Data You Enter Into the App (Stored Locally Only)
Nutrition and meal-related data (such as daily calorie intake, bucketed calorie values, and meal actions) are stored **locally on your device** using secure on-device key-value storage appropriate to the platform. This data is never transmitted to our servers or shared with third parties.

**Exception:** Privacy consent preferences are stored both locally (for offline functionality) and in Firebase Firestore (linked to your anonymous UID) to ensure consent choices persist and can be synchronized across app reinstalls. No nutrition, meal, or tracking data is ever stored in Firestore. Only user consent records and non-personal configuration data are associated with the anonymous UID.

- **Linked to you:** No  
- **Shared:** No  
- **Purpose:** App functionality only  

In this policy, "linked" follows Apple's App Store Privacy definition, meaning the data is not associated with a user's identity and cannot personally identify the user.

Your nutrition data never leaves your device.

---

### 1.2 Anonymous Authentication Identifier (Firebase Anonymous Auth)
The App uses Firebase Anonymous Auth solely to store user consent records and essential non-personal preferences. This identifier is randomly generated and cannot be used to identify you.

- **Collected:** Yes  
- **Linked to identity:** No  
- **Used for tracking:** No  
- **Shared with third parties:** No  
- **Purpose:** Consent storage and secure preference management  

---

### 1.3 Analytics Data (Aggregated and De-Identified)
We use Firebase Analytics to collect aggregated event-level data such as:

- Screen views  
- Interactions with the nutrition tracker  
- Ad load events  
- Feature usage metrics  

This information is automatically aggregated and **not linked to any identifiable user**. Precise nutrition data, personal attributes, and identifiable information are not transmitted.

- **Linked to identity:** No  
- **Shared:** With Firebase (Google)  
- **Purpose:** Analytics and performance insights  

---

### 1.4 Crash and Performance Data
Firebase Crashlytics collects crash logs and performance diagnostics, which may include:

- Device model  
- Operating system version  
- App version  
- Stack traces  
- Basic performance timing  

This helps us maintain stability and improve the App. The data is anonymized and cannot identify a user.

- **Linked to identity:** No  
- **Shared:** With Firebase Crashlytics (Google)  
- **Purpose:** Diagnostics and reliability  
- **Retention:** Up to 90 days  

---

### 1.5 Device Information
Non-personal device information is collected, such as:

- Device type and model  
- OS version  
- Screen size and resolution  
- Country/locale  
- App version  

This information supports analytics, diagnostics, and contextual advertising. Device information is not linked to your identity and cannot personally identify you.

- **Linked to identity:** No  
- **Shared:** With Firebase and Google AdMob  
- **Purpose:** Analytics, diagnostics, contextual advertising  

---

### 1.6 Advertising Data (Non-Personalized Ads Only)
The App displays ads through Google AdMob in **non-personalized mode**, meaning:

- The App does **not** request or access the Apple IDFA  
- No cross-app tracking occurs  
- Ads are contextual only  
- No interest-based targeting, profiling, or remarketing is performed  

Data collected may include:

- Ad impressions  
- Click events  
- High-level device metadata  

- **Linked to identity:** No  
- **Used for tracking:** No  
- **Shared:** With Google AdMob  
- **Purpose:** Serving non-personalized advertisements  

iOS does not present the App Tracking Transparency (ATT) prompt because IDFA is not accessed.

---

## 2. Data We Do Not Collect
Nutrition Mate does **not** collect or store:

- Names, email addresses, phone numbers, or contact information  
- Location data (precise or coarse)  
- HealthKit, fitness, or medical data  
- Financial information  
- Photos, videos, or audio  
- Contacts or address book  
- Browser or search history  
- Exact or identifiable nutrition logs  
- Any personally identifiable information  

---

## 3. How We Use Information
Data collected is used for:

- Core app functionality  
- Aggregated analytics and performance measurement  
- Crash diagnostics  
- Non-personalized ad serving  
- Consent storage and internal preference management  

We do **not** sell or trade any data.

---

## 4. Third-Party Service Providers

### **Firebase Analytics**
Processes aggregated usage data to understand feature performance and engagement trends.

### **Firebase Crashlytics**
Processes anonymized crash reports and diagnostics.

### **Firebase Anonymous Auth**
Enables secure, anonymous storage of consent records and internal preferences.

### **Google AdMob**
Serves contextual advertisements. Operates in non-personalized mode and does not use IDFA or perform tracking.

No other third-party SDKs collect data from the App.

---

## 5. Data Retention
- On-device nutrition data remains until you delete the App or reset data.  
- Crash logs are retained by Firebase Crashlytics for up to 90 days.  
- Aggregated analytics data is retained according to Google Analytics retention policies.  
- Ad impression data is retained per Google's advertising retention policies.  
- Anonymous Auth identifiers persist until the App is uninstalled or data is reset.

---

## 6. Children's Privacy
Nutrition Mate is not directed to children under 13.  
We do not knowingly collect personal information from children. If you believe a child has provided data, please contact us.

---

## 7. Security
We implement industry-standard safeguards including:

- Secure on-device key-value storage for all nutrition and meal data  
- Encrypted communication with Firebase (HTTPS/TLS)  
- No transmission of nutrition or health-related data to servers  
- Minimal data collection principles  

---

## 8. Your Rights
You may:

- Disable analytics within the App  
- Delete the App to remove all locally stored data  
- Contact us regarding privacy questions  

Because Firebase anonymous identifiers cannot be linked to an individual without external data (which we do not collect), deletion requests regarding persistent identifiers may not be actionable.

---

## 9. Changes to This Policy
This Privacy Policy may be updated periodically. Updates will be posted to this publicly accessible page.

---

## 10. Contact Information
For privacy-related inquiries, please contact:

**CG Software Solutions LLC**  
**Email:** cgsoftwaresolutionsllc@gmail.com

---

© 2025 CG Software Solutions LLC. All rights reserved.
