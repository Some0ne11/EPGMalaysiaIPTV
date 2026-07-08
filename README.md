# Malaysia IPTV EPG

This repository provides a reliable, auto-updating Electronic Program Guide (EPG) in XML format for Malaysian IPTV channels. 

## 🔗 The EPG URL

To use this EPG in your IPTV player, copy the link below. 

**Use this URL:**
> `https://raw.githubusercontent.com/Some0ne11/EPGMalaysiaIPTV/refs/heads/main/epg.xml`

## ⚙️ How to Configure in Your IPTV Player

### For TiviMate (Android TV)
1. Open TiviMate and go to **Settings**.
2. Select **EPG** -> **EPG Sources**.
3. Click **Add source**.
4. Type or paste the jsDelivr URL provided above.
5. Go back to **Settings** -> **Playlists**, select your playlist, and ensure this new EPG source is assigned to it.
6. Return to the main EPG menu and click **Update EPG**.

### For Other Players (Generic Instructions)
1. Navigate to your app's **Settings** or **Playlist Management** section.
2. Look for an option labeled **XMLTV**, **EPG Source**, or **TV Guide**.
3. Add the jsDelivr URL as the source path.
4. Save and manually force an update if the app does not do it automatically.

---

## 🔄 How Updates Work
This `epg.xml` file is completely automated. It syncs regularly from a private server via GitHub Actions. You do not need to update your link or manually download anything—as long as your player uses the jsDelivr link above, it will automatically pull the latest TV guide data whenever it refreshes.
