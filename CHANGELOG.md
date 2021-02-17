# Changelog

All notable changes to this project will be documented in this file.

**Note:** This changelog is more detailed, compared to the summarised changelog on https://scratchaddons.com/changelog.

<!-- 

NOTE: 

Updates on the changelog entry in between the start and stop tags will 
automatically create a PR on the website to synchronize the changes!

-->

<!--

TODO LIST:

- Changed entries on "Fixed" section into "Fix ..." sentence form (v1.4.0 - latest)
- Complete missing changelog (v1.4.0)
- Adjust apple's changelog format into the current format (v1.9.2 - v1.9.3)

-->

<!-- sa-changelog-start -->

## [v1.9.3] - 2021-02-15

***TODO***

Fixes bug that would make the extension crash if browser language set to Spanish.

## [v1.9.2] - 2021-02-13

***TODO***

Bugfixes

    #1540 more-links linkifies invalid URLs. (prio-3)
    #1541 Mute status is not loaded. (prio-3)
    #1543 Language codes with uppercase letters don't load. (prio-4)
    #1549 editor-stage-left partially hides the direction picker. (prio-4)
    #1551 animated-thumb alerts that the thumbnail is too big, when in fact the server is down. (prio-3)
    #1560 curator-link crashes on default locale. (prio-2)
    #1567 comments-linebreaks leaves empty lines on replies to ST members' comments. (prio-4)
    #1569 Scratch Addons still cannot be launched on non-English configuration. (prio-1)

## [v1.9.1] - 2021-02-09

NOTE: All updates from [v1.9.0] are pushed on this version.

### Fixed

- Extension crashing on non-English configuration (#1529)

## [v1.9.0] - 2021-02-08 [YANKED]

NOTE: v1.9.0 is only released on Firefox due to a bug that would make the extension crash if browser language not set to English. All updates are included on [v1.9.1].

### Added

#### Addons

- New addon: Fix capitalization of Account Settings (#1413)
- New addon: Show BBCode (#1411)
- Auto-hide block palette: "hover in category" (#1419)
- Mute project player: Icon for muted projects (#1412)
- Record project video: Record mic option (#1492)
- Scratch Messaging: Support for manager promotion notifications (#1471)
- Scratch Notifier: Support for manager promotion notifications (#1471)

### Changed

#### Addons

- Developer tools: Improve UI (#1433)
- Scratch Messaging: Show usernames of lovers and favers (#1474)

#### Extension and Addon API

- Ignore shift-click on settings toggle (#1484)

### Fixed

#### Addons

- Clone counter: Addon blocks main thread (#1473)
- Developer tools: Middle click feature does not list all broadcast block options (#1390)
- Developer tools: Dropdown is not sorted (#1390)
- Developer tools: Wrong color for lists (#1390)
- Developer tools: Invalid blocks sometimes added (#1498)
- Linebreaks in comments: Space after asterisk for ST member replies (#1461)
- Linebreaks in comments: Linebreaks not preserved in some cases (#1461)
- Thumbnails setter: Addon silently fails when thumbnail server errors (#1522)
- Website dark mode: Addon does not apply to post editing pages (#1481)

#### Extension and Addon API

- Inconsistent padding in More Settings (#1418)

## [v1.8.1] - 2021-01-29

### Changed

- Make some classes not use hardcoded hashes (#1403)
- Fix unused vars and return values

### Fixed

- Auto-hide block palette: Addon causing reporter return value bubbles to remain on screen
- More links: Words with ellipsis treated as links due to faulty regex (#1416)
- Scratch 2.0 → 3.0: Gray text shown on page load by default (#1417)
- Website dark mode: Forums image uploader text unreadable (#1389)

## [v1.8.0] - 2021-01-25

### Added

#### Addons

- Disable auto-save (#1232)
- Hide block palette (#1319)
- Linebreaks in comments (#1338)
- Project screen reader support (#1332)
- Better forum quoter: Include BBCode (#1230)
- Cat blocks: Add blinking (#1310)
- Data category tweaks: Move reporters under operations section (#1300)
- Record project video: Support sound recording (#1321)
- Record project video: Improve UI and add options (#1347)
- Show full areas: Support signature settings (#1251)

#### Extension and Addon API

- `msg.locale` (#1314)
- `Trap.getBlockly` (#1331)
- JSDoc (#1339)

### Changed

#### Extension and Addon API

- Render tooltips above tags (#1318)
- Refactor traps (#1331)
- Show beta tag in settings popup (#1336)
- Show warnings in settings popup (#1336)
- Used incorrect cases README and CREDITS (#1344)
- Use SPDX indentifier in licenses (#1344)
- Add web worker support on userscripts (#1345)
- Bump intl-messageformat (#1348)

### Fixed

#### Addons

- Cat blocks: fix missing ears (#1306)
- Developer tools: Help window is incompatible with "Website dark mode" (#1372)
- Editor dark mode: Custom procedure modal title cut (#1372)
- Infinite scrolling: Remove blank space scratchr2 footer (#1375)
- More links: Addon blocks main thread (#1345)
- Scratch 2.0 → 3.0: Remix tree button color affected (#1275)
- Semicolon glitch: Semicolon has wrong color (#1297)
- Website dark mode: 1Emojis have white background (#1276)
- Website dark mode: 2Search bar made unreadable (#1360)
- Website dark mode: 3Message count made unreadable (#1365)

#### Extension and Addon API

- LocalizationProvider logs excessive amount of errors (#1335)
- Addons with permission requirements cannot be enabled on Firefox (#1359)

### Removed

#### Addons

- Fix "Load more" scrolling in search results (#1311)
- Highlight currently executing blocks: Remove notice (#1312)

#### Extension and Addon API

- Remove unused API Tab.getScratchVM (#1339)

## [v1.7.1] - 2021-01-11

### Fixed

- Website dark mode: Certain elements of the Scratch editor affected

## [v1.7.0] - 2021-01-10

### Added

#### Addons

- Better forum quoter (#1127)
- Cat blocks (#639)
- Data category tweaks (v2) (#1097)
- Mute project player (#1217)
- Semicolon glitch (#507)
- Sprite and script count: Block counter (#1121)

#### Extension and Addon API

- A way to disable popups (#1006)
- New popup for changing settings (#1006)
- A way to change Scratch colors (#1096)
- A way to set FPS to values other than 60 (#1131)
- A way to export and import settings (#1136)
- Support for easter egg addons (#1177)

### Changed

#### Extension and Addon API

- Messaging related addons no longer go to the top (#1242)

### Fixed

#### Addons

- Block switching: Addon does not work after switching languages (#1139)
- Block switching: Addon mishandles forever block (#1139)
- Cloud games: Add links to users (#1006)
- Colored context menus: No color when right-clicking the edge (#1119)
- Colored context menus: No color on new procedure arguments (#1119)
- Confirm actions: Addon runs on studios and topics (#1166)
- Developer tools: Optimize slow operations (#1120)
- Developer tools: Actions required multiple undos when reverting (#1120)
- Developer tools: CSS may cause encoding error (#1120)
- Developer tools: Extension blocks that are not orphaned can be removed (#1196)
- Hex color picker: Wrong background color on dark mode (#1142)
- Project notes tabs: Addon does not work in Firefox (#1117)
- Project notes tabs: Instructions do not fill empty space in Firefox (#1117)
- Project notes tabs: Errors when a section is missing (#1117)
- Project notes tabs: Projects with only instructions would have "Notes and Credits" on the tab (#1117)
- Project notes tabs: Buttons overlaps with remix credits (#1117)
- Project notes tabs: Addon loads on onload, rather than DOMContentLoaded (#1117)
- Project notes tabs: Description has a typo (#1190)
- Website dark mode: Studio thumbnail border does not affected (#1160)
- Website dark mode: Compatibility with other addons (#1160)
- Website dark mode: Post preview does not affected (#1160)
- Website dark mode: Syntax highlighting in forums does not affected (#1160)
- Scratch 2.0 → 3.0: Color on usernames in Messages page affected (#1189)
- Scratch 2.0 → 3.0: Some pages are not supported (#1259)
- Scratch Messaging: Remove double escaping on tags (#1172)
- Scratch Notifier: Addon crashes when receiving crafted message (#1172)
- Scratch Notifier: Tags in project titles to emojis converted (#1172)
- Website dark mode: Some pages are not supported (#1259)

#### Extension and Addon API

- Update notification uses wrong font (#1125)
- Clicking outside "More Settings" modal does not close the modal (#1125)
- XSS filter does not escape quotes (#1128)
- Popup has two scrollbars (#1145)
- Extension option shows incorrect letters when localized (#1159)
- Uninstall URL still opens in prerelease (#1164)
- Popups are misaligned (#1187)
- Icons are blurry (#1243)
- getMsgCount errors when used in userscripts (#1245)
- Tooltips are misaligned (#1252)
- Site access screen opens on Firefox (#1258)


## [v1.6.1] - 2020-12-27

NOTE: All updates from [v1.6.0] are pushed on this version.

### Fixed

- Chrome enforces extensionName to be specified

## [v1.6.0] - 2020-12-27 [YANKED]

NOTE: v1.6.0 is only released on Firefox due to a special requirement by the Chrome Web Store related to localization. All updates are included on [v1.6.1].

### Added

#### Addons

- Color picker (#1061)
- Record project video (#1083)
- Show my-ocular status: Support profile pages (#1026)
- Studio manager tools: Add a way to leave studios from My Stuff (#1041)

### Fixed

#### Addons

- Thumbnails setter: Addon listed as a website addon (#1064)

#### Extension and Addon API

- Changing color settings may cause memory leak (#1062)

## [v1.5.1] - 2020-12-15

### Fixed

- Comment loading screen is not dark when using dark-www (#1019)
- Onion-skinning groups images unintentionally (#1037)

## [v1.5.0] - 2020-12-13

### Added

#### Addons

- Onion skinning (#879)
- Profile page banner (#895)

#### Extension and Addon API

- Show full areas supports loading more in What's Happening (#899)
- Warning when posting on Japanese forum (#944)
- Warning when site access is off (#950)
- A way to disable thumbnail overwriting (#964)
- Block switching supports more blocks (#979)
- New devtools feature for showing broadcast senders and receivers (#980)
- Button to open translation page (#1002)
- Notification for updates (#1016)
- "New" tag for addons (#1016)

### Changed

#### Extension and Addon API

- Load addons inside frames (#897)
- Localization updates

### Fixed

#### Addons

- Customizable block colors: Addon did not affect devtools middle click feature (#669)
- Customizable block colors: Custom colors do not apply to custom blocks (#948)
- Customizable block colors: Custom colors do not apply to dropdowns (#956)
- Customizable block colors: Custom colors do not apply to extension blocks in non-English environment (#956)
- Customized quotes & code blocks on forums: Addon categorized as editor addon (#989)
- Mouse position: Addon crashes in project view (#954)
- Scratch 2.0 → 3.0: /news is not supported (#941)
- Scratch Messaging: "Show More" button is partially hidden (#929)
- Scratch Messaging: Addon links to curators page for activity messages (#969)
- Scratch Messaging: Follower name links uses onClick (#969)
- Show my-ocular status: Addon is not localized (#925)
- Studio manager tools: Buttons don't have text when hovered (#994)
- Studio manager tools: Buttons don't have text when hovered (#994)
- Website dark mode: Project comments are unreadable with dark mode (#928)
- Website dark mode: /news is not supported (#941)
- Website dark mode: Some pages are not listed in dark mode list (#949)
- Website dark mode: Addon still loads on editors (#960)
- Website dark mode: Addon does not make cloudmonitor rows dark (#960)
- Website dark mode: Addon changes variable monitor color (#981)
- Website dark mode: Addon styles in-editor Join Flow (#981)
- Website dark mode: Addon styles list row backgrounds when focused (#981)
- Website dark mode: Addon does not apply to loading screen (#995)
- Website dark mode: Addon makes search input dark (#995)
- Website dark mode: Addon makes project warnings unreadable (#995)
- Some addons overflow in small stage (#930)
- Addons sometimes don't load in Firefox (#935)

#### Extension and Addon API

- Most translations don't load (#925)
- "Search" placeholder is not localized (#925)

## [v1.4.1] - 2020-12-03

### Fixed

- Forum search: Fix crashes (#901)
- Messages in editor: Typo in addon description (#903)
- Sprite and script count: Script count was inaccurate (#904)
- Addons have incorrect name (#887)

## [v1.4.0] - 2020-11-29

***TODO***

## [v1.3.3] - 2020-11-24

### Changed

- Move libraries to the `libraries` folder (998781b)

## [v1.3.2] - 2020-11-24

### Fixed

- More links: Fix security issue due to faulty regular expression (GHSA-6qfq-px3r-xj4p, #827)

## [v1.3.1] - 2020-11-09

### Fixed

- Live featured project: Disable addon by default (#684)

## [v1.3.0] - 2020-11-08

### Added

#### Addons

- Live featured project (#633)
- Pause button (#619)
- Resizable comment input (#608)
- Thumbnails setter (#602)
- Last edit tooltip: Fix errors when the project is unshared (#629)
- Scratch Notifier: Add sound when you get a message (#595)
- Show full areas: Add load more button on profile page (#630)

#### Extension and Addon API

- More settings (#609)
- A warning on the Scratch forums to avoid posts about Scratch Addons (#626)
- Theme switch (#641)
- /* sa-autoupdate-theme-ignore */` (#652)

### Changed

#### Addons

- Dark mode editor: make fullscreen dark (#658)
- Editor dark mode: Style color picker on 3.Dark(er) (#656)
- Enable some old addons for all users on v1.3.0 (#655)
- Forums image uploader: Do not use project thumbnails (#653)
- Show full areas: Only load data if the user clicks "load more" (#665)

#### Extension and Addon API

- Revamp icons (#617)
- Remove dark mode default changer (#625)
- Revamp scrollbar design (#651)
- Many little UI changes & fixes (#659)
- Use `ESC` to clear search on settings page (#664)
- Add version name and open in new tab in the link to changelog in settings (#677)

### Fixed

#### Addons

- Better emojis: Remove extraneous bracket (#586)
- Better emojis: Add extraneous bracket back (#605)
- Customizable block colors: Add warning for traps (#629)
- Exact count: Fix on studios (#599)
- Infinite scrolling: Fix bug when showing your topics/posts in the forums (#601)
- Remix tree button on project pages: Fix remix button to work on all project pages (#581)
- Use dynamic CSS selector instead of static (#606)

#### Extension and Addon API

- Fix `.zip` download link (#577)
- Fix background console errors (#663)

### Removed

#### Extension and Addon API

- Remove prototype handler (#652)

## [v1.2.1] - 2020-10-27

NOTE: All updates from [v1.2.0] are pushed on this version.

### Fixed

- Fix addon warning not showing (#571)

## [v1.2.0] - 2020-10-27 [YANKED]

NOTE: v1.2.0 is only released on Firefox due to an issue with perfomance warnings not showing. All updates are included on [v1.2.1].

## [v1.1.1] - 2020-10-11

NOTE: All updates from [v1.1.0] are pushed on this version.

### Fixed

- Use webRequest instead of webNavigation (#457)

## [v1.1.0] - 2020-10-10 [YANKED]

NOTE: v1.1.0 is not released due to a permission issue. All updates are included on [v1.1.1].

### Added

#### Addons

- 60fps (#383)
- Better emojis (#402)
- Cloud games (#407)
- Display stage on left side (#376)
- Forum Search (#363)
- Scratch 2.0 → 3.0 (theme) (#359)
- Search profile (#405)

#### Extension and Addon API

- Access to addon settings via CSS variables (#439)
- Color input on settings (#400)
- General CSS around tabs in popup (#411)
- New links to credits and review pages (#414)
- Uninstall page (#437)
- Warnings, mainly to warn lags for addons that use addon.tab.traps (6a222c0)

### Changed

#### Addons

- Bitmap images copying: Add note to clear up confusion (#454)
- Cloud games: Add new scrollbar to cloud games (#412)
- Display stage on left side: Add warning
- Editor dark mode: Affect password input (#440)
- Editor dark mode: Change var(--text) to white on 3.Darker so that text is more readable
- Editor dark mode: Decrease font-weight from 800 to 700
- Editor dark mode: Don't inject dark mode into the remix tree (#420)
- Editor dark mode: Don't style scratch 3.0 search bar (#420)
- Editor dark mode: Remove a border that shouldn't be in 3.Dark and 3.Darker
- Image uploader: Slight updates (#371)
- Scratch Messaging: Make reply textbox more like Scratch (#375)
- Show full areas: Add expand button instead of all full signatures (#330)
- Show full areas: Clean signature expand button (#384)
- Show full areas: Cleaner expand signature
- Show full areas: Complete refactor of expand signature 
- Update tags and addon names (#422)

#### Extension and Addon API

- Ability to inject userstyles when the page starts loading (#328)
- Automatically update themes when changing settings (#252)
- Change end lines from CRLF to LF (#367)
- Change search to 150px (#378)
- Do not load traps unless addons that use them are enabled (#403)
- Hide settings page until it is loaded (0b3392c)
- Make better variable name (#446)
- Make sure the head loaded before injecting userstyles (#408)
- Run userscripts earlier, when the window load event triggers (#429)

### Removed

#### Extension and Addon API

- "Changed by [line of code]" console logs (#419)

### Fixed

#### Addons

- Scratch Messaging: Fix link to studio comments (#356)
- Scratch Messaging: Ignore Set-Cookie inside comment endpoint (#331)
- Scratch Notifier: Fix studio comments don't notify with the full comment content

#### Extension and Addon API

- Fix Vue warns (#355)
- Fix bug in URL/pattern matcher when addon runs if manifest has no trailing slash (#332)
- Fix messageForAllTabs() not working properly in Firefox (#386)
- Fix modifying "select" setting not disabled if addon disabled (#353)

## [v1.0.0] - 2020-09-24

Initial release.

[v1.9.3]: https://github.com/ScratchAddons/ScratchAddons/releases/tag/v1.9.3
[v1.9.2]: https://github.com/ScratchAddons/ScratchAddons/releases/tag/v1.9.2
[v1.9.1]: https://github.com/ScratchAddons/ScratchAddons/releases/tag/v1.9.1
[v1.9.0]: https://github.com/ScratchAddons/ScratchAddons/releases/tag/v1.9.0
[v1.8.1]: https://github.com/ScratchAddons/ScratchAddons/releases/tag/v1.8.1
[v1.8.0]: https://github.com/ScratchAddons/ScratchAddons/releases/tag/v1.8.0
[v1.7.1]: https://github.com/ScratchAddons/ScratchAddons/releases/tag/v1.7.1
[v1.7.0]: https://github.com/ScratchAddons/ScratchAddons/releases/tag/v1.7.0
[v1.6.1]: https://github.com/ScratchAddons/ScratchAddons/releases/tag/v1.6.1
[v1.6.0]: https://github.com/ScratchAddons/ScratchAddons/releases/tag/v1.6.0
[v1.5.1]: https://github.com/ScratchAddons/ScratchAddons/releases/tag/v1.5.1
[v1.5.0]: https://github.com/ScratchAddons/ScratchAddons/releases/tag/v1.5.0
[v1.4.1]: https://github.com/ScratchAddons/ScratchAddons/releases/tag/v1.4.1
[v1.4.0]: https://github.com/ScratchAddons/ScratchAddons/releases/tag/v1.4.0
[v1.3.3]: https://github.com/ScratchAddons/ScratchAddons/releases/tag/v1.3.3
[v1.3.2]: https://github.com/ScratchAddons/ScratchAddons/releases/tag/v1.3.2
[v1.3.1]: https://github.com/ScratchAddons/ScratchAddons/releases/tag/v1.3.1
[v1.3.0]: https://github.com/ScratchAddons/ScratchAddons/releases/tag/v1.3.0
[v1.2.1]: https://github.com/ScratchAddons/ScratchAddons/releases/tag/v1.2.1
[v1.2.0]: https://github.com/ScratchAddons/ScratchAddons/releases/tag/v1.2.0
[v1.1.1]: https://github.com/ScratchAddons/ScratchAddons/releases/tag/v1.1.1
[v1.1.0]: https://github.com/ScratchAddons/ScratchAddons/releases/tag/v1.1.0
[v1.0.0]: https://github.com/ScratchAddons/ScratchAddons/releases/tag/v1.0.0

<!-- sa-changelog-end -->

<!--

Here's the simple format. Other types such as "Removed" can be added later.

### Added

#### Addons

#### Extension and Addon API

### Changed

#### Addons

#### Extension and Addon API

### Fixed

#### Addons

#### Extension and Addon API

-->