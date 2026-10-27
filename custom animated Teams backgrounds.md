---
layout: default
---

## Custom Animated Teams Backgrounds

This is still a hack where you replace one of the Microsoft MP4s with your own, under the filename Teams is expecting.

- Use one of the "stock" animated backgrounds in a meeting or call. This triggers a download of all the attendant MP4 files. (If you don't have a meeting scheduled, start one spontaneously by going to the Calendar and clicking `Meet Now` at upper right.)
- Close Teams completely, including in the system tray.
- Go to `%localappdata%\Packages\MSTeams_8wekyb3d8bbwe\LocalCache\Microsoft\MSTeams\Backgrounds`
- The files with an `.mp4` extension are the animated ones. Choose one you don't particularly like, remember how it looks, and replace it with your own, under the same filename.
- Keep a backup copy of your MP4. When Teams updates itself, it may overwrite the MP4s with the Microsoft ones, and you'll have to repeat this process to restore your custom background.
- Restart Teams, and when you select that background, yours should play instead. (The preview won't look like your video, it will look how it did before.)