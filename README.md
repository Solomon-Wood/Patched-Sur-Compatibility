# Patched Sur Compatibility

I'm going to improve this repo in the morning, but I'm making something quick so if you came from Mr. Macintosh's video you are prepared. If you are here already, either remind yourself to do it tomorrow or just do it now.

These will show up in the next release of Patched Sur (I know pre-v1.0.1 had this, but after the down time this entire repo was lost and I didn't set it up in time for v1.0.1)

If you haven't seen what this looks like when it's deployed, I'll add a screenshot later. I made this in 30 minutes, and I don't want to develop more tonight. 

## Instructions to Contribute

1. [Look at my example](https://github.com/Ben216k/Patched-Sur-Compatibility/discussions/1)
2. [Open a new discussion](https://github.com/Ben216k/Patched-Sur-Compatibility/discussions/new)
3. Title it either your Mac Model (MacBookPro9,2 or MacBook Pro (13-inch, 2012), doesn't matter which)
4. Whatever you didn't do in the title make sure to put in the description (So if you did MacBook Pro (13-inch, 2012), then put MacBook Pro)
   - You can get `MacBookPro9,2` with `sysctl -n hw.model` in Terminal or you can check the About My Mac screen in Patched Sur.
5. Put a quick summary, it should not be what the works and warns are, basically just reassurance.
6. Put the works and warns (list below)
7. If you don't want me to credit you towards your GitHub, specify something else. I'm not doing links, just a basic "@Ben216k" or "u/SoAndSo"
8. Click Start Discussion, I might ask questions, so just check back every little bit and I should respond at some point.

## Works And Warns

Your works and warns should include all of the following (if you're not sure, make sure to specify that, I can probably already tell you yes or no) and anything you deem noteworthy. Also, some of these might not work in very very edge cases (that I can't explain), so be aware of that. You can ask questions, don't worry about that. My summary 

- WiFi, Ethernet, and Bluetooth (WiFi requires patching the kexts, probably worth specifying in the summary)
- I/O Ports (be specific if something doesn't work)
- Graphics Acceleration (all 2012 and later Macs will have this)
- Sleep and Brightness (if you have Graphics Acceleration, you have this)
- FileVault (Doesn't work, and you are not going to test it)
- Personal Hotspots (Doesn't work on Early 2013 and earlier Macs, though there is a workaround)
- WPA2 Enterprise (same case as Personal Hotspots, except the workaround part)