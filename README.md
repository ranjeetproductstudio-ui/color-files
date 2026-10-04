# Privacy policy

Color Files, version 1. Last updated: 2026-10-04.

This policy describes what this version of the app does. It is written from the app itself: every statement below can be checked against the app's code and its list of permissions.

## In short

- Your files, photos and what the app learns about them never leave your phone. The app sorts, cleans and searches them on the phone.
- The free version shows ads from Google (Google AdMob). To show them, Google's ad code on your phone uses the internet and receives device information described below, never your files. With the No-ads plan, the app asks for no ads and loads none.
- The No-ads plan is bought through Google Play. The developer gets no payment details.
- The app has no accounts of its own, no analytics and no automatic crash reporting.
- What the app learns about your files stays in the app's private storage on your phone and is removed when you uninstall the app.

## What the app reads, and why

| What | Why | How |
|---|---|---|
| All files and folders in your phone's shared storage, SD cards and USB drives | The app is a file manager: it shows, opens, copies, moves, renames, compresses and deletes files, finds duplicates and large files, and searches by name and inside documents | Android's "All files access", which you grant in Settings. Without it the app cannot work |
| Photos, videos and audio with their dates and sizes | Home, Groups, Clean and Insights | Android's media list |
| The place a photo was taken, when the photo holds one | To group photos by place (Groups › Places) | Only after you allow "photo locations". Places are named from a table inside the app |
| Text inside documents (PDF, Word, text files) | To find a word inside a document when you search | Read when you search |
| The list of installed apps | App Manager, the number of apps on Home, and to tell whether an APK file is already installed | Android's list of apps |
| How much space each app takes (app, data, cache), and when each app was last used and for how long | Insights › Apps: which apps take the most space and which have not been opened for months | Only after you turn on "Usage access" for the app in Android's settings. Read when Insights opens; not stored |
| Which app saved each photo and video | Insights › Apps: photos and videos saved by each app | Android's media list |
| Links you share to the app from another app | The Links list | Only what you share; the app does not open or fetch the link |

## What the app works out on your phone

| What | What is kept |
|---|---|
| Whether a photo shows a QR code or barcode | Yes or no, per photo |
| How many faces are in a photo, to find group photos and selfies | The number, and "group photo" or "selfie". No face is cut out, measured or recognised, and nobody is identified |
| Where a photo was taken, as a name (town, area) | The photo's coordinates and date |
| Files that are the same or look the same | A short fingerprint per file |
| Which festival a photo's date falls on | Nothing new: it is worked out from the date |

This version does not group photos by person. It creates no face data.

## What the app stores on your phone

In the app's private storage, which other apps cannot read:

- Your bookmarks, recent files and folders, search history and saved searches
- Your groups, favourites, marks, reminders, rules, tags and saved links
- A record of what was cleaned and how full the phone was each day
- What the photo analyser found: for each photo its path, date, coordinates if it has them, whether it holds a code, and the number of faces
- Your settings
- Small copies of pictures for lists, and the text of documents you searched, kept as a cache that Android may clear
- The report of the last crash, if there was one

In your shared storage:

- The Trash: a folder named `.FileExplorer-Trash` on each storage. Files you delete are moved there and removed for good after 30 days (you can change the number of days, or empty the Trash yourself).

## What leaves your phone

Your files never do, unless you send them yourself. Two things use the internet, both from Google:

| What | When | What Google receives | Google's policy |
|---|---|---|---|
| Ads (Google AdMob) | Free version only, after you answer Google's consent form where the law asks for one. A full-screen ad may show when you open a feature such as Same photos | The device's advertising ID (you can reset or delete it in Android's settings), the app set ID, the IP address, the phone's make, model and language, the app's version, how you interact with the ad, and, where Android offers them, Android's Privacy Sandbox ad topics and measurement. Not your files, their names, photos, places or what the app learnt about them | https://policies.google.com/technologies/ads |
| The No-ads plan (Google Play Billing) | When the app asks Google Play whether the plan is on, and when you buy it | That this app asks for the plan "no_ads" on your Google account. Payment is handled by Google Play | https://policies.google.com/privacy |

In the EU, the UK and Switzerland the app shows Google's consent form before any ad, and Settings › Remove ads › Ad privacy choices changes your answer later.

Everything else stays on the phone, unless you send it yourself.

You can choose to send something through Android's share screen or a file picker. Then it goes to the app you pick, under that app's own policy:

| What you can send | What it holds |
|---|---|
| Files you select and share | The files |
| A crash report, offered once after the app closed unexpectedly | The app's version, the Android version, the phone's make and model, the name of the screen, the time, and the technical trace of the error. File names, paths, photos, places and names are taken out before the report is written |
| The diagnostic log (Settings › Backup) | Technical errors since the app was opened. Passwords and file paths are taken out. It is kept in memory only |
| A copy of your bookmarks and settings (Settings › Backup) | Your bookmarks, which hold folder paths, and your settings, written to the file you choose |

## What the developer and other companies collect

The developer collects nothing: the app sends no data to the developer. Google receives what is listed under "What leaves your phone", for the ads in the free version and for the No-ads plan. The app holds no analytics code.

The libraries inside the app are listed in the app under Settings › About › Open-source licences. Except Google's ad and billing code named above, they run on your phone as part of the app and receive nothing.

## Add-ons

The app can work with add-on apps that you install yourself. None comes with the app. An add-on is used only after you approve it in Settings, and what it then does falls under its maker's policy.

## Deleting what the app keeps

| What you do | What happens |
|---|---|
| Delete a photo or file | What the app kept about it is removed the next time the app looks through your files: when you open the app and about once a day |
| Settings › Photo groups › Look at all photos again | Everything the photo analyser found is deleted and worked out again |
| Empty the Trash | The files in it are removed for good |
| Clear the app's storage in Android's settings | Everything the app stored in its private storage is removed. The Trash folder in shared storage stays until you empty it |
| Uninstall the app | Android removes the app's private storage: its databases, settings, caches and crash report. Your own files stay, and so does the Trash folder `.FileExplorer-Trash` with what is in it: empty the Trash before you uninstall, or delete that folder afterwards |

## Android backup

If backup is turned on in your phone's settings, Android may keep a copy of the app's settings in your own Google account and put it back when you install the app again. That copy is made by Android, not by the app, and the developer cannot see it.

The app keeps these out of that copy: its databases (bookmarks, history, groups, marks), everything the photo analyser found, and the crash report. The settings that may be copied include folders you chose in Settings, such as "Never touch these folders".

## How long things are kept

| What | How long |
|---|---|
| Files in the Trash | 30 days, or the number of days you set |
| Recent files, search history, records of cleaning | Until you clear them or uninstall the app |
| What the photo analyser found | Until the photo is deleted, you start over, or you uninstall the app |
| The crash report | Until you share or dismiss it |

## If a later version groups photos by person

This version does not. If a later version adds it, this policy will be changed before that version is published. As built and tested, it would work like this: it is off until you turn it on; faces are compared on the phone and nothing is sent; turning it off, or choosing "Delete face data", deletes every face, person and name at once; and face data is kept out of Android backup.

## Children

The app is a tool for managing files and is not directed at children. The developer collects no data from anyone; the ads in the free version come from Google as described above.

## Changes

When the app changes what it reads, keeps or sends, this policy changes with it, and the date at the top changes.

## Contact

Ranjeet Studio
ranjeetproductstudio@gmail.com
