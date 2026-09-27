1. Download the latest macOS DMG installer from [GitHub](https://github.com/NuvioMedia/NuvioDesktop/releases).
2. Leave the DMG in your Downloads folder.
3. Do not open the DMG or drag Nuvio.app into Applications. The script handles both parts for you.
4. Press Cmd+Space, search for and open Terminal.
5. Paste this command and press Return:
```
curl -fsSL https://raw.githubusercontent.com/amackarrey/nuvioadhocsigner/main/resign_nuvio.sh -o "$HOME/Downloads/install_nuvio.sh" && bash "$HOME/Downloads/install_nuvio.sh"
```
6. You should now be able to open Nuvio from your applications.