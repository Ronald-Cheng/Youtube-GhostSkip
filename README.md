# Youtube-GhostSkip
Ambient Safari extension designed to automate the YouTube advertisement experience.

👻 YouTube GhostSkip

A fun, ambient Safari extension designed to automate the YouTube advertisement experience.

Note: This project is for educational/fun purposes. It does not "block" ads in a way that makes them disappear entirely from the stream. Instead, it uses a high-speed "Ghost Skip" workflow to fast-forward through ads automatically, providing a truly hands-free experience.

✨ Key Features

Automatic Detection: Identifies ads in any mode (Theater, Fullscreen, Default).

GhostSkip Workflow:

Detects an ad phase.

Plays at 16x speed for 0.5s to maintain player stability.

Instantly jumps to the final 10 seconds of the ad.

Finishes the remainder at 16x speed.

Ambient Design: Mutes audio and hides the video element during the skip sequence so you aren't interrupted by ad visuals or sound.

Smart Restoration: Automatically returns to 1x speed and restores audio once the main content starts.

🚀 How to Install (Safari)

Since this is a Safari Web Extension, follow these steps to use it on your Mac:

1. Enable Developer Menu in Safari

Open Safari.

Go to Settings (or Preferences) > Advanced.

Check the box: "Show features for web developers" (or "Show Develop menu in menu bar").

2. Allow Unsigned Extensions

In the Safari menu bar, click on Develop.

Click Allow Unsigned Extensions. (Note: You will need to do this every time you restart Safari for security reasons).

3. Load the Extension

Clone this repository or download the ZIP file and unzip it.

Open the project folder and launch the .xcodeproj file in Xcode.

Select the YouTube AdSkip scheme and click the Play button (Run).

Once the host app opens, go back to Safari > Settings > Extensions.

Check the box next to YouTube AdSkip to enable it.

🛠 Project Structure

.appex: The Safari Extension bundle.

.swiftmodule: Compiled Swift code for the macOS host app.

content.js: The "GhostSkip" logic that handles the video manipulation and speed control.

📜 Disclaimer

This project is for fun and personal use. It is not intended to bypass YouTube's terms of service but rather to experiment with browser automation and video DOM manipulation.

Made with ❤️ for a better YouTube experience.
