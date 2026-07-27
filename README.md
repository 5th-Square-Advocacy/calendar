# 5th Square Advocacy — events calendar feed

This repository exists to serve one file: a calendar feed of
[5th Square Advocacy](https://www.5thsqadvocacy.org) events.

## Subscribe

```
https://5th-square-advocacy.github.io/calendar/events.ics
```

- **Google Calendar** — Other calendars → **+** → *From URL* → paste
- **Apple Calendar** — File → *New Calendar Subscription* → paste
- **Outlook** — Add calendar → *Subscribe from web* → paste

Some clients want `webcal://` instead of `https://` — same address, different
scheme.

Calendar apps refresh subscriptions on their own schedule, and Google in
particular can take up to a day. A newly added event may not appear right away.

## About the file

`events.ics` is generated from our Neon CRM events. **Don't edit it by hand** —
changes are overwritten when it's regenerated. Event details are managed in Neon;
this is only a published copy.

Full event listings, including registration, are at
<https://www.5thsqadvocacy.org/events>.
