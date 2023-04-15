![Classic Power Menu](https://i.imgur.com/DonYhMA.png)

This is a fork of [Classic Power Menu](https://github.com/KieronQuinn/ClassicPowerMenu) by [Kieron Quinn](https://github.com/KieronQuinn) so please support the original project and developers for making this essential app.

This fork is basically just some changes that I personaly wanted to make to the original project. See the tweaks bellow.

## My Tweaks
1. Google Pay cards are always blurred.
2. Add NFC toggle, Torch Toggle to power menu settings
3. Power Menu is always hidden on lockscreen.
4. Google Wallet is always hidden on lockscreen.
5. Non Monet colours changed to be dark, transparent and red. Red outline for cards. All icons etc. See screenshots bellow (doesn't look good with monet enabled).
6. No black background when power menu shortcuts are minimised. It is completely transparent now.
7. Changed device controls to sit on top of Google Wallet as they are used more frequently.
8. All default settings are set to what I use. So when you install the tweaks it should look like the screenshots bellow.

## About original Project
Classic Power Menu is a Power Menu Replacement for Android 11+, with the main aim being restoring power menu options (Device Controls & Quick Access Wallet) on Android 12.

**Classic Power Menu Requires root access to function, it is not possible without root**

**[Please read the FAQ before downloading or creating an issue](https://github.com/KieronQuinn/ClassicPowerMenu/blob/main/app/src/main/assets/faq.md)**

[![Crowdin](https://badges.crowdin.net/classicpowermenu/localized.svg)](https://crowdin.com/project/classicpowermenu)

## Features

- Up to 10 power options in the Power Menu, including the non-stock options of Screenshot, Reboot Recovery and Reboot Bootloader
    - Fully customisable, including rearranging and hiding buttons you don't use

- Quick Access Wallet in the Power Menu, accessible while locked or unlocked
    - Optional blurring of card numbers while locked
    - Optional showing of loyalty cards, restoring a previous feature from Android 10 which was removed. Loyalty cards' codes can be shown while locked and without needing to open Google Wallet, if you wish.
    
- Device Controls in the Power Menu, accessible while locked or unlocked
    - Optional ability to interact with controls while locked, without requiring authentication
    
- Material You inspired theme, using Monet colours and background blur on the Power Menu

- Xposed is not required, interception of the power button is done via Accessibility Service, with only normal root required
    - An optional Xposed module is included, which can react quicker than the Accessibility Service

## My Tweaks Screenshots
![screenshot 1](https://github.com/ArtiomSu/AndroidClassicPowerMenuTweaks/blob/tweaks/.screenshots/1.png) ![screenshot 2](https://github.com/ArtiomSu/AndroidClassicPowerMenuTweaks/blob/tweaks/.screenshots/2.png) ![screenshot 3](https://github.com/ArtiomSu/AndroidClassicPowerMenuTweaks/blob/tweaks/.screenshots/3.png)
### Lock Screen
![screenshot 4](https://github.com/ArtiomSu/AndroidClassicPowerMenuTweaks/blob/tweaks/.screenshots/4.png)
## Original Project Screenshots

![Classic Power Menu](https://i.imgur.com/rhm4bqvl.png) ![Settings](https://i.imgur.com/rAG0htEl.png)

![Loyalty Cards in Pay](https://i.imgur.com/eKOI84El.png) ![Showing a Card](https://i.imgur.com/PR6uqUnl.png)

## Download

[Download the original latest release from the Releases page](https://github.com/KieronQuinn/ClassicPowerMenu/releases)

[Download my tweaks from the Releases page](https://github.com/ArtiomSu/AndroidClassicPowerMenuTweaks/releases)

### Content Creators

If you are making a video or article about Classic Power Menu, you will want to hide your card numbers. Enable the developer options in Classic Power Menu by triple tapping the "About" option, and enable Content Creator Mode. This will always blur your card numbers and will show a fake QR code for loyalty cards, keeping your data safe.
