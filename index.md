# Caliper

## Privacy and video policy

Last updated: November 13, 2026.

Caliper is a training app that films your sets and measures your
reps. This page says exactly what data exists, where it lives, and
what ever leaves your phone.

### Who we are

Caliper is made and run by one person, not a company: Mateo Galarce,
Kensington, California, United States. That person is responsible for
the data described on this page and answers the contact address at
the bottom. We call that person "the developer" below.

### The short version

- Your videos live on your phone. Recording happens in the app, the
  files stay in the app's storage, and the only way a video is ever
  deleted is you deleting it.
- A video leaves your phone only when you choose Analyze on a set or
  run the range setup. The server measures it, sends the results back
  to your phone, and deletes the video after analysis in almost every
  case. The narrow exception is described below.
- No accounts. There is no sign-up, no profile, and no advertising
  or analytics SDKs in the app.
- We never sell your videos or results, and we never share or show
  them to anyone. The one party that holds them besides us is the
  company we rent the server from, described under "Where the server
  is". It hosts the files; it does not use them.

### Videos on your phone

Set videos are stored in the app's own Documents folder on your
phone. iPhone backups (iCloud or a computer) include that folder, so
if you back up your phone, your set videos are in the backup under
Apple's terms, and deleting a video in the app does not remove it
from a backup you already made.

### What uploads and when

Nothing uploads unless you start it. Four actions send data, and
each one is yours:

1. **Analyze a set.** Uploads that set's video, the exercise name, a
   random install ID generated on your phone, any rep count you
   typed for that set, and, for exercises with a personal range,
   your range, which is used only to grade that submission and is
   never stored on the server. Weight and reps in reserve never
   leave the phone.
2. **Set up your range.** For exercises with a personal range, the
   range setup uploads a short placement clip (so the server can
   check the camera angle) and the two assessment videos you record,
   each with the exercise name and the install ID, and each handled
   like an Analyze upload. When the assessment results land, the app
   automatically sends the measured value of each rep you confirmed
   back to the server, which works out your range from them and
   returns it. That last call carries numbers, never video, and the
   server keeps nothing from it; your range lives on your phone.
3. **Send feedback.** Sends your message, the topic you picked, the
   app version and the install ID. If you choose to attach one of
   your set videos, it is uploaded with the report and kept up to 90
   days, whether or not "Help improve rep counting" is on, so the
   developer can look at what you reported.
4. **Use the app.** At a few milestones (app opened, set recorded,
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

Like any web server, ours also records the internet address (IP
address) of each connection in an access log, with the time and the
path requested. That log is kept by our hosting provider under the
developer's account and is used only to keep the server running and
to spot abuse. We never join it to your videos or results.

### What the server does with a video

To count and measure reps, the server works out approximate
body-joint positions in each frame: hips, knees, shoulders and so on,
plus nose and ear points, which are used only to check the camera
angle. These are coarse positions, not a face scan and not a body
scan. They are used only to measure the movement, are never stored,
and are never used to identify anyone. They are discarded when the
analysis of that video ends.

### What is kept on the server, and for how long

Your uploaded video is deleted right after analysis in almost every
case. A video is kept only when it is evidence the measurement
needs: when the rep count you typed disagrees with the measured
count, or when the recording could not be measured at all (for
example, nobody was in frame). This rule only applies if you turned
on "Help improve rep counting" in Help & settings. It is off by
default; while it is off, nothing is ever kept, disagreement or not.

A kept video shows you, including your face if it was in frame. It
is viewed only by the developer, on the developer's own computer, to
check the measurement against what the video shows and to improve
rep counting. Kept videos are never published or shared, and are
deleted when that check is done, at the 90-day bound below, or on
your request, whichever comes first. You can turn the switch off at
any time; videos you submit after that are not kept.

Every kept video, including a video attached to feedback, is deleted
at most 90 days after upload, automatically.

The server also keeps one line per submission with counts, durations
and an error type (how many reps were detected, how long analysis
took, whether it failed and why), and one line per event. These log
lines hold counts, timestamps and the install ID. Never the video,
never your measured angles (the one measured number in the
rep-removal event is described above). Log lines are kept up to 12
months.

### Where the server is

Our analysis server is a computer we rent from Render, Inc., in
Oregon, United States. Everything that leaves your phone goes there
and nowhere else. If you use Caliper outside the United States, your
video and the other data above are sent to the United States when you
choose Analyze, run the range setup, or send feedback. Our basis for
that transfer, and for handling the video at all, is your consent:
you give it by choosing to upload, after the consent sheet that lists
what is sent, and you can withdraw it at any time by not analyzing
further sets and by turning "Help improve rep counting" off. Render
runs the machine and its disk and may keep backup snapshots of that
disk for up to 7 days, so a deleted file can exist in a snapshot for
up to 7 more days. That is the only way anyone besides the developer
holds a copy of anything you upload.

### Children

Caliper is not meant for children under 13, and we do not knowingly
collect anything from them. If you believe a child under 13 has used
the app and uploaded a video, write to us and we will delete it.

### Your rights

Whatever country you are in, you can:

- **Ask what we hold.** Use "Send feedback" in Help & settings
  (it carries your install ID, which you do not need to know) and
  we will tell you what the server holds for that install ID: any
  kept video, and the log lines tied to it.
- **Ask us to delete it.** See the next section. We honor deletion
  requests without questions.
- **Withdraw consent.** Turn "Help improve rep counting" off, stop
  analyzing sets, or delete the app. Nothing uploads without you.
- **Complain.** If you think we have handled your data wrongly, you
  can complain to the data-protection authority where you live. We
  would rather hear from you first, at the address below.

### Delete my data

- **On your phone:** delete a video (the training record stays),
  delete a set and its results, or delete the app, which removes
  every video, result and range on the phone.
- **On the server:** in almost every case there is nothing to
  delete, because videos are removed after analysis. To be sure,
  open Help & settings and tap "Ask to delete reviewed videos", or
  write to the support address below. When you do, every kept video
  from your install ID is removed, including any video you attached
  to feedback, and your install ID is replaced with the word
  "deleted" in our logs. Anonymous count lines remain (how many sets
  were analyzed that day, for example) and are not linked to you.
  Every kept video is deleted automatically at most 90 days after
  upload in any case.

### Contact

Privacy questions, access requests or deletion requests:
calipersupport@gmail.com. The same address is listed in the app
under Help & settings.
