# Yuyake Privacy Policy

Effective October 10, 2026

Yuyake is a local-first wallpaper app for macOS. No Yuyake account is required.

## Personal media

- Videos and photo slideshows are stored locally under Yuyake’s Application Support folder.
- Yuyake reads only files you explicitly select with Apple’s file picker.
- Yuyake does not request access to your Photos library.
- Selected photos are rendered into a local slideshow video. Yuyake also creates private,
  app-owned image copies so you can change slideshow timing and framing later. It does not
  retain file-provider bookmarks or links back to the originals.
- Yuyake does not upload personal videos, photos, or rendered slideshows.

Deleting a personal scene removes its rendered video and editable image copies from Yuyake’s library.

## Tracking and diagnostics

The Mac app contains no advertising, behavioral analytics, or crash-reporting SDKs. Yuyake does not sell personal information.

Help has two optional items. **Copy diagnostics** puts a short summary on your clipboard: app version and build, macOS version and build, Mac model, number of displays, lock screen status, and Yuyake’s own recent log lines. It contains no file paths, scene or media names, or location, and nothing is sent unless you paste it somewhere. **Send feedback…** opens a draft in your email app, addressed to support@pennowick.com, with that same summary in the body. You can read and edit it before you send, and nothing is sent unless you press Send.

## Network connections

These are all of Yuyake’s connections. Yuyake does not contact any other server on its own. Everything except update checks is tied to a feature you use.

- **Update checks (Sparkle):** Yuyake reads its update feed from `raw.githubusercontent.com` (GitHub). It checks when it launches, when the Mac wakes, when the app comes forward, and about once an hour, with a gap of at least 15 minutes between checks. You can turn automatic checks off in Settings. Yuyake always asks before installing, and sends no system profile. GitHub also serves the update download when you accept one.
- **Discover and Yuyake Picks:** search and catalog requests go to Yuyake’s own proxy at `yuyakeapi.pennowick.com`, which keeps Yuyake’s Pexels key off your Mac, and Yuyake asks that proxy whether Discover is switched on. Thumbnails, previews, and downloads load directly from Pexels’ servers, so Pexels and the network providers involved can see your IP address and those requests. Personal media is never included. Yuyake credits each creator, does not let you share Discover clips as files, and is not affiliated with or endorsed by Pexels.
- **Weather and daylight (optional):** if you allow location, the approximate coordinates are sent to Open-Meteo (`api.open-meteo.com`) to get local weather and sunrise and sunset times. Yuyake does not use Apple WeatherKit.
- **Place names (optional):** if you allow location, Apple’s geocoding service turns your coordinates into a city name. This request goes to Apple under Apple’s privacy terms.
- **Links you paste to import a video:** when you import a video from a link, Yuyake connects to whatever https host is in that link to download the file. That host sees your IP address and the request. Nothing else is sent.

Yuyake asks for location only when you choose Allow location. Your location is kept on this Mac (a last-known position and city, used for the travel signal and for sunrise and sunset). It is never sent to Yuyake’s own servers. Focus status, preferences, scene history, and other local context remain on the Mac.

GitHub (downloads and the update feed), website hosting, DNS, and security providers process ordinary network request data under their own policies.

## Permissions

Desktop wallpaper and photo slideshow creation do not require Full Disk Access. The optional lock-screen wallpaper feature requires Full Disk Access so Yuyake can manage Apple’s wallpaper files. macOS grants this permission broadly; Yuyake uses it only for wallpaper-related files and settings. You can revoke it at any time in System Settings.

## Retention and choices

Local data remains until you delete scenes or remove Yuyake’s Application Support data. Service-provider network logs follow each provider’s configured retention. You can use local wallpapers without Discover, weather context, or lock-screen access.

For privacy questions, email [support@pennowick.com](mailto:support@pennowick.com).

The canonical public policy lives at [pennowick.com/yuyake/privacy](https://pennowick.com/yuyake/privacy/). This file is the source copy; keep both in sync.
