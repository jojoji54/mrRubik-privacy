# GlucoPilot Privacy Policy

**Last updated: February 19, 2026**

This Privacy Policy explains how GlucoPilot handles personal data when you use the app.

## 1. Data Controller and Contact

- Controller: GlucoPilot developer (Mr Rubik Dev)
- Contact email: `mrrubikdev@gmail.com`
- Website: `https://mrrubik.dev`

## 2. Scope

This policy applies to GlucoPilot on supported platforms (including iOS, Android, macOS, and Windows), and to optional cloud services used by the app.

GlucoPilot is a self-management and insights app for diabetes-related tracking. It is **not** a medical diagnosis, treatment, or emergency service.

## 3. Data We Process

### 3.1 Data stored locally on your device

Depending on your use, GlucoPilot may store:

- Onboarding profile and preferences (for example diabetes type, goals, meal schedule, app settings).
- Health logs (for example glucose, meals, carbs, insulin, exercise, sleep, stress, heart rate, weight, lab values).
- Experiment history and progress.
- Integration state (for example sync timestamps and connector state).
- Optional in-app collaboration notes/comments entered by you.
- Optional GlucoGuide (copilot) conversation history.
- Optional local product telemetry events (feature usage events).

Core local app data is stored in an encrypted local database.

### 3.2 Data used for optional cloud features (Firebase)

If you enable cloud features and have required entitlement/subscription, GlucoPilot may send data to Firebase services, including:

- Daily summary payloads derived from your logs (including timestamps, entry type, values, source tags, and optional note fields).
- Push token registration data (device push token, platform, locale, UTC offset, timezone, quiet-hour preferences).
- Purchase entitlement verification metadata.
- Product telemetry **aggregates** (not full raw event history) only after explicit telemetry cloud consent.

Cloud features use authenticated requests with a Firebase user ID (anonymous authentication may be used).

### 3.3 Data used for optional AI drafting

GlucoPilot can generate deterministic local replies. If cloud drafting is available and enabled, the app may send limited drafting payloads to backend services, which may call OpenAI APIs. Payloads include:

- Your copilot prompt text.
- A deterministic draft based on your app insights.
- A limited set of grounded insight snippets/citations.

The app includes safety guardrails and does not provide medication or dosage instructions.

### 3.4 Purchases and subscriptions

In-app purchases are handled by Apple App Store and/or Google Play.
GlucoPilot and backend services may process:

- Product ID, platform, purchase ID (if available), transaction timestamp.
- Store verification payload/receipt data (or secure hash of verification data for idempotency and entitlement processing).

Billing, renewals, cancellations, and refunds are managed by the app store provider under its own terms.

## 4. Integrations and External Data Sources

Depending on enabled features, you may import or sync data from:

- Apple Health / Health Connect.
- CGM providers (for example Dexcom/Libre official APIs via OAuth).
- CSV/manual imports.
- Optional wearable provider OAuth/sync flows.
- Optional nutrition lookup provider (OpenFoodFacts).

Some integrations are optional and may be disabled in your current app build/configuration.

## 5. Permissions We Request

Permissions vary by platform and enabled features, for example:

- Health data read permissions.
- Notification permissions.
- Bluetooth permissions (for CGM BLE features).
- Activity recognition and related platform permissions.
- Biometric/local authentication for app lock.

You can deny permissions. Some app features may then be unavailable.

## 6. How We Use Data

We use data to:

- Provide logging, analysis, and insights.
- Sync data across optional cloud workflows.
- Send optional smart notifications.
- Enable premium features and verify entitlements.
- Improve product quality through optional telemetry.
- Protect service integrity and prevent abuse/fraud.

## 7. Legal Bases (where applicable)

Depending on your jurisdiction, we rely on:

- Performance of the service (to run requested app features).
- Consent (for permissions, optional cloud telemetry sync, and similar optional processing).
- Legitimate interests (security, abuse prevention, reliability).
- Legal obligations (where required).

## 8. Data Sharing and Recipients

We do not sell your personal data.

Data may be processed by:

- Google Firebase (Auth, Cloud Functions, Firestore, Cloud Messaging) for optional cloud features.
- OpenAI (for optional cloud copilot drafting when enabled).
- Apple and Google app stores (purchase handling and entitlement context).
- Connected third-party health providers you explicitly authorize (for example CGM/wearable providers).

GlucoPilot does not include third-party advertising SDKs.

## 9. International Transfers

Service providers may process data in countries outside your own jurisdiction.
When this happens, transfers are handled under the provider's legal transfer mechanisms and safeguards.

## 10. Retention

### 10.1 Local retention controls

GlucoPilot includes a Privacy Center with retention controls. You can set a retention window (or keep data indefinitely). Retention controls apply to local app datasets supported by the feature (for example logs/history/conversation records).

### 10.2 Export and deletion

- You can export a full local privacy snapshot from within the app.
- You can use "Delete all data" to remove local app data from the device.

Important: local delete/export actions do not automatically erase already stored third-party cloud records (for example Firebase backend records or store-side purchase records).

### 10.3 Cloud retention

Cloud records used for optional features are retained in backend systems until deleted according to service operation needs, entitlement workflows, or deletion requests.

## 11. Security

We implement reasonable technical and organizational safeguards, including encrypted local storage for core app data and encrypted transport for network communication.

No method of transmission or storage is 100% secure.

## 12. Children's Privacy

GlucoPilot is not directed to children under 13. If you believe a child provided personal data without proper authorization, contact us and we will review deletion steps.

## 13. Your Privacy Choices and Rights

Depending on your jurisdiction, you may have rights to access, correct, delete, restrict, object, or port personal data.

You can:

- Manage permissions at OS level.
- Use in-app privacy controls.
- Contact us for requests regarding cloud-stored data.

Contact: `mrrubikdev@gmail.com`

## 14. Changes to This Policy

We may update this Privacy Policy to reflect product, legal, or technical changes.
The current version is the latest version published at the official GlucoPilot privacy policy URL.

## 15. Third-Party Policies and Terms

- Google Privacy Policy: `https://policies.google.com/privacy`
- OpenAI Privacy Policy: `https://openai.com/policies/privacy-policy`
- Apple Standard EULA: `https://www.apple.com/legal/internet-services/itunes/dev/stdeula/`
- OpenFoodFacts Privacy Policy (if nutrition integration is enabled): `https://world.openfoodfacts.org/privacy`

