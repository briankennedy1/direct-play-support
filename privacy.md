# Direct Play Privacy Policy

Last updated: May 9, 2026

Direct Play is an Apple TV app for browsing and playing media from a Plex server you configure.

## Data Stored On Your Device

Direct Play stores:

- Your Plex access token and any discovered Plex server access tokens in Keychain.
- A stable Direct Play client identifier in UserDefaults.
- Your configured Plex server URL in UserDefaults.

## Network Connections

Direct Play connects to:

- The Plex server URL you configure, to browse and play your media library.
- `plex.tv`, during Plex link-code sign-in.
- `api.tvmaze.com`, to resolve the original platform/network for a show title when Plex metadata does not already provide it.
- `logo.clearbit.com`, to load network/studio logos for known attribution names.

During playback, Direct Play reports playback timeline state to your configured Plex server so resume and watched status can update.

## Media Library Data

Direct Play reads metadata from your configured Plex server, including show, season, episode, artwork, file, codec, duration, resume, and playback metadata.

Direct Play does not upload your media files. It sends Plex library requests to the Plex server you choose, may send a show title to TVmaze to resolve original-platform metadata, and may request a logo image from Clearbit using a known network or studio domain. It does not send your Plex token to TVmaze or Clearbit, and saved server preferences do not include Plex access tokens.

## Tracking And Advertising

Direct Play does not include third-party analytics, advertising, or tracking SDKs.

Direct Play does not sell personal information.

## Media Content

Direct Play does not provide, host, sell, or index movies, TV shows, live channels, or other media content. You are responsible for using Direct Play only with media you own or have permission to access.

## Contact

Privacy contact: [open an issue on the Direct Play support repo](https://github.com/briankennedy1/direct-play-support/issues).

Direct Play is not affiliated with, endorsed by, or sponsored by Plex.
