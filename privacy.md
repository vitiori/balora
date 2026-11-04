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

- Transactions (expenses and income), account balances, categories, budgets, recurring transactions, tags (trips and
  projects) and settings.
- **Recently deleted:** what you delete from Transactions is kept for 30 days so you can restore it; after that it is
  removed automatically, or sooner if you delete it from there (with the exception explained in section 12).
- **Profiles:** if you have several (for example, a personal one and a work one), each keeps its own data and settings
  separately, also on the phone.
- **Bank statement import:** the file you choose (CSV, Excel, Norma 43, OFX, QIF or CAMT) is read on your phone and
  is not kept. Balora keeps the transactions
  you import, the account number (IBAN) and the original description of each imported transaction, so the same
  transaction is not imported twice, and the import templates you save.
- **Automatic internal backup:** every day, after your changes (at most once an hour) and when you leave the app if you changed something, Balora keeps a copy of each
  profile's data in its private storage, so it can be recovered if the database gets damaged. It only leaves the phone
  with Android's backup (section 3).
- **"Your year" image:** when you share your year in review, Balora creates an image with no amounts in its temporary
  storage; it replaces it the next time you share, and Android may delete it when it needs space.

The developer has no access to any of this. Uninstalling the app or clearing its data deletes it from the phone (except
the backups you have exported yourself).

## 3. What leaves your phone, and only when you decide

| When | What | Who receives it |
|---|---|---|
| You **export a backup** | All your Balora data, from all your profiles, in a file encrypted with your password or as CSV files (your choice) | Only the place you choose (your phone's storage, a USB drive, a cloud service you use…) |
| You use the **Google account backup** (Balora Plus, off until you turn it on) | The automatic backup of each profile and the list of your profiles, through Android's backup service | Your Google account. It is only sent on Android 9 or later with a screen lock set, end-to-end encrypted with it, so neither Google nor the developer can read it; on Android 8 it is not sent. If you turn it off or your subscription ends, Balora stops sending new backups (by the next day at the latest), and Google keeps the last one under its backup service. Google handles it under the [Google Privacy Policy](https://policies.google.com/privacy) |
| You **move to a new phone** with Android's data transfer | The automatic backup of each profile and the list of your profiles, copied directly from the old phone | Only your new phone |
| You **save the annual report as a PDF** (Balora Plus) | The figures of the year you choose: income, expenses, balance and spending by category and month. It is created on the phone | Only the place you choose with Android's file picker |
| You **share "Your year"** | An image with your achievements of the year (days with entries, streaks, best month, top category, mascot level), with no amounts | The app or person you choose in Android's share menu |
| You **email us** (also with "Send a suggestion", which only opens your email app with our address and a subject) | What you write and your email address. Balora adds no text or data to the email | The developer, by email from your own email app |

"Recommend the app" opens Android's share menu with a message and the link to the Google Play listing. The link only
says that the install comes from a recommendation (Google Play Console counts how many) and carries no data about you
or your phone; you send it yourself to whoever you choose.

## 4. Purchases: Balora Plus and support

Subscriptions and support payments are processed by **Google Play**. The developer does not receive your card or
payment details. Google provides the developer with order information (order number, product, price, country or region,
date and status), which is used only to manage the purchase and to meet accounting and tax obligations. Google processes
your payment under its own terms and privacy policy. To know whether you have Balora Plus, Balora asks the Google Play app on
your phone when it opens and once a day in the background; this check sends no Balora data.

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

- **Notifications:** for the monthly balance reminder, recurring transactions to confirm, budget alerts, the notice
  that your monthly or yearly summary is ready and, only in the 14 days after installing the app, at most three
  reminders to get started. None of them show amounts. You can turn them off at any time, all or each type, in your
  Android settings.
- **Biometrics:** only for the optional app lock.
- **Google Play purchases:** for Balora Plus and support payments.
- **Technical permissions** added by Android's libraries: view network state (requested by the scheduled-tasks library;
  Balora does not connect to the internet), start when the phone is switched on (to reschedule reminders), keep the
  phone awake for a moment while a task finishes and, if a long task ever needed it, carry on with it in the foreground.

Balora does **not** request internet access, location, contacts, camera, microphone or the advertising ID.

## 9. No ads, no analytics, no sale of data

Balora contains no advertising, analytics or tracking tools, does not send your data to artificial intelligence services,
and the developer does not sell, rent or share any personal data.

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
(section 12 explains how).

## 12. How to delete your data

Balora has no user accounts or servers: there is no account to delete and the developer does not keep your transactions
or balances, so you delete them yourself, without asking anyone and for free.

- **A transaction:** in Transactions, swipe it to the left. It moves to Recently deleted (the 🗑 button on that screen),
  where you can restore it or delete it permanently, one by one or with "Delete all".
- **A balance:** delete it from Net worth.
- **What was already in a backup:** if a deleted transaction or balance was already in an exported backup or came from
  another phone, it no longer shows, but the app keeps its data with a deletion mark, also in the backups you export
  later, so that importing the earlier backup does not bring it back. To remove that mark too, delete the profile's data.
- **All the data in a profile:** *Settings › Profile › Delete this profile's data*. This deletes transactions, balances,
  recurring items, budgets, tags, bank imports and its automatic backup. Categories and settings (including import
  templates) stay. If it is not the main profile, *Delete this profile* removes it entirely.
- **Everything on the phone:** uninstall the app or clear its data in your Android settings. All profiles are deleted.
- **Exported backups, PDF reports and shared images:** Balora cannot reach them. Delete them wherever you saved or sent
  them. If you import an earlier backup, its data comes back.
- **Backup in your Google account:** when you turn it off, Balora stops sending new backups, but the last one stays with
  Google. After you delete a profile's data, the next backup Android makes no longer includes it. If you reinstall the
  app and it offers to recover a backup, choose "No, delete it". To delete the backup Google holds, go to the
  [Android dashboard of your Google account](https://myaccount.google.com/dashboard/android). Google manages it: that
  option may delete the backup of the whole device, not just Balora's, so read what it says carefully before confirming.
- **Your emails with the developer:** ask for them to be deleted by writing to
  [{{ site.email }}](mailto:{{ site.email }}).
- **Purchase information:** order information is kept for the period required by accounting and tax law (section 10), so
  it cannot be deleted sooner. Your payment details are managed by Google in your Google account.

## 13. Security

Encrypted backups use AES-256-GCM with a key derived from your password (PBKDF2, 600,000 iterations). If you forget the
password, the backup cannot be recovered by anyone. The app can be protected with your phone's screen lock.

## 14. Children

Balora is intended for adults and is not directed at children.

## 15. Changes to this policy

If this policy changes, the new version will be published on this page with its date. Significant changes will also be
announced in the app.

## 16. Contact

[{{ site.email }}](mailto:{{ site.email }})
