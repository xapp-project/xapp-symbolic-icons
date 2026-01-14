
## xapp-symbolic-icons (XSI)

XSI is a set of symbolic icons.

It is used by the following projects:

 - XApp
 - Cinnamon
 - Linux Mint

All XSI icons are prefixed with "xsi-" and placed in /usr/share/icons/hicolor.

## Migrating from adwaita-icon-theme

Adwaita-icon-theme only supports GNOME. Adwaita icons can be removed, and have been removed, if they are not used by the GNOME project.

To develop GTK projects which work outside of GNOME (in Cinnamon, Xfce, MATE etc..) a reliable set of symbolic icons was needed. So XSI was started.

The XSI icon names loosely follow the Adwaita names.

To migrate an application which uses adwaita-icon-theme to XSI, run:

`xsi-replace-adwaita-symbolic`

## Licensing

This project contains icons derived from third-party works. The project as a
whole is distributed under the GNU Lesser General Public License version 3
(LGPLv3).

Original licenses for third-party materials are available in `LICENSES/`.

Detailed per-file licensing, authorship and attribution are available in
`debian/copyright`.

