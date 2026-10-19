# Blip: closed playtest

Thanks for testing Blip! You need an **invite code** to sign up. Ask the person who sent you this link.

## Download

Get the latest files from **[Releases](../../releases/latest)**:

| Computer | File |
|---|---|
| Mac with Apple Silicon (M1 or newer) | `Blip-…-arm64.dmg` |
| Windows 10/11 (64-bit) | `Blip-…-win32-x64.zip` |

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

## Signing up

Open Blip → **Settings › Blip Online** → sign up with your email, a password and your invite code. Once you're in, the **+** on the Friends page has invite codes of your own to share.

## Feedback

Quit Blip and a small **"Before you go"** box pops up. Bugs, ideas, anything: it goes straight to the Blip team.
