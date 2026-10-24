# Privacy policy — DPA (Daqui Para Ali)

**Last updated:** 24 October 2026  
**App:** DPA — Daqui Para Ali (`com.daquiparaali.app`)  
**Contact:** ldumany@gmail.com

This policy explains what data DPA uses, why, and how you can control it. DPA is a free app for planning *chapa* (minibus) trips in Maputo. **There is no account** — your trips stay on this phone.

---

## 1. Summary

| What | Where | Sent off the device? |
|------|--------|----------------------|
| Location (foreground) | Phone; sent only if you use **Perto** (Nearby) | Yes — to our server, to list nearby stops |
| Search / origin & destination text | Phone and server | Yes — to plan routes and look up places |
| Saved trips & local history | On the phone only | No |
| Crash reports (optional) | Firebase Crashlytics | Yes — technical crash data, if enabled in Profile |
| Problem reports (if you send one) | Our server | Yes — the text you write |

We do not sell data. We do not show ads. We do not use an advertising ID.

---

## 2. Location

DPA asks for location **only in the foreground** (while you use the app). We do not request background location.

- **Perto (Nearby):** with your permission, we send your current latitude and longitude to our server (`dpa-backend.fly.dev`) to list nearby stops and lines. Without permission, trip planning still works with place names.
- **On a trip:** the map position is **your phone’s**, not the vehicle’s; it is used on screen and is not continuous “tracking” uploads.
- On the server, coordinates in logs and related fields are reduced/redacted where applicable. Route-request logs are **deleted automatically after about 30 days** (default setting).

---

## 3. Search and trip planning

When you type a place or request a route, that text (origin/destination or search) is sent over HTTPS to our server. We may store that text in technical route-request logs, also subject to about **30 days** retention.

---

## 4. Data that stays on the phone

These stay on the device (and can be cleared in Android settings or in the app, where the screen allows):

- Saved trips  
- Active journey and recent completed-trip history  
- Preferences and any offline map you download  
- Local cache of results you have already seen (sometimes including coordinates used for Perto, for limited offline use)

Android backup / device transfer, when enabled and encrypted by the system, may include **only** saved trips — not full history or location.

---

## 5. Crash reports (Crashlytics)

If you leave error reporting on in **Profile**, we use Firebase Crashlytics to receive technical data about crashes, app version, Android version, device model and installation identifiers, so we can fix problems. We **do not** attach your searches, location or trip contents. You can turn this off in Profile.

Turning it off requests deletion of pending reports on the device; it does not delete reports already uploaded. Debug builds do not send these reports.

---

## 6. Problem reports and sharing

If you **Report** a problem, the text and context you choose to send go to our server so we can improve the service.  
If you **share** a trip with Android’s share sheet, you start that share; the destination app (WhatsApp, etc.) is under that app’s rules.

---

## 7. Payments (M-Pesa)

When fare payments go live, phone number and payment details required by the payment provider (for example M-Pesa / a gateway) will be handled under that provider’s terms, and this policy will be updated. Until then, the app may include test/simulated payment flows that do not charge.

---

## 8. Maps and hosting

- The map uses third-party services (for example OpenFreeMap) for styles and tiles; those requests reveal your IP and the map area you view.  
- The app server is hosted on **Fly.io** (service provider). Traffic uses **HTTPS**.

---

## 9. How to delete or limit data

1. Deny or revoke location permission in Android settings.  
2. Turn off crash reporting in Profile.  
3. Remove saved trips in the app; delete the offline map.  
4. Android Settings → Apps → DPA → Clear storage / uninstall.  
5. For questions about server-side data with no account linked to you, email **ldumany@gmail.com** (include approximate dates and what you want).

---

## 10. Children

DPA is not directed at children under 13 and does not collect data in order to identify them.

---

## 11. Changes

We may update this policy. The date at the top will change. Material changes will be reflected on the Play Store listing and on this page.

---

## 12. Contact

Dumany Lombe — Daqui Para Ali  
Email: **ldumany@gmail.com**
