# AutoHub KingInstaller

Modified version of **KingInstaller 2.5** by fcaronte (https://github.com/fcaronte/KingInstaller,
commit 87446cb "bump a v2.5 (versionCode 12)"), distributed under the GNU General Public License v3.0 (see LICENSE).

Changes made by Zicspanico for AutoHub (2026-11-11):
- removed the automatic update check at start-up and hid the "check for updates" menu item
  (the AutoHub Connect Parking app delivers this installer);
- application ID `it.autohub.kinginstaller`, name "AutoHub KingInstaller", so it can coexist with the original;
- no signing configuration in the build (the APK is signed separately); release lint check disabled.

The installation methods (Classic, Shizuku, Root) are unchanged.
