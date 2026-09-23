# Privacy Policy

**Last Updated: September 23, 2026**

Welcome to CalMate ("we," "our," or "us"). This Privacy Policy explains how information is handled when you use the CalMate Android application and related services.

## 1. Information We Handle

### Account information
When you create an account, Firebase Authentication processes your account identifier and the email address and profile details you provide. CalMate also supports guest use.

### Nutrition and app data
Meal logs, food names, portions, nutrition information, goals, dietary preferences, saved recipes, meal plans, and weight logs may be stored in Cloud Firestore for signed-in users. App preferences may be stored on your device.

### Meal images and AI requests
When you choose an AI feature, the text and/or meal image you submit is sent to our Cloudflare Worker, which verifies your Firebase sign-in token and forwards the AI request to OpenRouter. The selected model is Meta's `meta/muse-spark-1.3-contributor`.

OpenRouter's listing for this Contributor model states that prompts and outputs may be used to improve Meta's products. Do not submit information you do not want processed by OpenRouter and Meta. See [OpenRouter's model listing](https://openrouter.ai/meta/muse-spark-1.3-contributor).

### Nutrition lookup
When you use a food or barcode lookup, the query may be sent to Open Food Facts to retrieve matching nutrition information.

### Subscriptions
Google Play and RevenueCat process subscription and transaction information needed to manage your purchase and entitlement. CalMate does not receive your payment card details.

## 2. How We Use Information

We use information to provide account access, store and display your nutrition data, process AI requests you initiate, perform nutrition lookups, manage subscriptions, maintain security, and respond to support requests.

## 3. Service Providers

We use the following services to operate CalMate:

- **Firebase Authentication and Cloud Firestore** for account authentication and signed-in user data storage.
- **Cloudflare** to host the AI proxy, validate Firebase ID tokens, and forward supported AI requests.
- **OpenRouter and Meta** to process AI prompts and meal images using the Muse Spark 1.3 Contributor model. As stated above, prompts and outputs may be used to improve Meta products.
- **Open Food Facts** for optional food and barcode nutrition lookups.
- **RevenueCat and Google Play** to coordinate and process Android subscriptions.

## 4. Retention, Deletion, and Subscriptions

Signed-in account data is retained while needed to provide the service. You can request deletion in the app under **Profile → Delete Account**. The deletion flow removes the Firebase account and associated CalMate Firestore records; email-and-password accounts must reauthenticate first. Local app preferences are cleared after successful deletion.

Deleting your CalMate account does not cancel an active Google Play subscription. Manage or cancel that subscription through Google Play.

## 5. Children's Privacy

CalMate is not intended for children under 13. We do not knowingly collect personal information from children under 13.

## 6. Changes to This Policy

We may update this policy when our practices or services change. The date above indicates when it was last updated.

## 7. Contact

For questions about this policy or your information, contact **wematelabs@gmail.com**.

© 2026 CalMate. All rights reserved.
