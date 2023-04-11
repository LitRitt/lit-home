---
layout: home
permalink: /ignited/releases
title: Ignited Releases Changelog
---

## [Ignited Main Page](https://litritt.com/ignited)

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