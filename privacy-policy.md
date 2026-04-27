# Privacy Policy

**Effective date:** April 23, 2026
**Last updated:** April 23, 2026

## Who we are

Litly is a free trivia application operated by **Lazar Nikolić**, an individual based in Serbia.

Contact for privacy questions: **lazar.nikolic@litcoding.net**

## Plain-English summary

- We don't ask for your name, email, phone number, or location.
- We store a random anonymous identifier ("device id") on your device so the app can keep your progress straight.
- When you submit a question report or feedback, we send the text plus that anonymous id to our database.
- We don't sell or share your data for advertising. We don't run ads.
- You can wipe everything by tapping **Reset history** in Settings or by uninstalling the app.

The detailed sections below explain exactly what's stored and where.

## What data we collect

### Stored only on your device (in app storage)

The app keeps the following on your device, so it can work offline and remember your preferences:

- **Anonymous device id** — a random string generated the first time you open the app (e.g. `anon-k7m2p9q1r5s3`). It is not linked to your phone, email, or any account.
- **Language preference** — `en` or `sr`.
- **Theme preference** — auto / light / dark.
- **Haptics on/off**.
- **Allow repeats on/off**.
- **List of question ids you've seen** — so the same question doesn't repeat in infinite mode.
- **List of question ids you've answered, and which you've ever answered correctly** — used to show your lifetime stats.
- **Excluded categories** — categories you've turned off in Settings.
- **Pending reports / feedback** — reports or feedback you submitted while offline, queued until they can be sent to our server.

This data lives only on your device. It is removed when you uninstall the app or tap **Reset history** in Settings.

### Sent to our server (Supabase, EU region)

We use Supabase, a PostgreSQL-based backend hosted in **Frankfurt, Germany**, to store:

- **Questions and translations** — the trivia content the app fetches (read-only for you).
- **Question reports** — when you tap "Report this question", we send: the question id, language, reason, your optional comment, your anonymous device id, timestamp.
- **General feedback** — when you submit feedback through Settings, we send: the text you wrote, your current language, your anonymous device id, timestamp.
- **Match data** (when this feature is enabled in a future version) — match configuration, anonymous participant ids, scores, timestamps.

We do not collect IP addresses on top of what Supabase logs at the infrastructure level, and we don't query those logs.

### Third-party services

When you actively use certain features, you interact with these third parties directly:

| Service | When | What they see |
|---|---|---|
| **Ko-fi** | When you tap "Donate" — it opens their site | Your IP and browser, per Ko-fi's own policy |
| **PayPal** | If you choose PayPal at Ko-fi checkout | Their standard payment data; governed by PayPal |
| **flagcdn.com** | When you open the language picker — it loads flag images | Your IP and User-Agent at the time of the request |

We don't pass any data to these services on your behalf — they only see what your device sends them when you trigger those actions or screens.

## Why we collect it

- **Device id, preferences, seen lists** — to make the app work (avoid repeating questions, remember your settings).
- **Question reports** — to let you flag bad content so we can fix it.
- **General feedback** — so you can tell us what you'd like to see improved.

We don't profile you, don't run ads, don't sell or trade data.

## How long we keep it

- **On your device** — until you uninstall or reset.
- **On our server** — indefinitely, but your data is anonymous (only the random device id ties it back to you). You can request deletion (see below).

## Your rights (GDPR)

Even though our data is anonymous, you have the following rights:

- **Right to access** — request a copy of any data tied to your device id.
- **Right to deletion** — request that we delete all data tied to your device id.
- **Right to correction** — request that we correct inaccurate data.

To exercise these, email **lazar.nikolic@litcoding.net** and include your **device id**. You can find your device id in Settings → About in a future version of the app; for now, you can email us with the rough date you started using the app and we'll do our best to identify your records.

## Children

Litly is not directed at children under 13. We do not knowingly collect any data from children. If you believe a child has used the app, contact us and we'll remove any associated records.

## International transfers

Our backend (Supabase) is in the EU (Frankfurt). If you use the app from outside the EU, your data is transferred to and stored in the EU. EU users' data stays in the EU.

## Changes to this policy

We'll update this page when our practices change. The "Last updated" date at the top reflects the most recent change. For material changes, we'll highlight them at the top of the page for at least 30 days.

## Contact

Lazar Nikolić
Email: **lazar.nikolic@litcoding.net**
Country: Serbia
