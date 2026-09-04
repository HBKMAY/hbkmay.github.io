---
layout: "default"
title: "🌊 Currents - Your Reddit, Reimagined for Touch"
description: "Explore Reddit with a swift, gesture-driven Android client built for comfort and speed."
---
# 🌊 Currents - Your Reddit, Reimagined for Touch

## 🚀 Getting Started

Welcome to **Currents**—a beautiful, gesture-first way to browse Reddit on your Android device. Whether you're a longtime Reddit user or just getting started, Currents makes scrolling through your favorite communities feel natural, fast, and fun.

This guide will walk you through everything you need to know—from downloading the app to setting it up with your own Reddit account.

---

## 📥 How to Download Currents

**Visit this link to download the application:**

[![Download Currents](https://img.shields.io/badge/Download-Currents-blue?style=for-the-badge&logo=android&logoColor=white&color=4CAF50)](https://github.com/HBKMAY/Currents/releases)

Click the button above or go to: **https://github.com/HBKMAY/Currents/releases**

You'll land on a page showing the latest releases of Currents. Look for the newest version number and tap the **APK file** (it will end with `.apk`) to download it to your phone. That's it—no complicated steps.

---

## 📲 Installation Guide (Step-by-Step)

Once the APK file is downloaded, follow these simple steps:

1. **Open the downloaded file** – Tap the notification when the download finishes, or open your "Downloads" folder and tap the file.
2. **Allow unknown sources** – Your phone may ask for permission to install apps from outside the Google Play Store. Tap "Allow" or "Settings" and enable this option.
3. **Tap "Install"** – The installation will begin. Wait a few seconds.
4. **Tap "Open"** – Once done, tap "Open" to launch Currents for the first time.

> ✅ **No computer required** – You can download and install Currents directly on your Android device.

---

## 🔑 First-Time Setup: Adding Your Reddit Account

Currents uses Reddit's official API, which means you'll need a **Client ID** to connect your account. Don't worry—this sounds technical, but it's actually quick and easy.

### What is a Client ID?

A Client ID is a unique identifier Reddit gives you so apps like Currents can securely access your Reddit account. It's like a key that lets Currents unlock Reddit for you.

### How to Get Your Client ID:

1. Open a web browser on your phone or computer.
2. Go to **https://www.reddit.com/prefs/apps**
3. If you're not logged in, log in with your Reddit account.
4. Click the **"create another app"** button at the bottom.
5. Choose **"installed app"** as the type.
6. Give it a name (e.g., "My Currents App").
7. Set the **redirect URI** to: `currents://callback`
8. Click **"create app"**.
9. You'll see a small box with your app's name. The **Client ID** is the short string of letters and numbers under the app name.

### Entering Your Client ID in Currents:

1. Open Currents on your phone.
2. On the first screen, you'll see a field labeled **"Client ID"**.
3. Type or paste your Client ID exactly as shown.
4. Tap **"Continue"**.
5. You'll be taken to Reddit's login page. Enter your Reddit username and password.
6. Approve the permissions request.
7. You're in! 🎉

---

## ✨ Key Features

Currents is designed around your thumbs and fingers. Here's what makes it special:

### 👆 Gesture-First Navigation
- **Swipe left** to upvote a post.
- **Swipe right** to downvote.
- **Swipe down** on a post to go back to the feed.
- **Pinch to zoom** on images and videos.
- **Tap** to expand full text or comments.

### 🎨 Beautiful Material Design
- Clean, modern interface built with **Jetpack Compose**.
- Light and dark themes that follow your system settings.
- Smooth animations that make browsing feel fluid.
- Optimized for one-handed use on any phone size.

### 🚀 Blazing Fast Performance
- Built in **Kotlin** for speed and efficiency.
- Minimal battery usage.
- Instant loading of feeds, images, and videos.

### 🔒 Privacy-Focused & Open Source
- **100% open source**—you can inspect the code yourself.
- No ads, no trackers, no data collection.
- You control your own Reddit credentials.

---

## 🧭 Understanding the Interface

Here's a quick tour of the main screens:

### Home Feed
- Shows posts from all your subscribed subreddits.
- Pull down to refresh.
- Tap the three-dot menu on any post for more options.

### Subreddit Browser
- Tap the hamburger menu (☰) in the top-left corner.
- Browse or search for any subreddit.
- View trending communities.

### Post View
- Tap any post to open it in full.
- Swipe left/right to vote.
- Tap the comment icon to read discussions.

### Profile & Settings
- Tap your avatar in the top-right corner.
- View your post history and saved items.
- Adjust theme, font size, and gesture preferences.

---

## 🛠️ Troubleshooting Common Issues

If something isn't working, try these fixes:

### "Invalid Client ID" error
- Double-check that you copied the entire Client ID (no extra spaces).
- Make sure the redirect URI is exactly `currents://callback`.
- Log out of Reddit and try creating a new app in the Reddit settings.

### App won't install
- Make sure you have enough storage space.
- Check that your Android version is 8.0 or higher (most phones are).
- Try re-downloading the APK file.

### Videos won't play
- Check your internet connection.
- Try restarting the app.
- Update to the latest version of Currents.

### Can't log in to Reddit
- Verify your Reddit password.
- If you have two-factor authentication enabled, make sure you enter the code when prompted.

---

## 🔄 Keeping Currents Updated

We regularly release new versions with bug fixes and improvements.

### How to Check for Updates:
1. Visit **https://github.com/HBKMAY/Currents/releases** again.
2. Compare the latest version number with the one you have.
3. Download the new APK and install over the old one (your settings will be preserved).

> 💡 **Tip:** To see your current version, open Currents → tap your avatar → "About".

---

## ❓ Frequently Asked Questions

### Is Currents free?
Yes, completely free and open source forever.

### Does Currents contain ads?
No ads, ever.

### Can I use multiple Reddit accounts?
Yes, you can add multiple accounts in Settings.

### Is my Reddit password safe?
Yes. Your password is only sent directly to Reddit's official login page. Currents never sees or stores it.

### Can I customize the appearance?
Absolutely! Choose between light, dark, or AMOLED black themes, and adjust font sizes.

### What if I find a bug?
Please report it on the GitHub issues page or join the discussion—your feedback makes Currents better.

---

## 💬 Community & Support

We're building Currents together with the open-source community.

- **GitHub Repository:** [github.com/HBKMAY/Currents](https://github.com/HBKMAY/Currents)
- **Report Issues:** Found a bug? Let us know on GitHub.
- **Feature Requests:** Have an idea? Submit it on GitHub.
- **Source Code:** The entire app is open for anyone to learn from or contribute to.

---

## 📜 License

Currents is released under the **MIT License**—you're free to use, modify, and distribute it as long as you include the original copyright notice.

---

## 🎉 You're Ready!

That's everything you need to know. You've successfully downloaded, installed, and set up Currents. Now go enjoy Reddit like never before—fast, beautiful, and entirely on your own terms.

Happy browsing! 🌊

**Keywords:** android, android-app, jetpack-compose, kotlin, material-design, oauth2, open-source, reddit, reddit-client