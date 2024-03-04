# Instructions[^1]:

Requires: systemd

To install...
1. Place scipt in desired directory (ex: /usr/bin)
2. `chmod a+x` the script.
3. Edit your desktop entry at `/usr/share/applications/firefox-esr.desktop` and change the `Exec=` destination to point to your script.

Change your `MemoryMax=` value to desired RAM usage limit. (Exmaples: `MemoryMax=2G` for 2 Gigabytes, `MemoryMax=200M` for 200 Megabytes.)

>[!NOTE]
>This can be applied to other programs in linux. Essentially, just replace firefox with the desired program when using this script. I only used Firefox in this script as it's a common resource hog on my smaller linux devices.

[^1]: Discovered from this form: https://bbs.archlinux.org/viewtopic.php?id=271719
