# Happy Hacking Keyboard Studio (US Layout) — Complete User Manual

**Manufactured by PFU Limited**
**Issue Date: September 2024 | Document No. P3PX-E061-04ENZ2**

![HHKB Studio Front View](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/front_US.png)

---

## Table of Contents

1. [Parts and Functions](#1-parts-and-functions)
2. [Special Key Assignment](#2-special-key-assignment)
3. [Power](#3-power)
4. [DIP Switch Settings](#4-dip-switch-settings)
5. [Adjusting Keyboard Height](#5-adjusting-keyboard-height)
6. [Status of the LED Indicator](#6-status-of-the-led-indicator)
7. [Profiles](#7-profiles)
8. [Bluetooth Connection](#8-bluetooth-connection)
9. [USB Connection](#9-usb-connection)
10. [Switching & Deleting Devices](#10-switching--deleting-devices)
11. [Fn (Function) Key & Layers](#11-fn-function-key--layers)
12. [Fn Key Input Reference Table](#12-fn-key-input-reference-table)
13. [Key Combinations Quick Reference](#13-key-combinations-quick-reference)
14. [Pointing Stick & Mouse Keys](#14-pointing-stick--mouse-keys)
15. [Gesture Pads](#15-gesture-pads)
16. [Changing the Keymap (Keymap Tool)](#16-changing-the-keymap-keymap-tool)
17. [Replacing Parts](#17-replacing-parts)
18. [Keyboard Specifications](#18-keyboard-specifications)
19. [Cleaning](#19-cleaning)

---

## 1. Parts and Functions

### Front

![Front View](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/front_US.png)

| No. | Name | Description |
|-----|------|-------------|
| 1 | Pointing stick | Push this stick with your finger in any direction to move the cursor on the screen. Hold down the mouse key center button and control the pointing stick to scroll the screen. |
| 2 | LED indicator | Located at the upper right. Indicates the keyboard status with its color and blinking/lighting pattern. |
| 3 | Mouse key left button | Functions as the left button on an ordinary mouse by default. |
| 4 | Mouse key center button | Hold down this button and control the pointing stick to scroll. Functions as the [Fn2] key by default and can change pointing stick and gesture pad movements when used with other keys. |
| 5 | Mouse key right button | Functions as the right button on an ordinary mouse by default. |

### Back

![Back View](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/back.png)

| No. | Name | Description |
|-----|------|-------------|
| 1 | Power switch | Turns on/off the keyboard. Slide right to turn on (green indicator visible). |
| 2 | USB Type-C connector | Used with the provided USB Type-C cable to connect the keyboard to a device via USB. This connector has no charging function for rechargeable batteries. |

### Side

![Side View](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/side_US.png)

| No. | Name | Description |
|-----|------|-------------|
| 1 | Gesture pads | Four pads located on the sides of the keyboard. Switch windows, scroll, and perform other operations intuitively by sliding the gesture pads with your fingers. |

### Bottom

![Bottom View](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/bottom.png)

| No. | Name | Description |
|-----|------|-------------|
| 1 | Battery cover | Open this cover to insert/remove the batteries and access the DIP switches. Access information is printed on the reverse side. |
| 2 | Tilt stand | Used to adjust the height of the keyboard at two levels. |
| 3 | DIP switch | Turn the switch Up (ON)/Down to change the keyboard settings. |
| 4 | Battery box | To use the keyboard with a wireless connection, insert four AA batteries. |
| 5 | Product label | A label displaying the serial number (SER.NO.) and other information. |

---

## 2. Special Key Assignment

Special key assignment varies depending on the profile (key layout) in use. A profile for each OS is saved as default. Profile1 (Windows) is applied automatically when the keyboard is first connected.

To use the keyboard on macOS/iOS/iPadOS, switch to Profile2 (macOS profile).

### Profile1 — Windows Key Layout

![Windows Key Assignment](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/designkey_Win_US.png)

### Profile2 — macOS Key Layout

![macOS Key Assignment](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/designkey_Mac_US.png)

---

## 3. Power

### Using Batteries for Power Supply

To use the keyboard wirelessly, insert four AA batteries. When replacing batteries, make sure the power is off.

![Removing the Cover](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/cover_remove.png)

**Procedure:**

1. Slide the cover on the base of the keyboard and lift it up to remove it.
2. When lifting or moving the keyboard, hold it with both hands.
3. Insert four AA batteries, negative side first, into the battery box. Check that positive and negative terminals are placed correctly.
4. Attach the cover back. Close the cover firmly.

![Inserting Batteries](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/battery_replace.png)

### Using a USB Cable for Power Supply

By connecting a USB cable to HHKB Studio, you can supply power via USB without using batteries. Connect HHKB Studio to a device with the provided USB Type-C cable. This does not consume battery power (except for self-discharge). Remove the batteries if you will not use them for a long time.

### Turning the Power ON/OFF

**Turning ON:** Slide the power switch on the back of the keyboard to the right (it will turn green).

**Turning OFF:** Slide the power switch on the back of the keyboard to the left.

**Power Saving Mode:** If HHKB Studio is left unused for 30 minutes, it will automatically enter power saving mode and disconnect from Bluetooth. To reconnect, press the [Return] key. Power saving mode will not activate when connected via USB. You can change the power saving setting using DIP switch SW6.

---

## 4. DIP Switch Settings

You can use the DIP switches on the keyboard to quickly change settings for the mouse keys, gesture pads, pointing stick, scrolling direction, [Delete] key, and power saving.

> **Important:** Be sure to turn off the power before setting any of the DIP switches. Use a flathead screwdriver to change the switches. All switches are set to [Down] as the factory default.

![DIP Switch Location](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/DIPswitch.png)

| DIP Switch | SW1 | SW2 | SW3 | SW4 | SW5 | SW6 |
|------------|-----|-----|-----|-----|-----|-----|
| **Description** | Mouse key | Gesture pad | Pointing stick | Scrolling direction | [Delete] key | Power saving |
| **Up (ON)** | Disabled | Disabled | Disabled | Reverse scrolling | Back Space | Disabled |
| **Down** | Enabled | Enabled | Enabled | Natural scrolling | Delete | Enabled |

**SW4 Notes:** Reverse scrolling = opposite direction to the pointing stick push. Natural scrolling = same direction as the pointing stick push.

**SW5 Note:** For a macOS profile, SW5 is disabled and [Delete] always works as the Delete key.

**SW6 Notes:** When enabled (Down), the keyboard enters power saving mode after 30 minutes of inactivity. Press [Return] to reconnect. Power saving mode does not activate when connected via USB regardless of this setting. Requires firmware B0.07 or later.

---

## 5. Adjusting Keyboard Height

A tilt mechanism on the bottom of the keyboard allows you to adjust the height at two levels. Raise one of the tilt stands until it locks in place. Set the tilt stands to the same height on the right and left sides.

![Tilt Stand Adjustment](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/tilt_US.png)

To store the tilt stands, push back the long tilt stand first and then push back the short tilt stand. Pushing back both at the same time also works.

---

## 6. Status of the LED Indicator

The LED indicator on the upper right of HHKB Studio indicates the status of the keyboard. Various statuses are displayed by combining four LED indicator lights.

![LED Indicator Layout](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/LEDstatus_US.png)

### After Power On / Checking Profile & Device

| Order | Status | Description |
|-------|--------|-------------|
| 1 | ![Power ON](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/LED_PowerON_01.png) All four lights light up once in white | Indicates the keyboard is turned on. |
| 2 | ![Profile Check](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/LED_PowerON_02.png) Light for profile number lights up in white | Indicates which profile (1–4) is applied. |
| 3a | ![BT Connection](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/LED_PowerON_03.png) Light for device lights up in blue (Bluetooth) | Shows which Bluetooth device (1–4) is connected. |
| 3b | ![USB Connection](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/LED_Connect_USB.png) All four lights light up in blue (USB) | Indicates USB connection. |

### During Use

| Status | Description |
|--------|-------------|
| ![Off](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/LED_OFF.png) All lights off | **Connected mode (Ready):** Keyboard is connected and ready. **Power saving mode:** Activated after 30 min inactivity (battery), 10 min in pairing mode, or when disconnected. Press [Return] to resume. |
| ![Low Battery](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/LED_LowBattery.png) Leftmost light blinks in orange | Once every 30 seconds: battery power is low. Twice every 15 seconds: replace batteries immediately. |

### When Establishing/Switching a Connection

| Status | Description |
|--------|-------------|
| ![Pairing Standby](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/LED_PairingStandby.png) Lights sweep side to side | **Pairing standby mode.** Press [Fn] + [Control] + [1]–[4] to enter pairing mode. |
| ![Pairing Mode](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/LED_Pairing.png) Light blinks quickly in blue (5×/sec) | **Pairing mode.** Keyboard is ready to connect via Bluetooth. |
| ![BT Waiting](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/LED_Connect_BT.png) Light lights up blue, then turns off | **Waiting for Bluetooth device** reconnection. |
| ![USB Waiting](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/LED_Connect_USB.png) All four lights blue, then turn off | **Waiting for USB connection.** |

### When Switching Profiles

| Status | Description |
|--------|-------------|
| ![Profile Switch](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/LED_Profile_01.png) Light blinks in white (1×/sec) | **Profile switching mode.** The light for the current profile blinks. |
| ![Profile Switched](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/LED_Profile_02.png) Light lights up white, then turns off | **Profile switched** to the selected number. |

### When Adjusting Input Devices

| Status | Description |
|--------|-------------|
| ![Speed](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/LED_Spd_01.png) Blue/white lights per speed level | **Pointing stick cursor speed changed.** Lights vary by level (1–4 rough, 1–28 fine). |
| ![PS On](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/LED_PointingStick_ON.png) All four white | Pointing stick temporarily **enabled**. |
| ![PS Off](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/LED_PointingStick_OFF.png) Lights at both ends white | Pointing stick temporarily **disabled**. |
| ![GP Sensitivity](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/LED_GesturePad_sensitivity.png) 1–4 white lights from left | **Gesture pad sensitivity changed.** Low=1, Medium=2, High=3, Highest=4 lights. |
| ![GP On/Off](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/LED_GesturePad_ON_OFF.png) Individual lights on/off per pad | **Gesture pad enable/disable status.** Left to right: left side, front left, front right, right side. Lit = enabled, off = disabled. |

---

## 7. Profiles

You can customize the key layout and save up to four layout profiles to number keys [1] to [4]. HHKB Studio has four layers for each profile. Use the Keymap Tool software to customize layouts and create your own profiles.

### How to Switch Between Profiles

1. Hold down [Fn] and press [C]. The keyboard enters profile switching mode — the LED light for the current profile blinks in white.
2. Press a number key [1]–[4] to switch to that profile.
3. The LED light for the selected profile lights up in white, then turns off.

### How to Check the Profile in Use

Hold down [Fn] and press [C]. The LED light for the current profile blinks in white. Press [Fn] + [X] to exit without changing.

### Factory Default Profiles

| Profile | OS | Description |
|---------|---------|-------------|
| Profile1 | Windows | Key layout optimized for Windows |
| Profile2 | macOS | Key layout optimized for macOS/iOS/iPadOS |
| Profile3 | (Empty) | Available for customization |
| Profile4 | (Empty) | Available for customization |

---

## 8. Bluetooth Connection

Pairing information for up to four Bluetooth devices can be registered to number keys [1]–[4]. You can quickly switch between devices using shortcut keys.

> **Hint:** If your device doesn't support Bluetooth, use a commercially available Bluetooth USB adapter or the provided USB Type-C cable.

### Connecting (Pairing) for the First Time

1. **Turn on** the keyboard by sliding the power switch to the right.
2. **Enter pairing mode.** When no pairing info exists, the keyboard enters pairing mode automatically. The leftmost LED blinks quickly in blue.
3. **Pair with your device** (see OS-specific instructions below).

#### Windows 11

1. Open Settings → Bluetooth & devices → Add device → Bluetooth
2. Select "HHKB-Studio1" from the list
3. A several-digit number for pairing is displayed — enter it on the keyboard and press [Return]
4. When "Connected" appears for HHKB-Studio1, the connection is established

#### Windows 10

1. Open Windows Settings → Devices → Bluetooth & other devices → Add Bluetooth or other device → Bluetooth
2. Select "HHKB-Studio1" from the list
3. Enter the pairing number on the keyboard and press [Return]
4. When "Connected" appears, the connection is established

#### macOS

1. Open System Preferences/Settings → Bluetooth
2. Select "HHKB-Studio1" and enter the pairing number on the keyboard, press [Return]
3. If [Connect] button is available, click it
4. **Switch to Profile2 (macOS):** Press [Fn] + [C], then press [2]

#### iOS / iPadOS

1. Open Settings → Bluetooth
2. Select "HHKB-Studio1" and enter the pairing number, press [Return]
3. **Switch to Profile2:** Press [Fn] + [C], then press [2]

#### Android

1. Open Settings → Connected devices → Pair new device
2. Select "HHKB-Studio1" and enter the pairing number, press [Return]

### Registering an Additional Bluetooth Device

1. Turn on the keyboard.
2. Press [Fn] + [Q] to enter pairing standby mode (LED lights sweep side to side).
3. Press [Fn] + [Control] + [1]–[4] to assign the pairing to a specific number key and enter pairing mode.
4. Follow the OS-specific pairing steps above.
5. Switch to the appropriate profile for your OS if needed.

---

## 9. USB Connection

Connect HHKB Studio to a device with the provided USB Type-C cable for a wired connection. This does not consume battery power (except for self-discharge).

1. Turn on the power by sliding the power switch to the right.
2. **If connected for the first time or was last connected via USB:** The keyboard automatically switches to USB connection. All four LED lights light up in blue, then turn off.
3. **If currently connected or was last connected via Bluetooth:** Press [Fn] + [Control] + [0] to switch to USB connection. All four LED lights will light up in blue, then turn off.

---

## 10. Switching & Deleting Devices

### Switching Between Devices

When turned on, HHKB Studio automatically connects to the last-connected device.

![Switching Bluetooth Devices](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/switch_device_BT_US.png)

#### Switch to Bluetooth device

Press [Fn] + [Control] + [1]–[4] (the number key where the pairing info is registered). The corresponding LED light lights up in blue during connection, then turns off.

#### Switch to USB connection

Press [Fn] + [Control] + [0]. All four LED lights light up in blue, then turn off.

![Switching to USB](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/switch_device_USB_US.png)

#### Check connected device

Press [Fn] + [Control] + [0]. Bluetooth: the light for the device number lights up in blue. USB: all four lights light up in blue.

### Deleting Pairing Information

#### Deleting Individually

1. Press [Fn] + [Q] to enter pairing standby mode (lights sweep side to side).
2. Press [Fn] + [Control], then hold [Delete] and press the number key [1]–[4] for the device to delete.
3. The LED turns off and the keyboard disconnects.
4. Also delete the device from your OS Bluetooth settings.

Press [Return] to reconnect after deletion.

#### Deleting All at Once

1. Press [Fn] + [Q] to enter pairing standby mode.
2. Press [Fn] + [Control], then hold [Delete] and press [0].
3. All pairing information is deleted.
4. Also delete from your OS Bluetooth settings.

---

## 11. Fn (Function) Key & Layers

HHKB Studio has four layers for each profile, activated by the function keys [Fn] (Fn1), [Fn2], and [Fn3].

### Function Key Positions

![Fn Key Positions](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/fn1fn2_US.png)

| Key | Default Position |
|-----|-----------------|
| [Fn] (Fn1) | Right side of the bottom row |
| [Fn2] | Mouse key center button |
| [Fn3] | Not assigned — customizable via Keymap Tool |

### Layer Types

| Layer | Activation | Default Function |
|-------|-----------|-----------------|
| Standard | No Fn key pressed | Normal key input |
| Fn1 layer | Hold [Fn] | F1–F12, PgUp/PgDn, Home/End, arrow keys, Caps Lock, volume controls, and connection key combinations |
| Fn2 layer | Hold [Fn2] (mouse center) | Cursor speed adjustment, gesture pad sensitivity |
| Fn3 layer | Hold [Fn3] | Fully customizable via Keymap Tool |

---

## 12. Fn Key Input Reference Table

To input characters printed on the front side of the key tops, hold down the [Fn] key and press the corresponding key.

| Key | Front Print | Meaning | Win | Mac |
|-----|------------|---------|:---:|:---:|
| [1]–[=] | F1–F12 | Function keys F1 through F12 | ✓ | ✓ |
| (key) | Ins | Insert | ✓ | — |
| (key) | Del | Delete | ✓ | ✓ |
| (key) | Clear | Clear (keypad) | — | ✓ |
| (key) | PS/SRq | Print Screen / System Request | ✓ | — |
| (key) | ScrLk | Scroll Lock | ✓ | — |
| (key) | Pus/Brk | Pause / Break | ✓ | — |
| (key) | Home | Home | ✓ | ✓ |
| (key) | PgUp | Page Up | ✓ | ✓ |
| (key) | End | End | ✓ | ✓ |
| (key) | PgDn | Page Down | ✓ | ✓ |
| (key) | Caps | Caps Lock | ✓ | ✓ |
| Arrow keys | ←↑↓→ | Cursor keys | ✓ | ✓ |
| (key) | VolDn | Volume Down | ✓ | ✓ |
| (key) | VolUp | Volume Up | ✓ | ✓ |
| (key) | Mute | Mute | ✓ | ✓ |
| (key) | Eject | Eject | — | ✓ |
| (key) | Power | Power (turns off connected device) | — | ✓ |

---

## 13. Key Combinations Quick Reference

| Operation | Key Combination | LED Status |
|-----------|----------------|------------|
| Enter pairing mode (first time) | [Fn] + [Q] | Leftmost light blinks blue |
| Register additional pairing | [Fn] + [Q] → [Fn] + [Control] + [1]–[4] | Corresponding light blinks blue |
| Switch to Bluetooth device | [Fn] + [Control] + [1]–[4] | Corresponding light lights blue |
| Switch to USB | [Fn] + [Control] + [0] | All four lights blue |
| Check connection status | [Fn] + [Control] + [0] | Blue lights indicate type |
| Delete individual pairing | [Fn] + [Q] → [Fn] + [Control] + [Delete] + [1]–[4] | Lights turn off |
| Delete all pairing | [Fn] + [Q] → [Fn] + [Control] + [Delete] + [0] | Lights turn off |
| Switch profile | [Fn] + [C] → [1]–[4] | Corresponding light white |
| Check current profile | [Fn] + [C] | Current profile light blinks white |
| Exit pairing standby / profile mode | [Fn] + [X] | — |
| Cursor speed (4 levels) | Mouse center + [1]–[4] | Blue/white lights |
| Cursor speed fine adjust | Mouse center + [↑] / [↓] | Blue/white lights |
| Gesture pad sensitivity | Mouse center + [6]–[9] | 1–4 white lights |

---

## 14. Pointing Stick & Mouse Keys

### How to Operate

![Pointing Stick Position](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/use_PointingStick_US.png)

#### Moving the Cursor

Push the pointing stick with your fingertip in any direction to move the cursor.

![Moving Cursor](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/use_PointingStick_cursor_US.png)

#### Scrolling

Hold down the mouse key center button and push the pointing stick in the desired direction.

![Scrolling](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/use_PointingStick_scroll_US.png)

#### Pointing Stick Button

Press the pointing stick straight down to perform a mouse middle-click.

#### Mouse Key Operations

| Button | Action | Result |
|--------|--------|--------|
| Left button | Press once | Left-click |
| Left button | Press twice quickly | Double-click |
| Left button | Hold and move pointing stick | Drag |
| Right button | Press once | Right-click |
| Center button | Hold | Scroll mode (move pointing stick to scroll) |
| Center button | Functions as [Fn2] | Activates Fn2 layer key combinations |

> **Note:** The pointing stick cursor may drift or lag when first used after power on, after being enabled, when used with excessive force, after prolonged use, or during temperature changes. Wait a few seconds without touching the pointing stick, then try again, or restart the keyboard.

### Changing the Cursor Speed

![Speed Adjustment Keys](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/fn2_Spd_US.png)

Default speed: Speed 1. Setting range: 4 levels (rough) or 28 levels (fine).

| Key Combination | Speed | LED Status |
|----------------|-------|------------|
| Mouse center + [1] | Speed 1 (slow) | ![Speed 1](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/LED_Spd_01.png) Leftmost light white |
| Mouse center + [2] | Speed 2 | ![Speed 2](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/LED_Spd_02.png) Left blue + second white |
| Mouse center + [3] | Speed 3 | ![Speed 3](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/LED_Spd_03.png) Left two blue + third white |
| Mouse center + [4] | Speed 4 (fast) | ![Speed 4](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/LED_Spd_04.png) Left three blue + rightmost white |
| Mouse center + [↑] | Increase by 1 step | ![Fine Adjust](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/LED_Spd_increment.png) Fine adjustment (28 levels) |
| Mouse center + [↓] | Decrease by 1 step | Fine adjustment (28 levels) |

### Changing the Scrolling Direction

Use DIP switch SW4 on the base of the keyboard:

| SW4 Position | Scrolling Behavior |
|-------------|-------------------|
| Up (ON) | **Reverse scrolling:** Opposite direction to the pointing stick push |
| Down (default) | **Natural scrolling:** Same direction as the pointing stick push |

### Enabling/Disabling

**DIP switches:** SW1 controls mouse keys (Up=disabled, Down=enabled). SW3 controls pointing stick (Up=disabled, Down=enabled).

**Key operation (temporary):** Configurable via Keymap Tool. Settings are not saved — power cycling restores DIP switch settings.

---

## 15. Gesture Pads

The gesture pads are four touch-sensitive pads on the sides of the keyboard (two on the front, one on each side). Slide your finger on a pad to activate the assigned function.

![Gesture Pad Positions](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/use_GesturePad_US.png)

> **Note:** When lifting or moving the keyboard while it is turned on, hold it with both hands to prevent unintended gesture pad activation. If using a palm rest, leave a gap between the palm rest and keyboard.

### Default Gesture Pad Assignments

![Gesture Pad Slide Operations](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/use_GesturePad_slide_US.png)

| Position | Direction | Default Function |
|----------|-----------|-----------------|
| Front left | Slide left/right | Left/Right arrow keys |
| Front right | Slide left/right | Switch foremost window (Alt+Tab / Cmd+Tab) |
| Left side | Slide forward/backward | Up/Down arrow keys |
| Right side | Slide forward/backward | Scroll up/down |

### Adjusting the Sensitivity

Default: Medium. Setting range: 4 levels.

| Key Combination | Sensitivity | LED Status |
|----------------|-------------|------------|
| Mouse center + [6] | Low | 1 white light (leftmost) |
| Mouse center + [7] | Medium | 2 white lights from left |
| Mouse center + [8] | High | 3 white lights from left |
| Mouse center + [9] | Highest | All 4 white lights |

### Enabling/Disabling

**DIP switch:** SW2 Up (ON) = all gesture pads disabled. SW2 Down = all enabled.

**Key operation (temporary):** Configurable via Keymap Tool. Each pad can be toggled individually. LED indicators show status (left to right: left side, front left, front right, right side — lit = enabled, off = disabled).

**Keymap Tool:** Each gesture pad can be enabled/disabled individually, and settings are saved to the keyboard.

---

## 16. Changing the Keymap (Keymap Tool)

Use the dedicated Keymap Tool software to change the key layout, register shortcuts, and change gesture pad movements.

### What You Can Customize

| Category | Details |
|----------|---------|
| Applicable range | Keys, mouse keys, and gesture pad slide operations |
| Basic key functions | Standard keyboard keys, media keys, screen brightness, scroll/wheel operation |
| Device functions | Mouse clicks, enable/disable gesture pads & pointing stick, cursor speed, gesture sensitivity, profile switching, connection switching |
| Shortcut keys | Single key combination shortcuts assigned to a single key |
| Macro keys | Up to 32 sequential key operations assigned to a single key |

### Getting Started

1. Visit the **HHKB Studio web portal:** [https://happyhackingkb.com/global/studio/portal/](https://happyhackingkb.com/global/studio/portal/)
2. Connect HHKB Studio to your device via USB.
3. Access Keymap Tool from the web portal using a compatible web browser (Chrome recommended).

> **Important:** Keymap Tool works only with a USB connection. An internet connection is required to access the web portal.

---

## 17. Replacing Parts

> **Warning:** Replace parts at your own risk. Parts may be damaged during replacement. Read the procedures carefully.

### Replacing Key Tops

Key tops can be replaced with PFU optional parts or compatible third-party parts. Only parts designed for HHKB Studio are compatible (Professional series parts will **not** fit).

![New Key Top](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/keytop.png)

![Remover Tool](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/kougu.png)

**Procedure:**

1. Prepare a new key top and a remover tool.
2. Turn off the keyboard.
3. Insert the remover tool under the key top and pull straight upward to remove it.

![Inserting the Remover](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/replace_keytop_01.png)

![Removing the Key Top](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/replace_keytop_02.png)

4. Place the new key top on the key switch and press down firmly until it clicks.

![Installing the Key Top](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/replace_keytop_03.png)

#### Key Top Size Reference

![Key Top Size Chart](https://happyhackingkb.com/manual/studio/ug-us/en/ug/images/keytop_size_US.png)

### Replacing Key Switches

Key switches can be replaced with PFU optional parts or compatible third-party parts. Only HHKB Studio switches are compatible — Professional series are **not** replaceable. The procedure covers both standard key switches and mouse key switches. Follow the detailed instructions carefully to avoid damage.

### Replacing the Pointing Stick Cap

The pointing stick cap can be replaced with the spare cap supplied with the keyboard.

1. Pull the pointing stick cap straight upward to remove it.
2. Align the hole on the new cap with the protrusion on the keyboard and push it firmly to the bottom.

---

## 18. Keyboard Specifications

| Item | Specification |
|------|--------------|
| Key specification | Mechanical / Step sculpture / Key pitch: 19.05 mm (0.75 in.) |
| Ambient temperature | 5 to 35°C (41 to 95°F) |
| Ambient humidity | 20 to 80% RH (non-condensing) |
| Dimensions | 308 mm (W) × 132 mm (D) × 41 mm (H) / 12.13 × 5.20 × 1.61 in. |
| Weight | Approx. 840 g / 1.85 lb (without batteries) |
| Connection method | Bluetooth wireless; USB 2.0 Full Speed (Type-C) |
| Bluetooth standard | Bluetooth 5.0 (LE) Class 2 |
| Bluetooth profile | HOGP (HID over GATT profile) |
| Radio frequency | 2.4 GHz band, GFSK modulation |
| Wireless range | Approx. 10 m (no magnetic objects nearby) |
| Battery life | Approx. 3 months (with AA alkaline; varies by usage) |
| Required batteries | 4× AA (alkaline, manganese, or NiMH rechargeable) |

### OS Compatibility

Windows, macOS, iOS, iPadOS, Android, visionOS. For Bluetooth, device must support Bluetooth 5.0 (LE) Class 2.

---

## 19. Cleaning

When the keyboard is dirty, wipe it with a soft, dry cloth. For stubborn dirt, wipe with a cloth moistened with a small amount of mild detergent. **Do not use volatile liquids such as alcohol** — they may damage the product in quality and color.

---

*© PFU Limited 2023–2024. Happy Hacking Keyboard is a trademark of PFU Limited. Microsoft and Windows are trademarks of the Microsoft group of companies. macOS, iPadOS, and visionOS are trademarks of Apple Inc. The Bluetooth® word mark and logos are registered trademarks of Bluetooth SIG, Inc. Android is a trademark of Google LLC.*