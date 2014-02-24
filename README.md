MagicKeys
=========

This is a preference pane for Mac OS X 10.7+ that enables hardware media keys (prev, play, next) to be routed to 3rd-party sandboxed applications in a nice way, without unwanted side effects.

Although the prefpane was originally developed to complement G-Ear (see http://www.treasurebox.hu), it should work well with other applications, file a bug report (or even better, a pull request) if not. It can also launch a specified app on demand.

When the routing is enabled via the prefpane, a background is launched to do the actual work. It shouldn’t have any noticeable impact on performance, as it registers for Quartz “Event Taps”.

After uninstalling, a small (approx. 100byes) file is left at ~/Library/Preferences/com.treasurebox.magickeys.plist for eventual future use. Apart from that, no permanent change is left on the system (the launch services entry which facilitates automatic start of the background process is invalidated by the system).  

A screenshot is available at http://treasurebox-gear.s3.amazonaws.com/magickeys.png
