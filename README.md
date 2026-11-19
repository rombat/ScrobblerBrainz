# ScrobblerBrainz
A MusicBee plug-in to scrobble tracks to ListenBrainz.

> **This is a maintained fork of [karaluh/ScrobblerBrainz](https://github.com/karaluh/ScrobblerBrainz)**, which hasn't been updated since 2024.
> Version 2.0.2 fixes:
> - ListenBrainz blocking the plugin (and your IP) because it sent no User-Agent ([#24](https://github.com/karaluh/ScrobblerBrainz/issues/24)).
> - Listens getting the MusicBrainz IDs of another track, or none ([#25](https://github.com/karaluh/ScrobblerBrainz/issues/25)).
> - The first listen after MusicBee starts being rejected by ListenBrainz.
> - Listens being rejected by ListenBrainz because of a malformed MusicBrainz ID tag.
>
> Still on 1.x? Versions before 2.0.0 never send MusicBrainz IDs, so ListenBrainz has to guess which recording you played. Upgrade to link your listens to your tags.

# Restrictions
1. Scrobbles tracks shorter than 30 s. (last.fm scrobbler doesn't do this).
1. No loved tracks/playcount sync.
1. Doesn't scrobble tracks played on portable devices.
1. No feature to disable podcast scrobbling.

# Download
https://github.com/rombat/ScrobblerBrainz/releases/latest/download/mb_ScrobblerBrainz.zip

# Usage
1. Get MusicBee https://getmusicbee.com/downloads/
1. Get MusicBrainz account https://musicbrainz.org/register?uri=%2F
1. Get ListenBrainz account https://listenbrainz.org/login/
1. Download the plugin
1. Open MusicBee and go to *Edit->Edit preferences->Plugins*
1. Press the *Add plugin...* button
1. Choose the downloadwd file and press *Open*
1. Get your ListenBrainz user token https://listenbrainz.org/profile/
1. Input your user token into the toolbox
1. Save the settings and you're good to go
