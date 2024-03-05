> Credit: Learned method through user latalante1p[^1]

# Instructions:

Requires: systemd

To install...
1. Place script in desired directory (ex: /usr/bin)
2. `chmod a+x` the script.
3. Edit your desktop entry at `/usr/share/applications/firefox-esr.desktop` and change the `Exec=` destination to point to your script.
4. Restart Desktop Environment.

Change your `MemoryMax=` value to desired RAM usage limit. (Exmaples: `MemoryMax=2G` for 2 Gigabytes, `MemoryMax=200M` for 200 Megabytes.)



>[!NOTE]
>This can be applied to other programs in linux. Essentially, just replace any line concerning firefox with the desired program when using this script. I only used Firefox in this script as it's a common resource hog on my smaller linux devices.


[^1]: https://bbs.archlinux.org/viewtopic.php?pid=2006208#p2006208
