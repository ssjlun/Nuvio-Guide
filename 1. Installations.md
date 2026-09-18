## Windows Installation
1. Download the installer. Grab the latest .msi installer from the official GitHub releases.
2. Launch the setup. Double-click the downloaded file to run the installer.
3. Follow the on-screen setup prompts.Grant permissions. When the prompt appears asking for permission, click Yes to allow the installation.
4. Click Finish to complete the setup and launch Nuvio. (Click More info and then Run anyway to proceed safely if you get a warning).
## MacOS Installation
1. Download the latest macOS DMG installer from GitHub.
2. Leave the DMG in your Downloads folder.
3. Do not open the DMG or drag Nuvio.app into Applications. The script handles both parts for you.
4. Press Cmd+Space, search for and open Terminal.
5. Paste this command and press Return:
```
curl -fsSL https://raw.githubusercontent.com/amackarrey/nuvioadhocsigner/main/resign_nuvio.sh -o "$HOME/Downloads/install_nuvio.sh" && bash "$HOME/Downloads/install_nuvio.sh"
```
6. You should now be able to open Nuvio from your applications.
## IOS Installation
1. Download and install AltServer on your Mac or Windows PC. (Windows users: You must install iTunes and iCloud directly from Apple's website, not from the Microsoft Store).
2. Plug your iPhone into your computer using a USB cable. Unlock your phone and tap Trust This Computer when the prompt appears.
3. Launch AltServer on your computer. Click the AltServer icon in your menu bar (Mac) or system tray (Windows), select Install AltStore, and choose your connected iPhone. You will need to enter your Apple ID and password to digitally sign the app.
4. Open your iPhone's Settings app. Navigate to General > VPN & Device Management. Under the "Developer App" section, tap your Apple ID email and select Trust.
5. Go to Settings > Privacy & Security. Scroll to the bottom and tap Developer Mode. Toggle it on, and your phone will restart to apply the change.
6. Go to the App Store, download LocalDevVPN, and turn it on.
7. Open the Altstore app, go to settings and sign in using your icloud account. Scroll down then enable remote altserver.
8. On Altstore, go to Sources tab, click the + and paste this link to add the repo.
```
https://raw.githubusercontent.com/NuvioMedia/NuvioMobile/cmp-rewrite/store.json
```
9. Nuvio should now be visible when you open the source we added. 
10. Install Nuvio.
### Shortcuts Auto-Refresh