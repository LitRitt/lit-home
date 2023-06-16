---
layout: home
permalink: /ignited/releases
title: Ignited Releases
---

## [Ignited Home](https://litritt.com/ignited)

## 1.4.4 - 6/7/2023

## 1.4.5 - 6/16/2023

### **New Features**

- Blurred game backgrounds for skins
  - Options to enable/disable, change blur strength, and adjust the brightness
- Option to change the N64 graphics rendering API between OpenGL ES 2 and OpenGL ES 3

### **Updates**

- Adds support for skins with .ignitedskin extension to differentiate between legacy Delta skins and new Ignited skins
- Adds more mappable inputs for controllers

### **Bugfixes**

- Fixes overlapping buttons when mapping controller inputs
- Fixes crashes on N64 when opening menu and saving state

### **New Features**

- Adds several new alternate app icons and an interface to change between them
- Adds an option within every feature to reset all options to their default values, and a power user option to reset all options at once
- Adds an option to change the intensity of the favorite games highlight glow

### **Updates**

- Makes the reset artwork feature work with the DS home screen icons
- Makes rewind deleting its states on rewinding or quitting the game a toggleable option
  - Allows the rewind feature to be used as a persistent secondary auto-save method

### **Bugfixes**

- Fixes artwork size setting not applying until swiping to a new page

## 1.4.3 - 6/4/2023

### **Updates**

- Adds an option for custom touch overlay color
- Creates a new feature section called Games Collection
- Moves settings previously found in Game Artwork Customization into separate sections within the Games Collection feature set
- Makes Favorites features respect whether the feature is actually enabled

### **Bugfixes**

- Fixes lag when changing settings with animated artwork in the background
- Fixes animated artwork losing transparency when downsampling

## 1.4.2 - 6/3/2023

### **New Features**

- Quick Settings
  - Quick access to game options and actions: screenshot, save, load, volume, game speed, palettes
  - Accessible from a controller/skin button as well as the pause menu

### **Updates**

- New options for game title size and max lines, available in User Interface Features -> Game Artwork Customization

### **Bugfixes**

- Fixes crash on iPad when resolving sync merge conflicts
- Fixes accidentally deleting Games directory during sync in rare circumstances

## 1.4.1 - 5/14/2023

### **New Features**

- Adds an option to reset game artwork to the one provided by the games database
- Adds a power user option to reset artwork for every game at once

### **Bugfixes**

- Fixes cancelling some pause menu popups causing the game to freeze
- Fixes incorrect checkmarks next to selected palette for sprite 1 and 2
- Fixes preview save state being overwritten by auto save state

## 1.4 - 5/13/2023

### **Updates**

- Settings page has been completely revamped and reorganized
  - Many existing features received improvements as they were moved

### **New Features**

- Game Boy color palettes
  - Several built in palettes and 3 user customizable palettes
  - Both the main and sprite palettes can be changed, allowing for unique palettes never before possible
- Custom Theme Color
  - Choose your own color to use for the app accent color
- Favorite Games
  - Games can be favorited, with options to highlight and sort them to the top of the games list
- Game Sorting
  - You can now sort games A-Z, Z-A, most recently played, and least recently played
- Animated Game Artwork
  - Support for short animated GIFs as your game artwork, with options for animation pause and speed

### Bugfixes

- Burnt a bunch of bugs

## 1.3.0 - 4/28/2023

### **New Features**

- Skin Debug Device
  - Switch to another device type when debugging a skin, useful for testing skins on devices you don't own

### **Updates**

- Adds toasts notifications for more actions

### **Bugfixes**

- Now creates an auto save state when saving in-game, fixes old autosaves overwriting game data when loaded
- Fixes the Resume button not working with auto-load save states disabled
- Fixes the pause menu not fully showing in landscape with 2 rows of buttons

## 1.2.10 - 4/23/2023

### **New Features**

- New Screenshot options
  - Save to Files, Save to Photos, Image Scale

### **Updates**

- Forced light status bar during gameplay
- Updated licenses page formatting
- Reordered pause menu buttons and adjusted spacing to 4 items per row

### **Bugfixes**

- Adjusted settings slider labels to fit with bold system text
- Removed unimplemented swipable page control

## 1.2.9 - 4/18/2023

### **Updates**

- Added page for Lit Patrons shoutout
- Changed rewind to be disabled by default

### **Bugfixes**

- Fixed a crash when toggling clicky haptics
- Removed unsupported file extensions on GPGX

## 1.2.8 - 4/16/2023

### **New Features**

- Added toggle to show or hide the status bar while in-game
- Added Resource Links section to settings
- Added Rom Patcher JS and DS Save Converter links

### **Updates**

- Added remaining file extensions for all systems supported by the Genesis Plus GX core

## 1.2.7 - 4/15/2023

### **New Features**

- Added options to toggle game artwork borders, shadows, and rounded corners

### **Updates**

- Added confirmation popup to advanced settings
- Game screenshots are now scaled up by 5x before being saved

## 1.2.6 - 4/14/2023

### **New Features**

- Game Screenshots - save a screenshot of the game screen to your photos with a pause menu item or controller skin button

## 1.2.5 - 4/12/2023

### **Bugfixes**

- Fixed importing game saves with auto-load save state enabled

### **New Features**

- Added advanced setting to clear auto save states from every game

## 1.2.4 - 4/11/2023

### **Bugfixes**

- Disabled auto-load save on DSi Home Screen
- Removed cheats, save, load, and rewind pause menu items from DSi Home Screen
- Removed cheats from DS Home Screen

## 1.2.3 - 4/10/2023

### **New Features**

- Updates screen will now be shown once per update at launch

### **Updates**

- Updates screen now includes dates for all versions

## 1.2.2 - 4/9/2023

### **New Features**

- Game Volume - Change the game volume relative to your device volume
- Toggle for whether game audio should play when other audio is playing in the background

### **Updates**

- Updated OpenVGDB database

## 1.2.1 - 4/9/2023

### **New Features**

- Audio Button Feedback - option to play a sound when a controller skin input is pressed

### **Updates**

- Raise minimum iOS to 14.0 - Removed all legacy code

### **Bugfixes**

- Fixed laggy sliders in settings that could crash the app when paused

## 1.2.0 - 4/8/2023

### **New Features**

- Touch Overlays - Get visual feedback about what buttons are currently pressed
- Options for size, opacity, and color of touch overlays
- Resume Button added to game collection screen beside the page dots

### **Bugfixes**

- Fixed controller skins losing transparency on device rotation

## 1.1.4 - 4/6/2023

### **New Features**

- Re-enabled Save State Rewind - Disabled on GBC to prevent crashes with gambette

### **Updates**

- Added new Advanced section to settings - Moved alt skin and debug toggles there
- Custom fast forward speed is now default - Toggle removed

### **Bugfixes**

- Fixed the Show with Controller settings not working on DS

## 1.1.3 - 4/5/2023

### **New Features**

- Added option for clicky haptic feedback - A more rigid haptic impulse will be sent on both button press and release
- Added slider for haptic feedback strength

## 1.1.2 - 4/2/2023

### **WARNING** 

This update uses a new bundleID with my domain. It will never change again after this point. Installing will not overwrite your old app. You will need to use Sync or manually transfer data to the new app.

### **New Features**

- Made auto save states syncable

### **Updates**

- Made the restart game button available to skins and controllers
- Made the current game highlighting stand out more

### **Bugfixes**

- Fixed last unthemed elements buried in settings

## 1.1.1 - 4/2/2023

### **Changes**

- Updated toast notification logic to prevent multiple toasts being shown at once

## 1.1.0 - 4/1/2023

### **New Features**

- Added a toggle to automatically load the last auto save when launching a game
- Added toggle to enabled/disabled in-game toast notifications

### **Updates**

- Removed the Resume Game prompt from the game selection screen
- Added a Restart Game pause menu button

## 1.0.2 - 4/1/2023

### **New Features**

- Added theme colored highlighting to currently running game's artwork

### **Updates**

- Make artwork spacing dynamic like size

### **Bugfixes**

- Fixed some artwork bugs caused by resizing

## 1.0.1 - 3/30/2023

### **Bugfixes**

- Fixed link in settings

## 1.0.0 - 3/30/2023

### **New Features**

- Theming - Choose from a variety of colors to change the tint and app icon of Ignited. Emulate in your own style!

### **UI Updates**

- Album artwork now has rounded corners, contrasting borders, and a drop shadow
- Can now change the artwork size between small, medium, and large
- Default box-art now features the cartridge of their respective system

### **Changes**

- Custom fast-forward is enabled by default
- Default speed changed to 4x
- Removed 4x from unsafe speeds

## 0.7.1 - 3/19/2023

### **Changes**

- Alternate Skin pause menu item now only shows is the current skin supports it
- Debug Mode pause menu item now only shows if the current skin's debug property is set to true, or debug mode is manually enabled in settings
- Reordered save state menu sections. General at the top and Quick/Auto at the bottom
- Rebrand to from Delta Ignited to just Ignited

## 0.7.0 - 3/18/2023

### **New Features**

- Alt Skins - An alternate skin appearance that can be swapped to from a skin or menu item. Allows for a wide range of implementations. Any feature that boils down to switching something on a skin can be achieved using this new feature, including: DS screen swapping, toggle-able screen filters, cosmetics like a power/charging light, and more.
- Toast Notifications - You will now receive short in-game popups when you save, load, or toggle something. Play with confidence knowing Ignited did what you asked it to.
- Always Show Skin Toggle - You now have the option to always show the skin image, even when a controller connected
- In-App Debug Toggle - You no longer have to edit the debug setting in a controller skin, the option is now available in both the settings and the pause menu

### **Changes**

- Updated footer descriptions for `Controller Skin Options` and `Fast Forward` sections in settings
- Added `Alternate Skin` and `Debug Mode` pause menu items

### **Bugfixes**

- Fixed a bug where the user preferred DS core was changed to MelonDS every time the app started

## 0.6.3 - 3/11/2023

### **New Features**

- Access custom fast forward speeds from in-game menu and skin buttons

### **Updates**

- Make users accept a warning prompt to access 4x and faster speeds
- Add 150% speed setting
- Game will auto-save on every fast forward activation
- Number of auto-saves increased from 2 to 4

## 0.6.2 - 3/5/2023

### **New Features**

- Allow patrons to install and update the app from safari

### **Updates**

- Fix controller skin previews not showing for standard size iPhones

## 0.6.1 - 3/4/2023

### **Updates**

- Change formatting of updates screen
- Move updates to its own section in settings

## 0.6.0 - 3/3/2023

### **New Features**

- Add in-app updates changelog

## 0.5.3 - 3/3/2023

### **Updates**

- Update local multiplayer controller settings logic
- Remove rewind feature due to crashes

## 0.5.2 - 2/26/2023

### **Updates**

- Added new GBC skin with matching style and previews 

## 0.5.1 - 2/25/2023

### **Updates**

- Implemented new preview feature in default GBA skin

## 0.5.0 - 2/25/2023

### **New Features**

- Controller skin previews in settings

## 0.4.1 - 2/25/2023

### **Updates**

- Made the custom fast forward speed popup pretty and informative
- Fixed crashes on iPad related to popups
- Fixed a crash in P2-P4 controller settings pages

## 0.4.0 - 2/24/2023

### **New Features**

- Custom fast forward speed setting and toggle

## 0.3.0 - 2/23/2023

### **New Features**

- Links to skin download sites added to settings
- Inset and rounded settings tables

### **Updates**

- Ensured all settings sections have a descriptive footer

## 0.2.1 - 2/21/2023

### **New Features**

- Genesis core made available

### **Updates**

- Genesis file extension fix
- Remove all beta checks
- Contributors page updated

## 0.2.0 - 2/20/2023

### **New Features**

- Extended MFi Controller Support
- Save State Rewind
- Local Multiplayer

### **Updates**

- Contributors page updated
- Update links in settings

## 0.1.0 - 2/19/2023

### **New Assets**

- App Icon
- Box Art
- DS Home Icon
- Launch Screen
- GBA Controller Skin