# lift — Privacy & Video Policy (beta)

_Last updated: 2026-10-10. This policy covers the TestFlight beta; it will be revised before App Store release._

## The short version

- Your videos live on **your phone**. Recording happens in the app,
  files stay in the app's storage, and the only way a video is ever
  deleted is **you deleting it**.
- When you submit a set for grading, the video is uploaded to our
  grading server, measured, and the **results are sent back to your
  phone**. In normal operation the server **deletes the video as soon
  as grading finishes** — graded results live on your phone, not on
  our servers.
- **No accounts.** The app has no sign-up, no profile, and no
  advertising or analytics SDKs. Your calibration data (your personal
  range-of-motion standard) is stored only on your phone and is sent
  with a submission solely to grade that submission.
- We never sell, share, or show your videos or results to anyone.

## What the app collects

| Data | Where it lives | Where it goes |
|---|---|---|
| Set videos you record | Your phone (until you delete them) | Uploaded once per submission for grading; deleted server-side after grading (see beta exception below) |
| Graded results (rep metrics, statuses) | Your phone | Nowhere else |
| Your calibration standard | Your phone | Attached to submissions to grade them; never stored server-side |
| Anonymous install id + usage events | A random ID generated on your phone (no account, no personal data) | Sent to our server with submissions and at app milestones (see below) |
| Accounts, contacts, location, audio | Not collected. Recording is video-only — the app never requests microphone access. | — |

## Anonymous usage events

So we can tell whether the app actually works for people (do testers
finish calibration? do they come back?), the app sends our own server
a short named event at a few milestones: app opened, calibration
completed, set recorded, set submitted, result viewed, feedback sent.
Each event carries only a **random install ID generated on your
phone** and a timestamp — no name, no email, no device fingerprint,
no location, nothing typed by you. The ID is not linked to any
account (there are no accounts) and resets if you delete the app.
**No third-party analytics or advertising service is involved** — the
events go only to the same grading server, into a log only the
developer reads.

## Beta exception: helping validate the instrument

During the TestFlight beta, and only with your consent as a tester,
videos you submit may be **retained and reviewed by the developer**
to validate and improve the measurement system — for example,
checking that the instrument correctly counts and measures reps on
bodies and filming setups other than the developer's own. This is
the entire purpose of the beta.

- Retained footage is used only for measurement validation, is never
  published or shared, and is deleted when validation of the relevant
  exercise is complete or on your request — whichever comes first.
- You can withdraw consent at any time; submissions after withdrawal
  return to the default grade-then-delete behavior.
- **During the invite-only phase, this consent is a condition of the
  invite**: by accepting the TestFlight invite you consent to the
  retention described above. If you don't want that, don't join the
  beta (or tell the developer — withdrawal always works). A per-user
  in-app consent control replaces invite-level consent before the
  beta ever opens beyond personal invites.

## Your controls

- **Delete a set**: removes the video from your phone permanently.
- **Delete the app**: removes all videos, results, and calibration
  data on the phone. (Server-side, there is nothing to delete outside
  the beta-retention exception above, which you can also ask us to
  clear at any time.)

## Contact

Beta privacy questions or deletion requests: the developer,
via your TestFlight invite contact.
