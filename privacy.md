---
title: Privacy Policy
permalink: /privacy/
---

# Standing Date Privacy Policy

**Effective date:** October 15, 2026

Standing Date is a small app that helps couples save date ideas, get
suggestions, and plan dates together. It's run by an individual developer
as a hobby project ("we", "us"). This policy explains, in plain language,
what we collect, why, who helps us run the app, and how to delete your data.

**The short version:** we collect what the app needs to work for you and
your partner. We don't show ads, we don't sell your data, and we don't
share it with anyone except the few services that run the app for us. You
can delete your account in the app at any time.

## 1. What we collect

**Account details.** Your email address, the name you choose to show your
partner, and your password. We store only a scrambled (hashed) version of
your password, never the password itself.

**Your home city.** You type in a city during setup. We look it up in a
list of cities built into our server (no outside service is involved) to
get its approximate map coordinates, so we can suggest things near you.

**Your current location (only if you ask).** When you ask for a suggestion
"near me now", or open the Trending list, the app can use your phone's
location for that one request, with your permission. We use it to pick a
nearby idea or the nearest city's Trending list, and we don't store it or
write it to our logs.

**Your tastes.** Your answers to the setup quiz, and how you respond to
suggestions (for example, which kinds of dates and price ranges you accept
or skip). We use this to make better suggestions.

**Your partner link.** When you invite your partner or accept their invite,
we link your two accounts so you share one Date Vault.

**Date ideas and links you add.** Ideas you add by hand, and links you share
into the app from other apps (like Instagram, Google Maps or your browser).
When you share a link, our server visits that public web page to pick up its
title, description, place name, location and the link to its main photo,
and saves them as a date idea.

**Photos on date ideas.** An idea's photo is a link to an image on the
website it came from. We store only the link, never a copy of the image.
To show it, your phone loads the image straight from that website, so that
website sees an ordinary request from your phone (like any web page would).

**Suggestions, plans and reviews.** The suggestions we send you, whether you
accept them, when a date is planned, and the reviews and notes you leave
afterward. Recurring suggestion schedules you set up are stored too.

**Calendar (only with your permission).** When you accept a date, the app
adds an event to your phone's calendar. That happens on your phone; we keep
only the event's ID and date so we can ask later how the date went. We don't
read the rest of your calendar.

**Push notification token.** An ID from your phone that lets us send you
notifications (new suggestions, review reminders). You can turn
notifications off in your phone's settings.

**Google Maps saved places (only if you choose to import them).** You can
import places you've saved in Google Maps from a file you download from
Google Takeout. The app reads that file **on your phone**; the file itself
never leaves your phone. We receive only your saved places: each place's
name, address, location, link and the list it's in, plus any note you wrote
on it. Notes are saved only if you choose to keep them. To suggest a
category and city for each place, we may send its name, address and list
name to our AI provider (see section 3), never your notes.

**Trending list.** For a few cities, we use AI with web search once a week
to find events and newly opened places. These searches are about the city,
not about you: only the city's name and the date are sent. When you save or
hide a Trending item, we record that for your couple.

**Technical logs.** Our servers keep short-lived logs (for example, errors)
to keep the app running. These may include your account ID but are deleted
automatically within about 30 days.

We don't collect your contacts, photos, messages, payment details, or
advertising IDs.

## 2. What your partner can see

Standing Date links two accounts into a couple. Your shared Date Vault,
suggestions made for both of you, planned dates and reviews are visible to
both of you. A suggestion schedule is visible to your partner unless you
mark it private. Your password, home city coordinates and taste answers are
not shown to your partner, though suggestions "for both of you" are based on
both partners' tastes combined.

## 3. Services that help run the app

We share data only with these service providers, only what each needs, and
they may not use it for their own purposes:

| Provider | What it does for us | What it receives |
|---|---|---|
| **Supabase** | Hosts our database | Everything described in section 1 (stored in the United States, Northern Virginia) |
| **Google Cloud** | Runs our servers | Data passing through our app, and the technical logs above (United States) |
| **Upstash** | Short-term counters and cache that keep the app fast and protect it from abuse | Rate-limit counters keyed by your IP address, sign-in email address or account ID (kept from 15 minutes to a day), and a pending schedule change for up to an hour |
| **Expo** (push notifications) | Delivers notifications to your phone, via Apple and Google | Your push token and the notification text (for example, the name of a suggested place) |
| **Anthropic** (Claude AI) | (1) Suggests a category (and, for imports, a city) for a link you share or places you import. (2) Searches the web each week for events and new places in our Trending cities | (1) The shared page's title, or each imported place's name, address and list name; never your notes. (2) Only a city name and the date. Never your name, email, location or account ID. Anthropic doesn't use this data to train its models |

When you share a link, our server fetches that web page directly from the
website that hosts it. That website sees a request from our server, not from
you.

## 4. What we don't do

- We don't sell your personal information.
- We don't show ads or share data with advertisers or data brokers.
- We don't track you across other apps or websites.

## 5. How long we keep data

We keep your data while your account is open. Some things are deleted
sooner on their own:

- Server logs: deleted within about 30 days.
- Rate-limit counters: deleted within a day.
- Trending events and places (public information, not about you): deleted
  about 30 to 60 days after they end or stop being found.

When you delete your account, your data is deleted right away (see below).

## 6. Deleting your account

**In the app:** open the Date Vault tab, tap the person icon at the top,
then **Delete account**, and type DELETE to confirm.

**Without the app:** email **[standingdateapp@gmail.com](mailto:standingdateapp@gmail.com)** from the address you signed
up with and ask us to delete your account. We'll confirm and delete it
within 30 days. See [How to delete your account](../delete-account/).

**What gets deleted:** your account (email, name, password), home city,
taste answers and history, suggestion schedules, reviews, calendar event
records, push token, invites, and suggestions that were only for you. If
you're not linked, your couple's saved or hidden Trending items go too. The
app also clears everything it stored on your phone.

**What your partner keeps:** if you're linked, your partner keeps their own
account, your shared Date Vault ideas (including ones you added, no longer
labeled with your name), their saved or hidden Trending items, and
suggestions that were made for them. Your link is removed. If you're not
linked, your Date Vault is deleted too.

**What stays on your phone:** calendar events the app created stay in your
calendar. Delete them in your calendar app if you don't want them.

Our database host may keep backup copies for disaster recovery for a short
period; we don't keep any other backups, and those copies are deleted on
the host's schedule.

## 7. Your choices

- **Change your details:** you set your name and home city during setup.
  To change them, email us (editing them in the app is planned).
- **Notifications:** turn them off in your phone's settings.
- **Calendar and location:** you can deny or withdraw these permissions in
  your phone's settings; the rest of the app still works.
- **A copy of your data, or questions:** email **[standingdateapp@gmail.com](mailto:standingdateapp@gmail.com)**.

## 8. Children

Standing Date is for adults. It's not meant for anyone under 18, and we
don't knowingly collect data from children. If you believe a child has
created an account, email us and we'll delete it.

## 9. Security

Connections to our servers are encrypted (HTTPS). Passwords are hashed.
Your sign-in tokens are stored in your phone's secure storage. Only you and
your linked partner can see your couple's data in the app.

## 10. Changes to this policy

If we make an important change, we'll tell you in the app before it takes
effect and update the date at the top.

## 11. Credits

City data © [GeoNames](https://www.geonames.org/), used under the
[Creative Commons Attribution 4.0 License](https://creativecommons.org/licenses/by/4.0/).

## 12. Contact

Questions or requests: **[standingdateapp@gmail.com](mailto:standingdateapp@gmail.com)**
