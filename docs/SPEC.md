# JobTrail: Spec

**Track every job application without a spreadsheet** · #31 of 33 · Wave 3: Seasonal and episodic · Used: Until hired · Easy · Revenue potential: Medium · Money & Work · Source: New (Claude)

## One-liner

Log job applications and their stage (applied, interview, offer, rejected), set follow-up reminders, keep interview notes and hit a weekly applications goal. Your whole pipeline at a glance.

## Problem / audience

- **Who it's for:** Graduates, career changers and anyone applying for lots of roles.
- **The problem it solves:** Applications get lost, follow-ups are forgotten, and it's hard to see progress.
- **Example:** A graduate applies to 12 roles a week, gets nudged to follow up after 7 days, and sees three move to interview.

## MVP features (ship with only these)

1. Applications with company, role, link, date and stage
2. Pipeline board
3. Follow-up and interview reminders
4. Notes per application (questions, contacts)
5. Weekly applications goal with a streak

## Not in MVP

- CV and cover-letter version tracking
- Export to CSV
- Interview question bank

## Monetisation

| Model | Detail |
|---|---|
| Free | Up to 15 active applications, with ads |
| Premium | £2.99/month: unlimited, CV versions, exports, insights |
| Ads | Light |

Prices are starting points; test before committing. **Portfolio premium promise:** free has ads; the moment you pay you get no ads, cloud backup and storage, and sync across your devices, plus this app's extras.

## Retention: The Progression Loop

| Stage | Design |
|---|---|
| Cue | Weekly goal and follow-up reminders |
| Tiny win | Log an application or move a stage |
| Progress | Pipeline and weekly goal |
| Share | 'Got the job!' card |
| Next step | After an offer: hand over to ShiftLedger or PocketLeft |
| Cadence | Several times a week during a search |

Follow the portfolio guardrails: no guilt-trip notifications, no fake urgency, progress is
never wiped, at most one notification a day by default.

## Animation and tone

**Calm.** Smooth, reassuring motion only: gentle ticks, numbers easing into place. No characters, jokes or drama.

- Cards move smoothly between stages; one celebration for an offer

**Line we don't cross:** Rejections are never animated.

## AI

**None.** Not needed. Plain code does everything this app does. (Portfolio rule: plain code first, code does the maths,
cheapest model, shared budget cap, premium-gated.)

## Platform & data

- **Platform:** Expo app.
- **Data:** On the device only.
- **Backend:** None for the free version: everything lives on the phone. Premium backup and sync use the shared portfolio backend (see the master repo's HOSTING.md).
- **Stack:** shared portfolio foundation (Expo, PostHog, RevenueCat, AdMob, shared Progression Loop module).

## Growth engine

- **Content pillars:** Job-hunt tips; Application tracking; Interview prep
- **Shareable output:** 'Got the job!' card

## Risks

Users leave once they're hired (that's success). Grow through graduate-season content.

## Launch checklist

- [ ] Name checked on the App Store, Play Store and a trademark search
- [ ] MVP features done and tested
- [ ] Progression Loop wired (cue, tiny win, progress, milestone, next step)
- [ ] Privacy policy and terms
- [ ] Landing page
- [ ] Analytics wired (D1/D7/D30 retention)
- [ ] Payments / ads wired
- [ ] Added to growth-engine as an app config
