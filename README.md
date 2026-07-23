<p align="center">
  <img src="./assets/Elixir-icon.png" alt="Elixir Browser Logo" width="256" height="256"/>
</p>

<p align="center">
  <a href="https://github.com/SF-FLAM/ElixirBrowser/releases"><img src="https://img.shields.io/badge/Download-Releases-brightgreen?style=for-the-badge"></a>
  <a href="https://github.com/sponsors/SF-FLAM"><img src="https://img.shields.io/badge/GitHub-Sponsor-EA4AAA?style=for-the-badge&logo=githubsponsors"></a>
  <a href="https://buymeacoffee.com/sf_flam"><img src="https://img.shields.io/badge/Buy_Me_A_Coffee-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=black"></a>
</p>

# Elixir Browser

> **[English](README.md) | [日本語 (Japanese)](README.ja.md)**

<br>

Elixir is a Chromium-based browser with full extension support for Android.  
Inspired by Kiwi Browser, this project focuses on providing extension compatibility, unique UI improvements, and refining inefficient behaviors.  

**Note:** This project has no affiliation with the developers or the team behind Kiwi Browser.  
Elixir is an independent fork built directly from the official Chromium source code. No code or binaries from other browsers (such as Kiwi) have been reused in this project.

Most Google-dependent features have been removed to block unnecessary communications.  
However, high-utility features such as Google Translate and Search Suggestions remain available as optional toggles to ensure user convenience.

<br>

<p align="center">
  <img src="./assets/Screenshot_0_Elixir_Browser.png" alt="screenshot0" width="32%">
  <img src="./assets/Screenshot_1_Elixir_Browser.png" alt="screenshot1" width="32%">
  <img src="./assets/Screenshot_2_Elixir_Browser.png" alt="screenshot2" width="32%">
</p>

<br>

## Key Features

*   **Extension Support**:
    * Install and use the same extensions as desktop Chrome directly from the Chrome Web Store.

*   **Enhanced UI**:
    * **Always-on Tab Bar option**
    * **Bottom Toolbar option**
    * **Removal of unnecessary UI elements**
    * **Google Translate button added to the main menu**
    * **Custom Speed Dial implementation**
    * **Etc...**

*   **Customizable Gestures**
    *   Freely map various actions to gestures for ultimate control and browsing comfort.

*   **Behavioral Improvements**:
    * **Close tab via back gesture**: When there is no remaining back history, the back gesture closes the tab instead of returning to the Home/New Tab Page.
    * **Etc...**

*   **Privacy Protection**:
    * Blocked multiple data transmissions found in original Chromium.

*   **Long-term Development**:
    *   Periodically tracks the latest Chromium releases and provides maintenance on a best-effort basis.

<br>

## Support & Solemn Oath

Elixir Browser is a project developed solely by an individual.  
**It is completely non-profit. I solemnly swear that this app does not—and will never—include affiliates, personal data collection, or paid content for monetization.**

That said, personal support is always welcome! 🤑  

Modifying and maintaining Chromium is an incredibly grueling task.  
To be honest, it is quite a struggle for a solo developer. To ensure the long-term sustainability of this project, please consider supporting me (the poor dev).  
↓↓↓  
  
<<**[❤️ GitHub Sponsors](https://github.com/sponsors/SF-FLAM)**>>

<<**[☕ Buy Me A Coffee](https://buymeacoffee.com/sf_flam)**>>  

<br>

## Download

All releases and APK versions are available at the link below:


<<**[Releases](https://github.com/SF-FLAM/ElixirBrowser/releases)**>>

<br>

## History & Roadmap

Detailed development history and planned future features can be found here.  
Since I originally built this as a personal replacement for Kiwi, the selection of features reflects my own preferences.  
  
**The names of all modified and newly added files are listed in the 'Modified Files' section. Any file not on this list is vanilla Chromium.**  

Most unnecessary Google communications have been removed at the component level.  
This is less about "privacy activism" and more a result of aggressive optimization for a lightweight experience.  
Consequently, some features have been retained because removing them could break core browsing functionality. These are scheduled for removal in future updates, subject to rigorous testing.  
  
<<**[History](./CHANGELOG.md)**>>

<br>

## Bug Reports

If you encounter any issues, please report them via GitHub Issues. I will do my best to improve the app (probably). 
    
<<**[Issues](https://github.com/SF-FLAM/ElixirBrowser/issues)**>>

<br>

## Q & A

Q : **Is this browser stable enough for daily use?**  
A : I personally use Elixir as my main browser every day and am satisfied with its stability, but your experience may vary.  
Since this is a solo project, updates may occasionally contain critical bugs, crashes, or broken features. In particular, bugs that do not occur on my own devices are often overlooked. Please use this browser with the understanding that it is a work-in-progress, and use it at your own risk.  
<br>
Q : **What are the system requirements?**  
A : It follows the base Chromium specifications. **Android 10+ (ARM64)** is needed. There is no 32-bit version available.  
**That said, please note that compatibility is not guaranteed, as I can only test on my own devices.**  
<br>
Q : **Why isn't this open source? Show me the code!**  
A : I aim to make it open source in the future.  
**At the moment, all code comments are written in Japanese, so I want to translate them into English before publishing.**  
My priority is on updates, and I don't have the bandwidth for code management yet, so I plan to proceed slowly.  
In any case, I promise I won't take the code to my grave. Even if the code is still messy, I will release everything if I ever decide to shut down the project.  
<br>
Q : **Is there a built-in password manager?**  
A : No. It utilizes the password manager specified in your Android system settings.  
While Google Password Manager is the standard, warnings may appear on non-major browsers like Kiwi or Elixir depending on the Android version, **but password input itself works without issues.**  
Personally, I recommend using **Bitwarden** (the standalone app, not the extension). I have confirmed that passkeys work perfectly with it.
