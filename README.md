# BetterDiscord Plugins

### [BetterFolders](/dist/bd/BetterFolders.plugin.js) <sub><sup>`v3.0.0` *(Updated: 9/11/21)*</sup></sub>
Add new functionality to server folders.
Current Features:
- Custom Folder Icons
- Close other folders on open

### [BetterVolume](/dist/bd/BetterVolume.plugin.js) <sub><sup>`v2.0.0` *(Updated: 07/11/21)*</sup></sub>
Set user volume values manually instead of using a limited slider.

### [Emulator](/old/Emulator.plugin.js) <sub><sup>`v2.0.0` *(Updated: 14/11/20)*</sup></sub>
Emulate Windows, MacOS, Linux or Browser on any platform.
**WARNING:** Emulating a different platform may cause unwanted side effects. Use at own risk.

### [OnlineFriendCount](/dist/bd/OnlineFriendCount.plugin.js) <sub><sup>`v2.0.0` *(Updated: 07/11/21)*</sup></sub>
Add the old online friend count back to guild list. Because nostalgia.

### [VoiceEvents](/dist/bd/VoiceEvents.plugin.js) <sub><sup>`v2.0.0` *(Updated: 07/11/21)*</sup></sub>
Add TTS Event Notifications to your selected Voice Channel. TeamSpeak feeling.

<br>

---

<br>

## Building from source
```sh
# install dependencies
npm install

# build all plugins
npm run build

# build single plugin
npm run build -- BetterFolders

# build single plugin to BetterDiscord folder & watch for changes
npm run dev -- BetterFolders
```
