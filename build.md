YouTube: 18.32.39  
YouTube-Android6-7: 17.34.36  
YouTube-Extended: 18.30.37  
Music (arm64-v8a): 6.17.52  
Music (arm-v7a): 6.17.52  
Music-Extended (arm64-v8a): 6.17.52  
Music-Extended (arm-v7a): 6.17.52  

Install [Vanced Microg](https://github.com/TeamVanced/VancedMicroG/releases) for non-root YouTube or YT Music  

[revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)  

---
Changelog:  
CLI: j-hc/revanced-cli-3.1.0-all.jar  
Integrations: ReVanced/revanced-integrations-0.117.1.apk  
Patches: ReVanced/revanced-patches-2.190.0.jar  

### [2.190.0](https://github.com/ReVanced/revanced-patches/compare/v2.189.0...v2.190.0) (2023-09-03)
### Bug Fixes
* **Infinity for Reddit - Spoof client:** Support latest version ([8a5311b](https://github.com/ReVanced/revanced-patches/commit/8a5311b1e645ca2aab1e416d647cf52bf0be6e7f))
### Features
* **Photomath:** Support latest version ([5a2cad0](https://github.com/ReVanced/revanced-patches/commit/5a2cad077f03880ee1417c5cfd448bbdea4c07e2))
* **Twitch:** Support version `16.1.0` ([#2923](https://github.com/ReVanced/revanced-patches/issues/2923)) ([d9834a9](https://github.com/ReVanced/revanced-patches/commit/d9834a9abb43390af4cb33f5dd5a0e2d3b7060e2))

---
CLI: inotia00/revanced-cli-2.22.2-all.jar  
Integrations: inotia00/revanced-integrations-0.115.1.apk  
Patches: inotia00/revanced-patches-2.187.1.jar  

YouTube
==
- feat(youtube): add support version `v18.30.37`
- feat(youtube/hide-button-container): now it support versions other than YouTube v18.20.39 https://github.com/ReVanced/revanced-patches/pull/2723
- fix(youtube/integration): move dependence to dummy class path
- fix(youtube/microg-support): app does not close when an error occurs
- fix(youtube/microg-support): error toast message is not set correctly
- feat(youtube/translations): update translation
`Belarusian`, `Bulgarian`, `Chinese Traditional`, `French`, `German`, `Greek`, `Hungarian`, `Indonesian`, `Italian`, `Japanese`, `Polish`, `Russian`, `Vietnamese`


Music
==
- feat(music): add `hide-channel-guidelines` patch
- feat(music/litho): add some exception
- feat(music/enable-new-layout): change default value
- feat(music/enable-new-layout): forcibly disable when the switch is off
- feat(music/enable-sleep-timer): forcibly disable when the switch is off
- feat(music/translations): update translation
`Brazilian`, `Chinese Traditional`, `French`, `Indonesian`, `Korean`, `Russian`, `Spanish`, `Ukrainian`, `Vietnamese`


Etc
==
- At the end of this release, RVX has been [discontinued](https://github.com/inotia00/revanced-documentation/wiki/Announcement). Thank you for using it so far.


※ Compatible ReVanced Manager: [RVX Manager v1.5.2 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.5.2)

---
CLI: j-hc/revanced-cli-3.1.0-all.jar  
Integrations: kitadai31/revanced-integrations-0.96.5.apk  
Patches: kitadai31/revanced-patches-2.160.5.jar  

**This update fixes the issue that video stops and starts buffering at 1:09 or 1:10!**

### Changes

- feat(spoof-player-parameter): Reflect original RVX / ReVanced changes
  - Add new spoofing type (This solves the buffering at 1:09 issue)
  - Change patch name ( `protobuf-spoof` -> `spoof-player-parameters` )
  - Enabled by default (nonroot only)
  - Remove automatic enable feature
- feat(spoof-app-version): Show reboot dialog after set
- feat(spoof-app-version): Move spoofing examples to external webpage ([GitHub Wiki](https://github.com/kitadai31/revanced-patches-android6-7/wiki/Spoof-app-version-information))
- Add reboot dialog when installing for the first time
- Add `os-version-check` patch (default = Excluded)
- Update dependencies
- Bump revanced-patcher to 12.1.0

### Announcements
• Telegram channel has been opened.
<img height=
---  
