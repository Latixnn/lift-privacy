# Caliper

## Privacy and video policy

Last updated: November 6, 2026.

Caliper is a training app that films your sets and measures your
reps. This page says exactly what data exists, where it lives, and
what ever leaves your phone. One clause applies only during the
TestFlight beta and is marked as such.

### The short version

- Your videos live on your phone. Recording happens in the app, the
  files stay in the app's storage, and the only way a video is ever
  deleted is you deleting it.
- A video leaves your phone only when you choose Analyze on that
  set. The server measures it, sends the results back to your phone,
  and deletes the video after analysis in almost every case. The
  narrow exception is described below.
- No accounts. There is no sign-up, no profile, and no advertising
  or analytics SDKs in the app.
- We never sell, share, or show your videos or results to anyone.

### What uploads and when

Nothing uploads on its own. Three actions send data, and each one is
yours:

1. **Analyze a set.** Uploads that set's video, the exercise name, a
   random install ID generated on your phone, any rep count you
   typed for that set, and, for exercises with a personal range,
   your range reference, which is used only to grade that submission
   and is never stored on the server. Weight and reps in reserve
   never leave the phone.
2. **Send feedback.** Sends your message, the topic you picked, the
   app version and the install ID. If you choose to attach one of
   your set videos, it is uploaded with the report and deleted
   within 90 days.
3. **Use the app.** At a few milestones (app opened, set recorded,
   set submitted, result viewed, feedback sent, the range-setup
   steps, the range-learning moments, and removing a flagged first
   or last rep) the app sends our server a short named event with
   the install ID and a timestamp. Events carry names and counts,
   never video and never your measured numbers. The one exception is
   the rep-removal event, which carries that one rep's measured
   number so we can check the remove button is only offered where it
   should be.

The install ID is random, is not linked to any account (there are
none), and resets if you delete the app. No third-party analytics or
advertising service is involved; everything above goes only to our
own analysis server, into logs only the developer reads.

### What is kept on the server, and for how long

Your uploaded video is deleted right after analysis in almost every
case. A video is kept only when it is evidence the measurement
needs: when the rep count you typed disagrees with the measured
count, or when the recording could not be measured at all (for
example, nobody was in frame). If you turned off video review in
Help & settings, nothing is ever kept, disagreement or not.

Every kept video is deleted at most 90 days after upload,
automatically.

The server also keeps one line per submission with counts, durations
and an error type (how many reps were detected, how long analysis
took, whether it failed and why). Never the video, never your
measured numbers.

### During the TestFlight beta only

This clause applies during the TestFlight beta and ends with it.
During the beta, and only with your consent as a tester, videos you
submit may be retained and reviewed by the developer to validate and
improve the measurement system. Retained footage is used only for
measurement validation, is never published or shared, and is deleted
when validation of the relevant exercise is complete, at the 90-day
bound above, or on your request, whichever comes first. You can
withdraw consent at any time with the Video review switch in Help &
settings.

### Delete my data

- **On your phone:** delete a video (the training record stays),
  delete a set and its results, or delete the app, which removes
  every video, result and range on the phone.
- **On the server:** in almost every case there is nothing to
  delete, because videos are removed after analysis. If a video of
  yours was kept under the rule above, open Help & settings and tap
  "Ask to delete reviewed videos", or contact us at the support
  address below. We honor deletion requests without questions, and
  every kept video is deleted automatically at most 90 days after
  upload in any case.

### Contact

Privacy questions or deletion requests: calipersupport@gmail.com.
The same address is listed in the app under Help & settings.

Need help with the app? See the [support page](https://latixnn.github.io/lift-privacy/support.html).
