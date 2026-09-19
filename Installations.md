## Windows Installation
1. Download the installer. Grab the latest .msi installer from the official [GitHub releases](https://github.com/NuvioMedia/NuvioDesktop/releases).
2. Launch the setup. Double-click the downloaded file to run the installer.
3. Follow the on-screen setup prompts to grant permissions. When the prompt appears asking for permission, click Yes to allow the installation.
4. Click Finish to complete the setup and launch Nuvio. (Click More info and then Run anyway to proceed safely if you get a warning).
## MacOS Installation
1. Download the latest macOS DMG installer from [GitHub](https://github.com/NuvioMedia/NuvioDesktop/releases).
2. Leave the DMG in your Downloads folder.
3. Do not open the DMG or drag Nuvio.app into Applications. The script handles both parts for you.
4. Press Cmd+Space, search for and open Terminal.
5. Paste this command and press Return:
```
curl -fsSL https://raw.githubusercontent.com/amackarrey/nuvioadhocsigner/main/resign_nuvio.sh -o "$HOME/Downloads/install_nuvio.sh" && bash "$HOME/Downloads/install_nuvio.sh"
```
6. You should now be able to open Nuvio from your applications.
## IOS Installation (AltStore Classic)
1. Download and install [AltServer](https://altstore.io/#Downloads) (Classic Version) on your Mac or Windows PC. 
	1. *(Windows users: You must install iTunes and iCloud directly from Apple's website, not from the Microsoft Store).*
2. Plug your iPhone into your computer using a USB cable. Unlock your phone and tap Trust This Computer when the prompt appears.
3. Launch AltServer on your computer. Click the AltServer icon in your menu bar (Mac) or system tray (Windows), select Install AltStore, and choose your connected iPhone. You will need to enter your Apple ID and password to digitally sign the app.
4. Open your iPhone's Settings app. Navigate to General > VPN & Device Management. Under the "Developer App" section, tap your Apple ID email and select Trust.

![IOS Cert](Attachments/IOS%20Cert.avif)

5. Go to Settings > Privacy & Security. Scroll to the bottom and tap Developer Mode. Toggle it on, and your phone will restart to apply the change.

![IOS Dev Mode](Attachments/IOS%20Dev%20Mode.avif)

6. Go to the App Store, download [LocalDevVPN](https://apps.apple.com/us/app/localdevvpn/id6755608044), and turn it on.
7. Open the AltStore app, go to settings and sign in using your icloud account. Scroll down then enable remote altserver.

![AltStore 1](Attachments/AltStore%201.avif)
![AltStore 2](Attachments/AltStore%202.avif)
![AltStore 3](Attachments/AltStore%203.avif)
![AltStore 4](Attachments/AltStore%204.avif)

8. On Altstore, go to the Sources tab, click the + and paste this link to add the repo.
```
https://raw.githubusercontent.com/NuvioMedia/NuvioMobile/cmp-rewrite/store.json
```
9. Nuvio should now be visible when you open the source previously added. 
10. Install Nuvio.
### Shortcuts Auto-Refresh
*If left alone, the app will automatically get revoked after 7 days unless you resign it before then. **You can get around this by using the Shortcuts app** to completely automate this process for you and keep Nuvio running smoothly on your phone without any real upkeeping—sometimes there can be a few hiccups.*
1. Create a shortcut that will actually be refreshing your apps:
	1. Turn Wi-Fi ON
	2. Enable LocalDevVPN
	3. Wait 3 Seconds
	4. Refresh All Apps
	5. Wait 3 Seconds
	6. Disable LocalDevVPN
	7. Show notification: "Refreshing done!"

![Shortcuts 1](Attachments/Shortcuts%201.png)

3.  Set up an automation that will run your shortcut for you without any input:
	1. Have the automation Run Immediately.
	2. Run at 1 AM, Mon, Wed, and Fri. Weekly.
	3. Set the shortcut we created in the previous step.

![Shortcuts 2](Attachments/Shortcuts%202.png)
