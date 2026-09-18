## Disable Cinemeta
1. On Nuvio, Open Settings>General>Content & Discovery>Addons 
2. Delete the addon named Cinemeta.
## TorBox Signup
- Create an account for TorBox and sign up for a $3/month subscription. (You will get an API key that is needed for AIOStreams)
## Additional API Keys (Required)
1. Create accounts for TMDb, TVDb, and Mdblist. **SAVE LOGINS FOR EACH**
2. Then Request an API for each—you will need these API keys for AIOMetadata.
### TMDb
### TVDb
### Mdblist
## AIOStreams
1. Skip any presets it suggests and use a custom setup—set it up myself. 
2. On the left first go to Save & Install to create a configuration. Make a password for it to create it (save this too). 
3. Then go down to where you see import and use the file below to import my settings/filters. 
4. On the left, click the Services tab. Select TorBox and put in your API key and click save.(make sure it is toggled on). 
5. Go back to the Save & Install tab on the left and click save. 
6. There should be a manifest json URL, copy it and go back to Nuvio. 
7. Open Settings>General>Content & Discovery>Addons 
8. Paste the manifest json URL and click add addon. You should now see a new add-on named AIOStreams.
## AIOMetadata
1. Skip any presets it suggests and use a custom setup—there should be a skip button.
2. On the left first go to the Configuration tab to create a configuration. Make a password for it to create it (I recommend using the same as AIOStreams).
3. Then go down to where you see import configuration and use the file below to import my settings.
4. Then on the left go to the Integrations tab, and paste in your API keys for TMDb and TVDb. Test your keys and make sure they both have a green check mark.
5. Go to the Catalogs tab on the left, and click the little logo for Simkl (small s) to link your Simkl account.
6. Click the Art Providers tab on the left, visit BetterPosters.
	1. Click Get Started. Then click AIOMetadata/Other Addon.
	2. Scroll down and copy the URL.
7. Head back to AIOMetadata and paste this URL in the bottom of the Art Providers tab, where it says Poster URL Pattern—replace existing if there is one.
8. Go back to the Configuration tab on the left and click save configuration.
9. There should be a manifest json URL, copy it and go back to Nuvio.
10. Open Settings>General>Content & Discovery>Addons 
11. Paste the manifest json URL and click add addon. You should now see a new add-on named AIOMetadata.
## PenguPlay (Optional, backup)
1. Connect your google account.
2. Click copy addon URL, and go back to Nuvio.
3. Open Settings>General>Content & Discovery>Addons
4. Paste the manifest json URL and click add addon.
