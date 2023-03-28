---
layout: home
permalink: /ignited
title: Ignited Emulator for iOS
---

Ignited is my fork of the Delta emulator. I build on top of Delta's development by adding new assets, skins, features, and fixes. If you want to support me and help make the best iOS emulator even better, please consider becoming a [patron](https://patreon.com/litritt).

Patrons will be able to install and update Delta Ignited from the link on this page at any time, without relying on sideloading solutions like AltStore or Scarlet. Non-patrons can install Ignited with the AltStore/SideStore links below, or download the IPA manually.

# GitHub

## [Repo](https://github.com/Lit-Development/Delta-Ignited) | [Releases](https://github.com/Lit-Development/Delta-Ignited/releases)

# Direct Download

## [Patron OTA](itms-services://?action=download-manifest&url=https://f005.backblazeb2.com/file/lit-apps/ignited/0.7.1/manifest.plist) | [IPA](https://github.com/Lit-Development/Delta-Ignited/releases/latest/download/Ignited.ipa)

# Add Source to AltStore

## [AltStore](altstore://source?url=https://apps.litritt.com) | [SideStore](sidestore://source?url=https://apps.litritt.com)

# Install with AltStore

## [AltStore](altstore://install?url=https://github.com/Lit-Development/Delta-Ignited/releases/latest/download/Ignited.ipa) | [SideStore](sidestore://install?url=https://github.com/Lit-Development/Delta-Ignited/releases/latest/download/Ignited.ipa)

# Changelog

## 0.7.1

### **Changes**

- Alternate Skin pause menu item now only shows is the current skin supports it
- Debug Mode pause menu item now only shows if the current skin's debug property is set to true, or debug mode is manually enabled in settings
- Reordered save state menu sections. General at the top and Quick/Auto at the bottom
- Rebrand to from Delta Ignited to just Ignited

## 0.7.0

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

## 0.6.3

### **New Features**

- Access custom fast forward speeds from in-game menu and skin buttons

### **Updates**

- Make users accept a warning prompt to access 4x and faster speeds
- Add 150% speed setting
- Game will auto-save on every fast forward activation
- Number of auto-saves increased from 2 to 4

## 0.6.2

### **New Features**

- Allow patrons to install and update the app from safari

### **Updates**

- Fix controller skin previews not showing for standard size iPhones

## 0.6.1

### **Updates**

- Change formatting of updates screen
- Move updates to its own section in settings

## 0.6.0

### **New Features**

- Add in-app updates changelog

## 0.5.3

### **Updates**

- Update local multiplayer controller settings logic
- Remove rewind feature due to crashes

## 0.5.2

### **Updates**

- Added new GBC skin with matching style and previews 

## 0.5.1

### **Updates**

- Implemented new preview feature in default GBA skin

## 0.5.0

### **New Features**

- Controller skin previews in settings

## 0.4.1

### **Updates**

- Made the custom fast forward speed popup pretty and informative
- Fixed crashes on iPad related to popups
- Fixed a crash in P2-P4 controller settings pages

## 0.4.0

### **New Features**

- Custom fast forward speed setting and toggle

## 0.3.0

### **New Features**

- Links to skin download sites added to settings
- Inset and rounded settings tables

### **Updates**

- Ensured all settings sections have a descriptive footer

## 0.2.1

### **New Features**

- Genesis core made available

### **Updates**

- Genesis file extension fix
- Remove all beta checks
- Contributors page updated

## 0.2.0

### **New Features**

- Extended MFi Controller Support
- Save State Rewind
- Local Multiplayer

### **Updates**

- Contributors page updated
- Update links in settings

## 0.1.0

### **New Assets**

- App Icon
- Box Art
- DS Home Icon
- Launch Screen
- GBA Controller Skin