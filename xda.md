[CENTER][URL='https://libremobileos.com/lmodroid'][IMG]https://raw.githubusercontent.com/iKeramat/lmo-xda/twelve/logo.png[/IMG][/URL][/CENTER]
[CODE]* Your warranty is now void.
* We are not responsible for anything that may happen to your phone by installing any custom ROMs and/or kernels.
* You do it at your own risk and take the responsibility upon yourself and you are not to blame us or XDA and its respected developers.[/CODE]

[URL='https://libremobileos.com/lmodroid']LMODroid[/URL] is an AOSP-based mobile OS aiming to ease transition to de-googled(*) Android use-cases, while also supporting using Google services. Additionally, we want to make everyday experience better with useful features

The term de-googled is complicated, as AOSP by itself is by Google. We aim to reduce Google's data collection on mobile devices and make active efforts to remove contacts to Google servers and document more regarding this topic, but we value application compatibility over total Google avoidance.

[B][U]Features:[/U][/B]
[CODE]UI/UX:
- Blur control
- Transparent control

Network & internet
- Control connected devices to hotspot (disconnect/backlist)
- eSIM support
- VPN tethring

Display:
- Lockscreen media art
- Pocket detection
- Customizable Wallpaper & style
- OSS Desktopmode

Sounds & vibration:
- In-call vibration
- Dual SIM rington
- Per-app volume control

Security:
- Enforcing selinux
- Encrypted storage
- OSS Face Unlock
- 3x3 / 4x4 / 5x5 / 6x6 pattern size
- Scramble pin layout
- QS toggle on lockscreen
- App lock
- Auto reboot
- Restrict USB
- Emergancy Panic trigger

Applications:
- Game Space
- Transistent task mode
- Parallel Space

Buttons:
- Taskbar toggle
- Invert layout
- Force navigation bar enabler
- Edge long swipe actions
- Advanced restart
- Power menu styles
- Long press button to enable torch
- Volume button control playback
- Volume panel on left
- Partial screenshot

Statusbar:
- QS quick pull down
- Network traffic monitor
- System icons tuner
- Old style signal icons
- Wi-Fi standart Icons
- Clock position
- Show seconds
- Auto hide
- AM/PM style
- Battery style
- QS Auto brightness toggle
- Data usage[/CODE]

[B][U]Changelogs:[/U][/B]
[URL]https://get.libremobileos.com/changes[/URL]

[U][B]Download:[/B][/U]
[URL]https://get.libremobileos.com/devices/codename/builds[/URL]

[B][U]Notice:[/U]
- [U]Recommended firmware is latest stable firmware[/U][/B]
- No custom kernels and custom modules are supported. Only stock kernel and official builds will be supported. No bug reports if that's not the case.

[U][B]Installation:[/B][/U]
Download *.img files from download section and install them from fastboot.
example:
[CODE]fastboot flash boot boot.img
fastboot flash recovery recovery.img
fastboot flash super super_empty.img[/CODE]
After installed all .img files reboot to recovery and follow these steps:
Factory reset:
- format data/cache/system
Apply update -> Apply from ADB:
[CODE]adb sideload LMODroid-*-RELEASE-codename.zip[/CODE]

[B][U]Useful links:[/U]
Web[U]:[/U][/B] https://libremobileos.com/
[B]Download[U]:[/U][/B] https://get.libremobileos.com/
[B]Gerrit: [/B]https://gerrit.libremobileos.com/
[B]Jenkins:[/B] https://jenkins.libremobileos.com/
[B][B]Git:[/B][/B] https://git.libremobileos.com/LMODroid
[B][B]Git devices:[/B][/B] https://git.libremobileos.com/LMODroid-Devices
[B]Github(mirror):[/B] https://github.com/LMODroid
[B]Github devices(mirror):[/B] https://github.com/LMODroid-Devices
[B]Telegram discussion group:[/B] https://t.me/LMODroid_Discussion