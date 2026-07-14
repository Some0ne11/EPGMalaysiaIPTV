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

<table>
  <thead>
    <tr>
      <th>Channel Name</th>
      <th>XML <code>tvg-id</code></th>
    </tr>
  </thead>
  <tbody>
    <tr><td>Inspirasi</td><td><code>Inspirasi</code></td></tr>
    <tr><td>Sensasi</td><td><code>Sensasi</code></td></tr>
    <tr><td>DEGUP</td><td><code>DEGUP</code></td></tr>
    <tr><td>TV1</td><td><code>TV1</code></td></tr>
    <tr><td>TV2</td><td><code>TV2</code></td></tr>
    <tr><td>TV3</td><td><code>TV3</code></td></tr>
    <tr><td>Didik TV KPM</td><td><code>DidikTVKPM</code></td></tr>
    <tr><td>8TV</td><td><code>8TV</code></td></tr>
    <tr><td>TV9</td><td><code>TV9</code></td></tr>
    <tr><td>Salam HD</td><td><code>Salam</code></td></tr>
    <tr><td>TV AlHijrah HD</td><td><code>AlHijrah</code></td></tr>
    <tr><td>SIAR</td><td><code>SIAR</code></td></tr>
    <tr><td>TV Sarawak</td><td><code>TVSarawak</code></td></tr>
    <tr><td>Dunia Sinema HD</td><td><code>DuniaSinema</code></td></tr>
    <tr><td>PESONA</td><td><code>PESONA</code></td></tr>
    <tr><td>tvN Movies HD</td><td><code>tvNMovies</code></td></tr>
    <tr><td>tvN HD</td><td><code>tvN</code></td></tr>
    <tr><td>TVB Jade</td><td><code>TVBJade</code></td></tr>
    <tr><td>CCTV4</td><td><code>CCTV4</code></td></tr>
    <tr><td>Phoenix Hong Kong Channel</td><td><code>PhoenixChineseChannel</code></td></tr>
    <tr><td>SETI</td><td><code>SETI</code></td></tr>
    <tr><td>Celestial Movies</td><td><code>CelestialMovies</code></td></tr>
    <tr><td>Celestial Classic Movies</td><td><code>CelestialClassicMovies</code></td></tr>
    <tr><td>Zee Thirai</td><td><code>ZeeThirai</code></td></tr>
    <tr><td>Sony YAY!</td><td><code>SonyYAY</code></td></tr>
    <tr><td>Zee Cinema HD</td><td><code>ZeeCinema</code></td></tr>
    <tr><td>HBO</td><td><code>HBO</code></td></tr>
    <tr><td>HBO Hits</td><td><code>HBOHits</code></td></tr>
    <tr><td>HBO Family</td><td><code>HBOFamily</code></td></tr>
    <tr><td>Cinemax</td><td><code>Cinemax</code></td></tr>
    <tr><td>HITS Movies</td><td><code>HITSMovies</code></td></tr>
    <tr><td>Warner TV HD</td><td><code>WarnerTV</code></td></tr>
    <tr><td>HITS NOW</td><td><code>HITSNow</code></td></tr>
    <tr><td>AXN</td><td><code>AXN</code></td></tr>
    <tr><td>HITS</td><td><code>HITS</code></td></tr>
    <tr><td>K Plus</td><td><code>K-Plus</code></td></tr>
    <tr><td>Animax</td><td><code>Animax</code></td></tr>
    <tr><td>ROCK Entertainment HD</td><td><code>ROCKEntertainment</code></td></tr>
    <tr><td>Rock Action HD</td><td><code>RockAction</code></td></tr>
    <tr><td>BBC Earth HD</td><td><code>BBCEarth</code></td></tr>
    <tr><td>Love Nature HD</td><td><code>LoveNature</code></td></tr>
    <tr><td>HGTV</td><td><code>HGTV</code></td></tr>
    <tr><td>BBC Lifestyle HD</td><td><code>BBCLifestyle</code></td></tr>
    <tr><td>Asian Food Network</td><td><code>AsianFoodNetwork</code></td></tr>
    <tr><td>DreamWorks HD</td><td><code>DreamWorks</code></td></tr>
    <tr><td>Moonbug Kids</td><td><code>MoonbugKids</code></td></tr>
    <tr><td>Nick Jr.</td><td><code>NickJr</code></td></tr>
    <tr><td>Cbeebies HD</td><td><code>Cbeebies</code></td></tr>
    <tr><td>Nickelodeon</td><td><code>Nickelodeon</code></td></tr>
    <tr><td>Cartoon Network</td><td><code>CartoonNetwork</code></td></tr>
    <tr><td>BBC World News HD</td><td><code>BBCWorldNews</code></td></tr>
    <tr><td>Al Jazeera</td><td><code>AlJazeera</code></td></tr>
    <tr><td>CGTN</td><td><code>CGTN</code></td></tr>
    <tr><td>CNA</td><td><code>CNA</code></td></tr>
    <tr><td>Euronews</td><td><code>Euronews</code></td></tr>
    <tr><td>Bernama TV</td><td><code>BernamaTV</code></td></tr>
    <tr><td>Parlimen Malaysia</td><td><code>ParlimenMalaysia</code></td></tr>
    <tr><td>ABC Australia</td><td><code>ABCAustralia</code></td></tr>
    <tr><td>DW</td><td><code>DW</code></td></tr>
    <tr><td>NHK WORLD JAPAN</td><td><code>NHKWorldJapan</code></td></tr>
    <tr><td>Unifi Sports 1</td><td><code>UnifiSports1</code></td></tr>
    <tr><td>SPOTV</td><td><code>SPOTV</code></td></tr>
    <tr><td>SPOTV2</td><td><code>SPOTV2</code></td></tr>
    <tr><td>beIN SPORTS 1</td><td><code>beINSports1</code></td></tr>
    <tr><td>beIN SPORTS 2</td><td><code>beINSports2</code></td></tr>
    <tr><td>beIN SPORTS 3</td><td><code>beINSports3</code></td></tr>
    <tr><td>beIN SPORTS 4</td><td><code>beINSports4</code></td></tr>
    <tr><td>KBS World HD</td><td><code>KBSWorld</code></td></tr>
    <tr><td>iQIYI HD</td><td><code>iQIYI</code></td></tr>
    <tr><td>Rock X Stream</td><td><code>RockXStream</code></td></tr>
    <tr><td>Astro Showcase</td><td><code>AstroShowcase</code></td></tr>
    <tr><td>Crime &amp; Investigation HD</td><td><code>CrimeInvestigation</code></td></tr>
    <tr><td>Lifetime HD</td><td><code>Lifetime</code></td></tr>
    <tr><td>History HD</td><td><code>History</code></td></tr>
    <tr><td>Discovery Channel HD</td><td><code>DiscoveryChannel</code></td></tr>
    <tr><td>Discovery Asia HD</td><td><code>DiscoveryAsia</code></td></tr>
    <tr><td>TLC HD</td><td><code>TLC</code></td></tr>
    <tr><td>ROLL</td><td><code>ROLL</code></td></tr>
    <tr><td>Lead</td><td><code>Lead</code></td></tr>
    <tr><td>JR.</td><td><code>JR.</code></td></tr>
    <tr><td>Snap</td><td><code>Snap</code></td></tr>
    <tr><td>Apetito</td><td><code>Apetito</code></td></tr>
    <tr><td>Aura</td><td><code>Aura</code></td></tr>
    <tr><td>Fitrah</td><td><code>Fitrah</code></td></tr>
  </tbody>
</table>

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
