# Changelog

## 28.9-ls149
- web UI improvements:
- display lyrics metadata
- toggle Spotify on/off in some views
- many minor improvements
- use compressed ALAC for Airplay for bandwidth + fixes esp32 issue
- don't merge Spotify albums with local albums
- handle playlist with Unicode BOM
- json API add tracks to queue returns info on added tracks
- replace syscall with gettid, syscall deprecated on MacOS
- fix issue where m3u genre doesn't override despite m3u_override = true
- fix possible crash from use-after-free
- fix FreeBSD possible crash
- fix crash when keys of incorrect length are used for legacy pairing

## 28.4-ls92-beta-2

- Implement reconnect for Airplay configuration

## 28.4-ls92-beta-1

- Support latest home assistant version
- change to OwnTone version 28.4-ls92
- fixes http/http issues with ingress
