## Super Fork v1

- Bump version to v1 (versionCode 1000)
- Add TSUpport Advanced option
- Update README badges & links to point at frpunlocking-com/PlayIntegritySuperFork
- Rename module to "Play Integrity Super Fork" and extend (confirmed) supported Android range from <A13 to A16
- Update update.json with correct zipUrl and changelog

## Custom Fork v13

- Improve Action on KSU/APatch, KSU-Next, MMRL
- Improve autopif2 to ignore Preview builds by default
- Remove unnecessary adb props spoof
- Add all known opt-out props for PPU/PIH variants/hybrids
- Add new verified boot error props deletion
- Update killgms to killpi by adding vending
- Improve autopif2 to populate TS's optional security_patch.txt
- Improve ROM overlay xml disabling support
- Improve autopif2 for wget2 on arm
- Improve Action to use Platform Preview builds

## Custom Fork v12
- Improve autopif2 to generate from Pixel Beta point releases
- Improve autopif2 to catch more broken environments
- Improve migrate parsing lines with comments
- Update default app replace list for helluvaOS
- Fix retaining replaced non-system ROM apps on KSU/APatch
- Add autopif2 --strong for initial setup with TS
- Add skipping prop deletion to avoid app detections if skipdelprop file exists
