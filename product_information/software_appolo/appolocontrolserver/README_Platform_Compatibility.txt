================================================================
PLEASE READ: Important information about platform compatibility.

This information applies to RCT5030 platforms with build label
XBOARD_130 or older. If your platform is a RCT5030 and has a build
label of RCT5030_130 or older, please read this to the end.

NOTE: You can find the platform build label of your RCT5030 on the
      "System settings" page on the Web-Interface of your RCT5030.
      (see RCT5030 manual, section "Controller Configuration")

----------------
If you want to install any of the LYNXEmbedded packages above RELEASE
2.6.4 onto a RCT5030 platform with build label XBOARD_130 or older,
then you need to make sure that RELEASE 2.6.4 is installed before
doing so.

1) if not already done: download RELEASE 2.6.4
   (LynxEmbedded.20641420.RELEASE_2.6.4.tgz.nc) from
   ftp://lynx-technik.com/embedded and install it into your RCT5030.
   (see RCT5030 manual for detailed instructions)

2) make sure RELEASE 2.6.4 (or any version above this) is currently
   activated. 

3) now you can download and install any current version from the 
   same FTP server and activate it.

----------------
Background:

The special RELEASE 2.6.4 contains a lot of data that upgrades the
platform to Extension level #1. (You may have noticed that the 2.6.4
package has a significanlty larger size than all other packages.)

Extension #1 is a required platform extension for any version above
2.6.4. In other words, software releases above 2.6.4 cannot be
installed and run on a platform that does not have extension #1
installed.

Platforms that have a label *higher* than RCT5030_130 do not need this
extension to be explicitly installed. They have the relevant data
pre-installed.

----------------

(end of file)

