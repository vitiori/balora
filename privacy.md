---
layout: default
lang: en
title: Privacy policy
description: Balora privacy policy. Your financial data stays on your phone.
permalink: /privacy/
home: /
alternates:
  en: /privacy/
  es: /es/privacidad/
  fr: /fr/confidentialite/
---

# Privacy policy

<p class="updated">Last updated: {{ site.updated.en }}</p>

<div class="summary" markdown="1">

**In short:** your financial data stays on your phone. Balora has no internet permission, no user accounts, no ads, no
analytics and no tracking. The developer never receives your transactions, balances or amounts. Data only leaves your
phone when you decide to: when you export a backup, when you move your data to a new phone with Android, when you use
the Google account backup of Balora Plus, or when you send us an email.

</div>

## 1. Who is responsible

Balora is developed by **{{ site.owner }}** ({{ site.country.en }}), who is responsible for the processing described in
this policy. Contact: [{{ site.email }}](mailto:{{ site.email }}).

## 2. What Balora stores on your phone

Everything you enter is stored only in the app's private storage on your phone:

- Transactions (expenses and income), account balances, categories, budgets, recurring transactions and settings.
- **Profiles:** if you have several (for example, a personal one and a work one), each keeps its own data and settings
  separately, also on the phone.
- **Bank statement import:** the file you choose is read on your phone and is not kept. Balora keeps the transactions
  you import, the account number (IBAN) and the original description of each imported transaction, so the same
  transaction is not imported twice, and the import templates you save.
- **Automatic internal backup:** every day and after your changes (at most once an hour), Balora keeps a copy of each
  profile's data in its private storage, so it can be recovered if the database gets damaged. It only leaves the phone
  with Android's backup (section 3).

The developer has no access to any of this. Uninstalling the app or clearing its data deletes it from the phone (except
the backups you have exported yourself).

## 3. What leaves your phone, and only when you decide

| When | What | Who receives it |
|---|---|---|
| You **export a backup** | All your Balora data, from all your profiles, in a file encrypted with your password or as CSV files (your choice) | Only the place you choose (your phone's storage, a USB drive, a cloud service you use…) |
| You use the **Google account backup** (Balora Plus, off until you turn it on) | The automatic backup of each profile and the list of your profiles, through Android's backup service | Your Google account. It is only sent on Android 9 or later with a screen lock set, end-to-end encrypted with it, so neither Google nor the developer can read it; on Android 8 it is not sent. If you turn it off or your subscription ends, Balora stops sending new backups, and Google keeps the last one under its backup service. Google handles it under the [Google Privacy Policy](https://policies.google.com/privacy) |
| You **move to a new phone** with Android's data transfer | The automatic backup of each profile and the list of your profiles, copied directly from the old phone | Only your new phone |
| You **send a suggestion** | The text you write, your email address, and technical details shown before sending: app version, Android version, phone model and language. Never transactions, balances or amounts | The developer, by email from your own email app |

## 4. Purchases: Balora Plus and support

Subscriptions and support payments are processed by **Google Play**. The developer does not receive your card or
payment details. Google provides the developer with order information (order number, product, price, country or region,
date and status), which is used only to manage the purchase and to meet accounting and tax obligations. Google processes
your payment under its own terms and privacy policy.

## 5. Crash reports

If you have allowed it in your Android settings (*Usage & diagnostics*), Android may send Google reports about app
crashes and freezes, which the developer can see in aggregate in Google Play Console (Android vitals). Balora adds no
code of its own for this and the reports contain no financial data. You can turn it off in your Android settings.

## 6. Ratings

If Balora shows Google Play's rating window, it is displayed and processed by Google. Balora does not learn whether you
rated it or what you wrote.

## 7. App lock

If you turn on the app lock, Android checks your fingerprint, face, PIN, pattern or password. Balora only receives
whether the unlock succeeded: your biometric data never reaches the app.

## 8. Permissions

- **Notifications:** for the monthly balance reminder, recurring transactions to confirm and budget alerts. You can
  turn them off at any time.
- **Biometrics:** only for the optional app lock.
- **Google Play purchases:** for Balora Plus and support payments.
- **Technical permissions** added by Android's libraries: view network state (requested by the scheduled-tasks library;
  Balora does not connect to the internet), start when the phone is switched on (to reschedule reminders) and keep the
  phone awake for a moment while a task finishes.

Balora does **not** request internet access, location, contacts, camera, microphone or the advertising ID.

## 9. No ads, no analytics, no sale of data

Balora contains no advertising, analytics or tracking tools, and the developer does not sell, rent or share any personal
data.

## 10. Legal basis and retention

- **Suggestions and questions by email:** your consent when writing, and the legitimate interest in answering you. They
  are kept as long as needed to deal with them and for at most two years, unless you ask us to delete them sooner.
- **Purchase information:** performance of the contract and legal obligations; kept for the period required by
  accounting and tax law.

## 11. Your rights

Under the GDPR you can request access to, rectification or erasure of your personal data, restrict or object to its
processing, and request its portability, by writing to [{{ site.email }}](mailto:{{ site.email }}). You also have the
right to lodge a complaint with a data protection authority; in Spain, the
[Agencia Española de Protección de Datos](https://www.aepd.es).

Your financial data is only on your phone: you can export it, change it or delete it yourself in the app at any time
(to delete all of it: *Settings › Profile › Delete this profile's data*, free).

## 12. Security

Encrypted backups use AES-256-GCM with a key derived from your password (PBKDF2, 600,000 iterations). If you forget the
password, the backup cannot be recovered by anyone. The app can be protected with your phone's screen lock.

## 13. Children

Balora is intended for adults and is not directed at children.

## 14. Changes to this policy

If this policy changes, the new version will be published on this page with its date. Significant changes will also be
announced in the app.

## 15. Contact

[{{ site.email }}](mailto:{{ site.email }})
