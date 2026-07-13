# Malaysia IPTV EPG

This repository provides a reliable, auto-updating Electronic Program Guide (EPG) in XML format for Malaysian IPTV channels. 

## 🔗 The EPG URL

To use this EPG in your IPTV player, copy the link below. 

**Use this URL:**
> `https://cdn.jsdelivr.net/gh/Some0ne11/EPGMalaysiaIPTV@main/epg.xml`

⚠️ **Important Note:** Do **not** use the `raw.githubusercontent.com` link. GitHub strictly limits raw file downloads. If too many users refresh at the same time, GitHub will block the connection (Error 503). The `jsdelivr` link above routes through a global CDN designed for high traffic and will not get blocked.

---

## 📺 Supported Channels & `tvg-id` Reference

To make sure your TV guide populates correctly, the `tvg-id` tag inside your `.m3u` file **must exactly match** the XML IDs used by this guide.

<details>
<summary><b>Click to expand/collapse the full channel list</b></summary>

| Channel Name | XML `tvg-id` |
| :--- | :--- |
| TV1 | `TV1.my` |
| TV2 | `TV2.my` |
| TV3 | `TV3.my` |
| NTV7 | `NTV7.my` |
| 8TV | `8TV.my` |
| TV9 | `TV9.my` |
| TV Alhijrah | `TVAlhijrah.my` |
| Astro Ria | `AstroRia.my` |
| Astro Prima | `AstroPrima.my` |
| Astro Arena | `AstroArena.my` |
| Astro Awani | `AstroAwani.my` |
| RTM Sports | `RTMSports.my` |
| Awesome TV | `AwesomeTV.my` |
| Suke TV | `SukeTV.my` |

</details>

*(Note: If you are looking for a specific channel not listed here, please open an Issue to request it.)*

---

## 🛠️ How to Match `tvg-id` in Your M3U Playlist

If your IPTV player shows "No Information" or blank guide slots, it means your `.m3u` playlist is using different names than this EPG file. You can fix this by editing your `.m3u` file in a text editor (like Notepad++ or VS Code).

### The Standard Formatting Rule
Locate the `#EXTINF` line for the channel you want to map and update the `tvg-id` attribute. 

**Example Structure:**
```m3u
#EXTINF:-1 tvg-id="XML_ID_HERE" tvg-name="TV_NAME" tvg-logo="LOGO_URL", Channel Name
http://your-iptv-stream-url.com/live.m3u8
```

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

---

## ⚖️ Disclaimer & Policy
- 100% Free: This repository and the generated EPG data are strictly not for sale. This is a free project meant for personal use. If someone tried to sell you access to this URL, you have been scammed.

- No Modifications: Redistribution or modifications of the code/files from this repository are not allowed.

- Contributions & Requests: Pull Requests (PRs) are not accepted for this repository. If you want to report a broken channel, request a new channel addition, or report an issue, please open an Issue instead.
