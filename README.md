# Blip: closed playtest

Thanks for testing Blip! You need an **invite code** to sign up. Ask the person who sent you this link.

## Download

Get the latest files from **[Releases](../../releases/latest)**:

| Computer | File |
|---|---|
| Mac with Apple Silicon (M1 or newer) | `Blip-…-arm64.dmg` |
| Windows 10/11 (64-bit) | `Blip-…-win32-x64.zip` |

The files are big (about 550 MB for Mac and 740 MB for Windows), so give the download a few minutes.

**Want a version with no AI, voice or microphone?** Get **Blip Social** instead. It has the pet, friends, chats, music and the Blip World, and never asks for the microphone. Its files are named `Blip-Social-…` and are on the [Blip Social releases](../../releases?q=social&expanded=true). The install steps below are the same.

## Install on Mac

1. Open the `.dmg` and drag **Blip** into **Applications**.
2. Open Blip. macOS will say Apple could not verify Blip is free of malware: click **Done**, *not* Move to Trash. (Blip isn't signed by Apple yet; it's safe.)
3. Open **System Settings → Privacy & Security** and scroll down to **Security**.
4. You'll see *"Blip" was blocked to protect your Mac*. Click **Open Anyway** and enter your Mac password.
5. Open Blip again and click **Open Anyway** in the next box.
6. Allow the permissions Blip asks for:
   - **Microphone** and **Speech Recognition**, so "Hey Blip" and Talk work.
   - **Screen & System Audio Recording**, so the visualizers move with your music. Blip only listens to the sound and never records your screen.

   If the visualizers don't move: open **System Settings → Privacy & Security → Screen & System Audio Recording**, turn on **Blip**, then quit and reopen Blip.

You only need to do this once.

### No admin password? (work or school Macs)

If **Open Anyway** asks for an administrator name and password you don't have, use Terminal instead:

1. Drag **Blip** into **Applications** as above.
2. Open **Terminal** (Spotlight: press ⌘ Space and type *Terminal*).
3. Paste this line and press **Return**:

   ```
   xattr -dr com.apple.quarantine /Applications/Blip.app
   ```

4. Double-click **Blip**. It now opens normally.

If Terminal says *Permission denied*: drag Blip to your **Desktop** instead, run `xattr -dr com.apple.quarantine ~/Desktop/Blip.app`, then move Blip into Applications.

## Install on Windows

1. Right-click the `.zip` → **Extract All** → **Extract**. Keep the whole folder together.
2. Open the extracted **Blip** folder and double-click **Blip.exe**.
3. Windows will say *"Windows protected your PC"*: click **More info**, then **Run anyway**. (Blip isn't code-signed yet; it's safe.)
4. Allow the **microphone** when asked, so "Hey Blip" and Talk work.
   If Blip can't hear you: **Settings → Privacy & security → Microphone** → turn on **Let desktop apps access your microphone**.

You only need to do step 3 once.

## First time you open Blip

A small card appears under your egg and asks whether you're **new** or **already have a Blip**.

- **I'm new:** tap the egg three times (or press **Hatch it**) and your Blip hatches. Pick the name friends will see, then paste the invite you were sent (the whole message works) and add your email and a password. You start with 10,000 coins and **3 invite codes of your own** to give to friends. The **+** on the Friends page has them.
- **I already have a Blip** (on another computer, or you reinstalled): choose **I already have a Blip: sign in** and use your email and password. Your own Blip hatches out of the egg just as you left her, with your coins, items and friends. You don't make a new one.

Blip Online works on one computer at a time: signing in on another computer signs you out of the first.

## Updating

Blip updates itself. When a new version is ready it shows **Update now**; press it. If you haven't opened Blip for a while, open it and wait a minute. On Windows, if you have a version older than 0.35.37 and the update won't start, download the latest `.zip` above and install it over the top. Your account, coins and friends are kept.

## Feedback

Quit Blip and a small **"Before you go"** box pops up. Bugs, ideas, anything: it goes straight to the Blip team.
