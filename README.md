# AI Vocal Coach

Releases of **AI Vocal Coach**, a karaoke app for Windows that reads your pitch in real time and
coaches you when the song ends. Sing over any YouTube backing track, compare yourself with the
original singer, practise phrase by phrase, and get feedback from an AI vocal coach.

## Download
Open the [latest release](../../releases/latest) and download every `AIVocalCoach-windows-<version>` zip
(the full build is split into `.part1.zip`, `.part2.zip`, … because GitHub limits a file to 2 GB).

## Updates
The app includes an automatic update system.

When a new version is released, the app checks for updates when launched and downloads the latest
version automatically. The update is applied when you restart AI Vocal Coach, in the same place, so
your shortcuts and taskbar pin keep working.

`AIVocalCoach-update-<version>.zip` is used by the automatic updater. You don't need to download it.

## Installation
1. Download all `AIVocalCoach-windows-<version>` zip parts
2. Extract every part into the **same** folder (the folder is large because the voice-separation and speech models are included)
3. Run `AIVocalCoach\AIVocalCoach.exe`

> Windows may show "Windows protected your PC" because the app isn't signed. Choose **More info** → **Run anyway**.

> Do not run the app directly inside the ZIP file. Extract it first.

## Notes
- Use wired headphones: the backing track should not reach the microphone, and wireless headsets add delay.
- An NVIDIA GPU makes the original-song preparation much faster but is not required.
- The AI coach needs an OpenAI API key (Settings → OpenAI). Without one you still get rule-based feedback.
- Recordings, reports and prepared songs are kept in `Documents\AI Vocal Coach`.

If you encounter a problem, please report it so it can be fixed in a future update.

---
*Repository description:* `AI Vocal Coach - App Releases`
