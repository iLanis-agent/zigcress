# Zigcress 1.0 TEST
Native Android Wamuzu zigzag pairing puzzle. Android 8+ (min26), target35. Package com.gg007.zigcress. Twelve original unique boards on a compact 4x3 grid.

## Rules
Wamuzu on a 4x3 grid. Pair all gold circles with separate paths through edge-neighboring cell centers. Every cell is used exactly once. A circle is an endpoint with exactly one link; every non-circle cell has two perpendicular links, making a 90-degree turn. Circle partners are not fixed. No loops, branches, crossings or passing through a circle. Adjacent circles may pair by one link. Separate paths may touch along sides or corners without joining. Tap a gap between cell centers to add or remove a link. Undo/reset, levels and next; saved palette and optional cell-guide dots. No timer or score.

## Download and status
https://mega.co.nz/#!IMdjADiS!KZJ9ZL603QVLgoredeT0XwG9UvPgo3ZwFtC_ji5KVVI
APK SHA256 2f9811bb90b672040310bc91a9d205f80db1f74c51fe62777dce3ace83539f7d; 16878 bytes. Original signing certificate SHA256 1651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. Anonymous downloaded bytes match. No requested permissions. Original icon unchanged.

## Checks
All 131,072 subsets of the 17 grid edges are checked on each of twelve boards: 1,572,864 comparisons agree between production direction masks and bitset component floods and an independent coordinate adjacency BFS oracle. The portable seed-661109 generator enumerates all edge subsets: 355 legal covers in 218 endpoint patterns, including 128 unique patterns with four to eight circles. Twelve selected circle boards each have exactly one solution and all twelve solutions differ. Full coverage, circle degrees, perpendicular turns, two endpoints per path, no loops, bounds, toggle/clear, undo/reset, solved lock and malformed states pass. Actual drawing-adapter taps solve all twelve and check undo/replay, next, levels, menu, privacy and saved palette/cell guides. Six drawing previews inspected, not phone screenshots. Phone runtime/performance/external-browser QA and full Git source commit remain incomplete. Signed TEST, not final or Play published.

## Functional difference
Reviewed all 197 prior live studio descriptions and byte-current 803 web registry entries using functional terms. No Wamuzu or free-partner zigzag pairing match in this partial corpus. Ribbonmere connects fixed endpoint pairs with unrestricted bends; Threadhaven places one open rope per room and separates endpoints. Zigcress instead pairs anonymous circles across the whole board with a compulsory turn in every non-circle cell, no fixed partners or room boundaries. Known Wamuzu adaptation with original generated boards, code and visuals; no copied layouts/code/art or global invention claim. Six fetched rule pages from four sites agree on core rules. No history claim.
Rules https://www.janko.at/Raetsel/Wamuzu/index.htm ; independent rules https://www.cross-plus-a.com/html/cros7wmzu.htm .

## Build
JDK17, Android SDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json. javac -d /tmp/blue-test src/com/gg007/zigcress/Board.java BoardTest.java then java -cp /tmp/blue-test com.gg007.zigcress.BoardTest. bash build.sh makes an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to your own private signing material. No signing secret is included.

## Privacy and branding
Zigcress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Palette, cell-guide dots and solved-board marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 original icon, menu studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and publishing
Complete source/APK, exact cumulative 198-card studio and published catalog/studio sources and updater privately preserved at https://files.instinct.com/pel8163ovpmp-zigcress-source-archive . Repository https://github.com/iLanis-agent/zigcress holds README only; full Git source commit pending. Existing Jekyll static includes retained without changes; no Pages settings changes or client loader. Both site publications verified separately.
