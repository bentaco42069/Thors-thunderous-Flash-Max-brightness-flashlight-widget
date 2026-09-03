# Thor's Thunderous Flash ⚡

<div align="center">
  <img src="assets/banner.gif" alt="Thor's Thunderous Flash" width="100%">
</div>

A dead-simple Android **home-screen widget** (and app icon) that turns on your
phone's flashlight at **true maximum brightness** — the same ceiling the
built-in flashlight button hits, not the dim level most widget apps settle for.

## Why this is brighter than your old widget

Most flashlight widgets call `setTorchMode(true)`, which lights the LED at the
system's *default* strength — often well below what the LED can actually do.
This app calls **`turnOnTorchWithStrengthLevel()`** at the phone's reported
**maximum** strength level (Android 13+), so the LED runs as bright as the
hardware physically allows. On a Samsung Galaxy that matches the bright native
flashlight instead of the weak default.

> Note: no app can go *brighter than the hardware maximum* — that's a physical
> limit of the LED. This app's job is to reach that maximum, which your old
> widget wasn't doing.

<div align="center">
  <img src="assets/max-brightness.gif" alt="Max Brightness — lightning fills left to right" width="85%">
</div>

## What you get

- **A home-screen widget** made from a real **Mjölnir photo** — cut out, stood
  upright, head on top. Tap it → LED on at max, and three lightning bolts blaze
  gold out of the hammer's crown. Tap again → off, and the hammer dims and the
  bolts go dead gray, so you can tell at a glance it's off.
- **An app icon** ("Thor's Thunderous Flash") that does the same thing when tapped.

---

## How to install (Android)

<div align="center">
  <img src="assets/warning.gif" alt="Warning: High Intensity" width="70%">
</div>

1. **Tap the Download button** — it saves the app file (`thors-thunderous-flash.apk`) to your **Downloads**.
2. **Open it** — tap the file in Downloads (or the download popup).
3. **First time only — let your phone install it:** Android asks *"Allow this source to install apps?"* → tap **Settings** → turn **Allow from this source** **On** → tap back.
4. **Tap Install.**
5. **Google will try to stop you — don't quit here.** A warning pops up (*"Unsafe app blocked"* / *"App not scanned"*). **Don't tap OK / Don't install.** Tap the little **pull-down arrow (More details)** to open it up, then tap **Install anyway** — it installs.
   *(If it still refuses: Play Store → your profile picture → Play Protect → the ⚙ gear → turn **Scan apps with Play Protect** Off → install → turn it back On.)*
6. **Add the widget:** press-and-hold an empty spot on your home screen → **Widgets** → find **Thor's Thunderous Flash** → drag it on.
7. **Tap it** — flashlight blasts at max. Tap again to shut it off. ⚡

That's it. One press, brightest your phone can go.

## Still won't go? Every roadblock — and how to smash through it ⚡

Some phones (especially Samsung) throw up extra blocks. Here's every one and the fix — all roads lead to the light.

**Won't DOWNLOAD**
- **"This type of file can harm your device"** → tap **Download anyway / Keep**. *(In Chrome: tap the **⋮** on the download bar → **Download anyway**.)*
- **"Blocked as harmful"** → Chrome **⋮ → Downloads →** find the file **→ Download anyway / Keep**.
- **Downloaded inside a chat app (WhatsApp / Messenger / Instagram) and the file is empty or won't open** → open the link in **Chrome** or **Samsung Internet** instead — a chat app's built-in browser can save a broken file. Tap **⋮ → Open in browser**, then download.
- **Not enough space** → free up a little storage and re-download.

**Won't OPEN (tapping the file does nothing)**
- ⭐ **Samsung Auto Blocker is ON** — it blocks apps from outside the store, so the file won't open or install. **Settings → Security and privacy → Auto Blocker → turn it OFF**, install, then turn it back on. *(This is the #1 one people get stuck on.)*
- **"Can't open file" / nothing happens** → open your **Files** app (or Chrome **⋮ → Downloads**), tap **thors-thunderous-flash.apk**, and choose **Package installer**.
- **Saved as `.apk.zip` or a weird name** → rename it so it ends in **.apk**, or re-download.

**Won't INSTALL**
- **"Allow from this source" is off** → tap **Settings** on the prompt → turn **Allow from this source** ON. *(No prompt? **Settings → Apps → Special access → Install unknown apps →** pick your browser or Files **→ Allow**.)*
- **Play Protect "Unsafe app blocked" / "not scanned"** → **More details → Install anyway.** Still fighting you? **Play Store → your profile picture → Play Protect → ⚙ → turn "Scan apps with Play Protect" OFF**, install, then turn it back on.
- **"App not installed" / "invalid package"** → the download didn't finish — delete it and re-download. If an old copy is on the phone, uninstall it first.
- **An old version is already installed** → uninstall the old **Thor's Thunderous Flash** first, then install.
- **Package Installer is disabled** → **Settings → Apps → (show system apps) → Package installer → Enable.**
- **Work / school phone or parental controls (Family Link)** → whoever manages the phone has to allow unknown apps; a fully locked-down phone may not allow it at all.
- **A third-party antivirus is eating it** → whitelist the file, or pause the antivirus while you install.

One of these clears it every time. ⚡🔨

---

<div align="center">
  <a href="https://github.com/bentaco42069/Thors-thunderous-Flash-Max-brightness-flashlight-widget/releases/download/flashlight/thors-thunderous-flash.apk"><img src="assets/download.gif" alt="Get it — Download Thor's Thunderous Flash" width="300"></a>
</div>

## Requirements & notes

- **Android 8.0+** to install; **Android 13+** for the true max-strength boost
  (older phones still get full-on, which is their hardware max anyway).
- Needs a phone with a camera flash LED (every Galaxy has one).
- No internet permission, no ads, no tracking — it only talks to the flashlight.
- If the LED won't turn on, close any open **Camera** app first (the camera and
  the torch can't both own the flash at the same time).
