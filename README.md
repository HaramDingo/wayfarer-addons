# wayfarer-addons

This is a collection of plugins with the Wayfarer Review website which augment the experience in various ways. 
Each plugin will work independently or along side the rest so users can customize their Wayfarer experience.

For feedback, help, or any other conversation about these scripts please join the [Wayfarer Discussion Discord](https://discord.gg/DvDCRXcvxG) -> #tools-chat channel. 

[Tampermonkey](https://tampermonkey.net/) is required in order to install these plugins, then each can be installed via the link below.

# Keyboard Review
[Install](https://github.com/tehstone/wayfarer-addons/raw/main/wayfarer-keyboard-review.user.js)

This plugin enables nearly full control of the review page via the keyboard.

- Numbers 1-5 to select a rating for the selected category
- Left & Right arrows to navigate between categories
- Enter key to submit the nomination (will select the Smart Submit option of the Review Timer script is installed).
- Numbers within Rejection Dialog to navigate the reject reason menu
- Backspace within Rejection Dialog to navigate back a level in the reject reason menu
- When the text box in the Rejection Dialog is focused, Shift+Enter will add a newline, Enter will submit the nomination
- Whenever the submit button is active, Ctrl+Enter will select the "Submit and finish reviewing" option
- "D" to mark the selected nomination as a duplicate
- "Q" to open the main photo
- "E" to open the supporting photo
- "R" & "F" to zoom in and out of the map
- If the Location Accuracy rating is focused, "Escape" will exit street view
- Number keys to select Edit options
- Letter keys to select photo options

# Review Timer with Smart Submit
[Install](https://github.com/tehstone/wayfarer-addons/raw/main/wayfarer-review-timer.user.js)

Adds a timer to the top of the page indicating the time remaining to review the current nomination.

Adds a Smart Submit button that will wait to submit the nomination until a certain amount of time has elapsed. The minimum and maximum wait times are configurable and a random value between the min and max will be selected each time the button is pressed. The nomination will be submitted once that amount of time has elapsed on the timer.

Smart Submit button can be disabled if desired, a toggle for the button as well as the min and max delays mentioned previously are all found within a new settings panel at the bottom of the review page.

# Extended Stats
[Install](https://github.com/tehstone/wayfarer-addons/raw/main/wayfarer-extended-stats.user.js)

- Adds total agreement count and percentage to the Profile Page
- Includes settings to indicate whether agreements should be calculated from the Badge Stat in Pokemon GO or based on Upgrade Count
- Includes settings for current Badge Count and Bonus Upgrades Earned count

# Review History
[Install](https://github.com/tehstone/wayfarer-addons/raw/main/wayfarer-review-history.user.js)

- Stores review history in 3 separate datasets for New Nominations, Edit Nominations, and Photo Reviews per user
- Includes Export and Remove options
- Currently there is no visualizer for this data

# Nomination Map 
[Install](https://github.com/tehstone/wayfarer-addons/raw/main/wayfarer-nomination-map.user.js)

Places a map of all player nominations at the top of the Nominations Page

# Nomination Streetview
[Install](https://github.com/tehstone/wayfarer-addons/raw/main/wayfarer-nomination-streetview.user.js)

Adds a Streetview panel to the selected nomination, also makes the Nomination Title a link to intel and adds click-to-copy GPS coordinates to the location.

# Nomination Stats
[Install](https://github.com/tehstone/wayfarer-addons/raw/main/wayfarer-nomination-stats.user.js)

Basic stats about nominations. Export in JSON or CSV for all nominations.

# Open In
[Install](https://github.com/tehstone/wayfarer-addons/raw/main/wayfarer-open-in.user.js)

Adds direct links to external map providers wherever maps are displayed in Wayfarer. The following providers are supported globally:

- Google Maps
- OpenStreetMap
- Ingress Intel
- Bing Maps
- Yandex.Maps

In addition to these providers, the plugin adds support for 29 regional map providers across 28 countries. Depending on the location of the wayspot, you may also see some of these map providers, many of which offer very high quality features such as high-resolution aerial imagery, property boundaries or street view:

<details>
    <summary>List of regional map providers</summary>

- 🇦🇺 **Australia:** NSW Imagery (NSW only)
- 🇦🇽 **Åland Islands:** Maanmittauslaitos, Paikkatietoikkuna
- 🇧🇪 **Belgium:** NGI/IGN
- 🇧🇱 **Saint Barthélemy:** Mappy
- 🇨🇭 **Switzerland:** Admin.ch
- 🇨🇿 **Czech Republic:** Mapy.cz
- 🇩🇰 **Denmark:** Find vej, Krak, SDFE Skråfoto
- 🇫🇮 **Finland:** Maanmittauslaitos, Paikkatietoikkuna
- 🇫🇴 **Faroe Islands:** Flogmyndir, Føroyakort
- 🇫🇷 **France:** Mappy
- 🇬🇫 **French Guiana:** Mappy
- 🇩🇪 **Germany:** BayernAtlas (Bavaria only), FIS-Broker (Berlin only), GeoPortal Bremen (Bremen only), Hamburg Geo-Online (Bremen, Hamburg, and Schleswig-Holstein only), Geoportal der Metropolregion Hamburg (Bremen and Hamburg only), GeobasisdatenViewer Niedersachsen (Lower Saxony only), GAIA-MV (Mecklenburg-Western Pomerania only), ORKa.MV (Mecklenburg-Western Pomerania only), GeoBasisViewer RLP (Rhineland-Palatinate only), Thüringen Viewer (Thuringia only)
- 🇬🇵 **Guadeloupe:** Mappy
- 🇮🇸 **Iceland:** Já.is Götusýn, Landupplýsingagátt LMÍ, Map.is, Samsýn
- 🇰🇷 **South Korea:** Kakao, Naver
- 🇱🇮 **Liechtenstein:** Geodatenportal der LLV
- 🇱🇺 **Luxembourg:** Geoportal Luxembourg
- 🇲🇫 **Saint Martin:** Mappy
- 🇲🇶 **Martinique:** Mappy
- 🇳🇱 **Netherlands:** Kaarten van Nederland, Map5 NLTopo
- 🇳🇴 **Norway:** Gule Sider, Kommunekart, Norge i bilder, Norgeskart, UT.no
- 🇵🇱 **Poland:** Geoportal
- 🇵🇲 **Saint Pierre and Miquelon:** Mappy
- 🇷🇪 **Réunion:** Mappy
- 🇸🇪 **Sweden:** Eniro, Lantmäteriet
- 🇸🇯 **Svalbard and Jan Mayen:** TopoSvalbard (Svalbard only)
- 🇸🇰 **Slovakia:** Mapy.cz
- 🇸🇽 **Sint Maarten:** Mappy
- 🇼🇫 **Wallis and Futuna:** Mappy
- 🇾🇹 **Mayotte:** Mappy

</details>

These are automatically made available to you in each respective region.

# Review Counter
[Install](https://github.com/tehstone/wayfarer-addons/raw/main/wayfarer-review-counter.user.js)

Adds a counter to the top of the page which increments for each review completed during the current session.

# Upgrade Percentage
[Install](https://github.com/tehstone/wayfarer-addons/raw/main/wayfarer-upgrade-percent.user.js)

Adds a percentage next to the user icon for current upgrade progress. Click on the number to refresh it (use with care, this creates abnormal requests to the Wayfarer site that may appear suspicious to Niantic).

# Legal Stuff
Significant portions of the code within each of the `.user.js` script files in this repository were copied and modified from [Wayfarer+](https://github.com/MrJPGames/WayFarerPlus) and [Wayfarer-Toolkit](https://github.com/AlterTobi/WayFarer-Toolkit). Note that the toolkit code was originally authored by [MrJPGames](https://github.com/MrJPGames) but their repository was removed or made private so this link is to a fork which may no longer match the original code.

Modifications include but are not limited to: rearranging code in order to package similar features together in single scripts, adding additional functionality, removing portions which no longer apply to the updated Wayfarer website.
