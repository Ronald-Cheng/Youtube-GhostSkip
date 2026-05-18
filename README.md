# YouTube-GhostSkip

### Ambient Safari extension designed to automate the YouTube advertisement experience.

---

## 👻 YouTube GhostSkip

A fun, ambient Safari extension designed to automate the YouTube advertisement experience.

**Note:** This project is for educational/fun purposes. It does not "block" ads in a way that makes them disappear entirely from the stream. Instead, it uses a high-speed "Ghost Skip" workflow to fast-forward through ads automatically, providing a truly hands-free experience when facing ads while watching YouTube videos.

---

## 🚀 How to Install & Set Up

Follow these steps to get the extension running on your Mac without needing to touch any code.

### Step 1: Download and Install the App

1. Click on the **Youtube AdSkip App.zip** file here on GitHub and download it.
2. Unzip the file on your Mac.
3. Drag the unzipped **Youtube AdSkip** app icon into your Mac's **Applications** folder.

### Step 2: Handle the macOS Security Bypass
Because this app is not distributed through the official App Store, macOS will show a `"Youtube AdSkip" Not Opened` verification warning when you try to open it. 

To bypass this safely:
1. Click the **Apple Menu** () in the top-left corner of your screen and open **System Settings**.
2. Navigate to **Privacy & Security**.
3. Scroll down to the *Security* section.
4. You will see a notice saying `"Youtube AdSkip" was blocked from use...`. Click the **Open Anyway** button next to it.
5. Enter your Mac password to confirm, then click **Open** on the final pop-up.

---

### Step 3: Configure Safari to Run the Extension

Safari requires developer permissions to run local, unsigned extensions. You must turn this option on:

1. Open **Safari**.
2. Go to the menu bar and choose **Safari > Settings** (or Preferences) > **Advanced**.
3. Check the box at the very bottom: **"Show features for web developers"** (or "Show Develop menu in menu bar").
4. Look at your Safari menu bar at the top of the screen, click on the new **Develop** menu, and select **Allow Unsigned Extensions**. *(Note: You will need to click this option once every time you fully restart Safari for security reasons).*
5. Finally, go to **Safari > Settings > Extensions** and check the box next to **YouTube AdSkip** to turn it on!

---

## ✨ Key Features

* **Automatic Detection:** Identifies ads in any mode (Theater, Fullscreen, Default).

* **GhostSkip Workflow:**
    1.  Detects an ad phase.
    2.  Plays at **16x speed** for 0.5s to maintain player stability.
    3.  Instantly jumps to the final **10 seconds** of the ad.
    4.  Finishes the remainder at **16x speed**.

* **Ambient Design:** Mutes audio and hides the video element during the skip sequence so you aren't interrupted by ad visuals or sound.

* **Smart Restoration:** Automatically returns to **1x speed** and restores audio once the main content starts.

---

## 🛠 Project Structure

* **Youtube AdSkip.zip**: The ready-to-run precompiled macOS application housing the Safari extension.

---

## 📜 Disclaimer

This project is for fun and personal use. It is not intended to bypass YouTube's terms of service but rather to experiment with browser automation and video DOM manipulation.

*Made with ❤️ for a better YouTube experience.*
