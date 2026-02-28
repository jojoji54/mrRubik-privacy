# Trazzio Terms of Use and Privacy Policy

**Last updated: February 28, 2026**

This document describes the terms of use and privacy policy for the **Trazzio** app.

## 1. Data Controller
**Data Controller:** Juan Ormaechea (Mr Rubik)  
**Privacy contact:** donrubikdev@gmail.com  
**Website:** https://www.mrrubik.com

## 2. What Trazzio Is
Trazzio is a social party game for mobile and desktop platforms.  
It supports local matches (offline, single device) and online matches (Firebase rooms with anonymous users).

## 3. Age and Acceptable Use
Trazzio is intended for a general audience (including teens).  
If you are under legal age in your region, use the app under parent/guardian supervision.  
Users agree not to tamper with, reverse engineer, abuse, or disrupt the app or backend services.

## 4. In-App Purchases (Planned)
Trazzio may include a one-time in-app purchase to remove ads in the future.  
Pricing, taxes, billing, refunds, and restoration are managed by Apple App Store / Google Play under their own terms.

## 5. Advertising (Planned, Not Active Yet)
Trazzio may integrate Google AdMob (for example: banner, interstitial, rewarded, app open) in future versions.  
As of the last update date above, ads are not active in current builds unless explicitly released in a future app version.  
When ads are enabled, ad personalization and processing will depend on user consent and local law.

## 6. Data We Process
### 6.1 Data handled by Trazzio
- Anonymous Firebase UID (online mode only).
- Nickname chosen by the player.
- Room/game state required to run matches:
  - ready status, phase state, votes, round results, score.
  - drawing stroke data (vector points, not photos or gallery media).
- Basic anti-abuse and reliability metadata (rate-limit and moderation events).

### 6.2 Data handled locally on device
- Local game settings and preferences.
- Temporary local match state in pass-and-play mode.

### 6.3 Data handled by third parties
When using Firebase, app stores, and (in future) AdMob, those providers may process technical data such as:
- Device/app identifiers.
- Approximate IP and network metadata.
- Diagnostics, crash, and service performance information.
- Purchase events handled by Apple/Google (if purchases are enabled).

Trazzio does not require account registration and does not request email/password to play.

## 7. What We Do Not Intentionally Collect
- Government ID numbers.
- Postal address.
- Phone contacts.
- Precise location.
- Payment card details (processed by platform stores, not by Trazzio directly).

## 8. Purposes and Legal Basis
Data is processed to:
- Provide local and online gameplay.
- Sync online room state securely.
- Prevent cheating, spam, fraud, and abuse.
- Moderate rooms (host actions such as kick/close).
- Comply with legal obligations.
- (Future) display/manage ads and ad-removal purchases.

Legal basis may include service performance, legal compliance, legitimate interest (security/abuse prevention), and consent where required.

## 9. Consent and Privacy Options
If ads are enabled in future versions, Trazzio may integrate consent management (for example, Google UMP) and provide privacy options where required by law.

## 10. Retention
- Online room data is retained only as needed for active gameplay and cleanup processes.
- Closed or expired rooms are marked and cleaned by backend retention mechanisms.
- Local data remains on device until app data is cleared, settings are reset, or the app is uninstalled.
- Third-party providers retain their own logs per their policies.

## 11. Recipients and International Transfers
Data may be processed by:
- Google Firebase (Auth, Firestore, Cloud Functions).
- Apple / Google as app distribution and payment platforms.
- (Future) Google AdMob if ads are activated.

These providers may process data outside your country/region under their own legal safeguards.

## 12. User Rights
Subject to local law, you may request access, rectification, deletion, restriction, objection, or portability by contacting:  
**donrubikdev@gmail.com**

You may also contact your local data protection authority.

## 13. Security
Trazzio applies reasonable technical and organizational protections, including:
- TLS in transit.
- Server-side control for critical game actions.
- Security rules and validations for online writes.
- Signed invitations and anti-abuse/rate-limit mechanisms.

No system can guarantee absolute security.

## 14. Intellectual Property
The app, branding, code, design, and content are owned by the rights holder or licensors.  
Unauthorized copying, redistribution, or commercial exploitation is prohibited.

## 15. Policy Updates
This document may be updated for legal, operational, or technical reasons.  
The latest published version is the one that applies.

## 16. Governing Law
Unless mandatory local law provides otherwise, these terms are governed by Spanish law and subject to the courts of Zaragoza, Spain.

## 17. Third-Party Links
- Google Privacy Policy: https://policies.google.com/privacy
- How Google uses data for ads: https://policies.google.com/technologies/ads
- Apple Standard EULA: https://www.apple.com/legal/internet-services/itunes/dev/stdeula/
- Firebase Privacy and Security: https://firebase.google.com/support/privacy

---

## Store Note (Recommended)
Host this policy at a public and stable URL (website or GitHub Pages) labeled clearly as **Privacy Policy**, and keep this document synchronized with production behavior.
