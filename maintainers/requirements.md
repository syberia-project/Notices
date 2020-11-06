**Required skills**
===================

  * The maintainer must own the device and do all their own testing. Blind and untested builds aren't allowed.

  * The maintainer must have an account on Github, Gerrit and SourceForge.

  * The maintainer must know how to use Gerrit correctly: pushing commits, rebasing commits, reviewing commits etc.

  * The maintainer must know how to use Git correctly: amending commits, rebasing commits, cloning repos, pushing commits/repos, merging and pulling commits accordingly.

  * The maintainer must display proper authorship and commit history in all non-original commits that are pulled from other sources.
	
  * The maintainer must be able to troubleshoot platform specific issues (reading logcats).

  * The maintainer must write clear commit messages. "Fix derp", "Fix#1" etc aren't allowed.

  * The maintainer must release updated builds at least once every 2 weeks. If there is a valid reason, updated builds can be released once a month, but not less often. The maintainer must inform the team administration in the Telegram group about these reasons. Otherwise, the maintainer may be kicked from the team without warning.

  * The maintainer must create and maintain an unofficial build on [XDA](https://forum.xda-developers.com/) for at least a month.
	
  * The maintainer must be a member of the [Telegram support group](https://t.me/SyberiaOSHelpdesk). 


**Device requirements**
=======================

  * The device tree must be buildable.
	
  * The device tree must have only open source dependencies.
	
  * It is preferable that the device has a selinux enforcing to release builds. However, this is discussed individually with each candidate.

  * The device tree must not include any unused overlays. For example placebo build.prop 'tweaks'.

  * The device must have working functions:

    - audio (in-call audio, speaker phone, headphone jack and bluetooth audio).

    - phone calls and data (phone calls, download files from the internet, use different sim slots if applicable).

    - hotspot if supported by device (WiFi and USB tethering).

    - camera (if you are using a third party camera app in your builds, this should be fully functional).

    - fingerprint scanner if supported by device.

    - NFC if supported by device

    - proximity sensor.

    - bluetooth.

    - WiFi.
