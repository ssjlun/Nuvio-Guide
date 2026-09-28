## 1. Download AltServer
- Download and install [AltServer](https://altstore.io/#Downloads) (Classic Version) on your Mac or Windows PC. 
	- *(Windows users: You must install iTunes and iCloud directly from Apple's website, not from the Microsoft Store).*
## 2. Connect your iPhone
- Plug your iPhone into your computer using a USB cable. Unlock your phone and tap Trust This Computer when the prompt appears.
## 3. Install AltStore
- Launch AltServer on your computer. Click the AltServer icon in your menu bar (Mac) or system tray (Windows), select Install AltStore, and choose your connected iPhone. You will need to enter your Apple ID and password to digitally sign the app.
## 4. Trust AltStore and Enable Developer Mode
- Open your iPhone's Settings app. Navigate to General > VPN & Device Management. Under the "Developer App" section, tap your Apple ID email and select Trust.
- Go to Settings > Privacy & Security. Scroll to the bottom and tap Developer Mode. Toggle it on, and your phone will restart to apply the change.

![IOS Cert](../Attachments/IOS%20Cert.avif)

![IOS Dev Mode](../Attachments/IOS%20Dev%20Mode.avif)

## 5. Use No Computer Resign Method
- Go to the App Store, download [LocalDevVPN](https://apps.apple.com/us/app/localdevvpn/id6755608044), and turn it on.
- Open the AltStore app, go to settings and sign in using your icloud account. 
- Scroll down then enable remote altserver.
## 6. Add Nuvio Repo and Install Nuvio
- On Altstore, go to the Sources tab, click the + and paste this link to add the repo.
```
https://raw.githubusercontent.com/NuvioMedia/NuvioMobile/cmp-rewrite/store.json
```
- Nuvio should now be visible when you open the source previously added. Install Nuvio.
---
# Shortcuts Auto-Refresh
*If left alone, the app will automatically get revoked after 7 days unless you resign it before then. **You can get around this by using the Shortcuts app** to completely automate this process for you and keep Nuvio running smoothly on your phone without any real upkeeping—sometimes there can be a few hiccups.*
## 1. Create the shortcut
1. Turn Wi-Fi ON
2. Enable LocalDevVPN
3. Wait 3 Seconds
4. Refresh All Apps
5. Wait 3 Seconds
6. Disable LocalDevVPN
7. Show notification: "Refreshing done!"
## 2. Set up an Automation
1. Have the automation Run Immediately.
2. Run at 1 AM, Mon, Wed, and Fri. Weekly.
3. Set the "Do" to the shortcut we created in the previous step.
