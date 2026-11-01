# Namma Auto TN

Mobile-first passenger/driver/admin UI preview for Tamil Nadu.

## Included
- Passenger, Driver and Admin workspace selection
- Firebase Google sign-in and Phone OTP UI
- User profile with Sign Out
- OpenStreetMap + Leaflet map and browser GPS capture
- Driver GPS write attempt to Firestore

## Important setup
1. In Firebase Authentication, enable Google and Phone providers.
2. Add your Vercel preview domain to Firebase Authentication > Settings > Authorized domains.
3. Configure Firestore rules from `firestore.rules` only after reviewing your authorization model.
4. Admin access is intentionally not granted by the client-side role selector.
5. Nearby driver discovery, ride dispatch, live multi-user tracking, driver document uploads, admin approval, and payment reconciliation are not yet production-ready.

This preview does not charge a platform commission. No official fare values are hardcoded.
