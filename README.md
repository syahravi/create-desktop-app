# Create Desktop Apps
Which .AppImage, .sh, etc.

then...

Properties >> Permissions >> Program: Allow this file to run as rogram

# Sample desktop app
Save the file in “~/.local/share/applications” or "/usr/share/applications/"
`~/.local/share/applications/<application-name.desktop>`
   
**email.desktop**
`9` lines of code
```bash
[Desktop Entry]
Name=zohomail
Exec=/fake/zoho-mail-desktop-x64-v1.3.2.AppImage
Comment=Zoho Mail is a secure, ad-free, enterprise-ready business email suite with Calendar, Tasks, Notes, Bookmarks and Contacts.
Icon=/fake/mail-logo.png
Type=Application
Terminal=false
Encoding=UTF-8
Categories=Internet;
```
