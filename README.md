<div align="center">

### General View
![ScreenShot](./scrennshots/general-view.png)

### Floating Navigation
![ScreenShot of Floating navbar](./scrennshots/floating-navigation.png)

### Audio Icon
![ScreenShot of media icon in tab](./scrennshots/audio-icon.png)

### Private Mode
![Private mode image](./scrennshots/private-mode.png)

</div>


# Firefox-minimal.css

Minimalistic ***oneliner*** firefox userChrome.css. Focus on keyboard shortcuts.

## Changes

 - Hide some context menu item
 - Hide Tab cross icon, shows when hover the tab
 - Now playing audio icon adjust, shows along favicon ( *don't need for firefox v136+* )
 - Floating navbar in center
 - Few default icon change ( *backward, forward, extension, etc* ) 
 - Hide most of the unnecessary items
 - And many more

 ## Installing
 
 Firstly write `about:config` urlbar  and enable `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`.

- Then open your profile folder (you can find the location in `about:profiles` root directory).
- Copy `chrome` folder to that root directory.
- This should work with any theme and density in Firefox.
- It meant for `compact density` (enbale `browser.compactmode.show` to `true` in `about:config`)

> the `user.js` same user.js from [betterfox](https://github.com/yokoffing/Betterfox)

## Contribution Guidelines

Thank you for your interest in this repository! Please note that this project is primarily for **personal use**, and I generally do not accept pull requests (PRs) for new features or changes. However, I welcome feedback, bug reports, and contributions that improve the codebase or fix issues.

### How You Can Contribute:
1. **Report Bugs:**
   - If you encounter any issues or bugs with the current code, please open an **Issue** on GitHub. Provide as much detail as possible, including steps to reproduce the problem.

2. **Feature Requests:**
   - While I appreciate your ideas, I am not currently accepting feature requests for this repository. This project is tailored to my personal needs, and I already have a clear roadmap for its development.

3. **Pull Requests for Improvements and Bug Fixes:**
   - If you have a pull request that improves the codebase (e.g., optimizations, refactoring, or bug fixes), you are welcome to submit it. Please ensure that your PR is well-documented and aligns with the purpose of this repository.

4. **Forking:**
   - You are welcome to fork this repository and use it for your own purposes. However, please note that I will only merge PRs that align with the goals of this project.

#### Why Limited Pull Requests?
This repository is maintained for **personal use**, and I want to keep the codebase aligned with my specific requirements. While I generally do not accept PRs for new features, I welcome contributions that improve the exiting codebase or fix bugs. If you have any questions, feel free to open an **Issue** to discuss your proposed changes before submitting a PR.

Thank you for understanding!

## Keyboard Shortcuts
Shortcuts for general use
- New Tab = ` ctrl + T `
- Close Tab = ` ctrl + W `
- Open tab in new window = ` ctrl + N `
- Open last close tab = ` ctrl + shift + T `
- Close all tab = ` ctrl + shift + W `
- Focus on address bar = ` ctrl + L `
- Cycle tabs = ` ctrl + tab ` (setting< general < tab)

<details>
<summary> <h3>Extra keyboard shorcuts</h3></summary><br>

- Show menu bar  = ` alt `
- Bookmark sidepanel = ` ctrl + B `
- Bookmark Library = ` ctrl + shift + O `
- Show / Hide bookmark bar = ` ctrl + shift + B `
- History sidepanel = ` ctrl + H `
- Donwloads = ` ctlr + J `
- Find in page = ` ctrl + F `
- Find next word = ` ctrl + G `
- Open defautl search open = ` ctrl + E `
- about:addons = ` ctrl + shift + A `

</details>

## Credits
Based off [userChrome.css](https://github.com/ericmurphyxyz/userChrome.css) and [FirefoxCSS-Darknight](https://github.com/BriLHR/FirefoxCSS-Darknight)
