# I have move to another userChrome, which doesn't have one line style minimal interface. So this repo may not update anytime soon. if i have time and look into it.

<p align="center">
 
<img src="./scrennshots/img0.png" alt="ScreenShot"/>
<img src="./scrennshots/img1.jpg" alt="ScreenShot of Floating navbar"/>
<img src="./scrennshots/img2.jpg" alt="ScreenShot of media icon in tab" />
</p>


# Firefox-minimal.css

Minimalistic firefox userChrome.css. Focus on keyboard shortcuts.

## Changes
Forgot most of them, what make the difference from other
 - Hide some context menu item
 - Hide Tab cross icon, shows when hover the tab
 - Now playing media icon adjust, shows along favicon
 - Floating navbar in center

### Known Issues
- dark and light mode doesn't work. [#2](https://github.com/farhanspace/Firefox-minimal.css/issues/2)
- after 132.b01 update the newtab plus icon disappear. [#1](https://github.com/farhanspace/Firefox-minimal.css/issues/1)

 ## Installing
Firstly enable the option `toolkit.legacyUserProfileCustomizations.stylesheets` from your `about:config` or `user.js` file.
- Then open your profile folder (you can find the location in `about:profiles` root directory).
- Create the folder chrome inside of it, and place the `userChrome.css` file inside.
- This should work with any theme and density in Firefox.(didn't tested fully)
- It meant for `compact density` (enbale `browser.compactmode.show` in `about:config`)

## Keyboard Shortcuts
Shortcuts for general use
- New Tab = ` ctrl + t `
- Close Tab = ` ctrl + w `
- Open tab in new window = ` ctrl + n `
- Open last close tab = ` ctrl + shift + t `
- Close all tab = ` ctrl + shift + w `
- Focus on address bar = ` ctrl + l `
- Cycle tabs = ` ctrl + tab ` (setting< general < tab)

<details>
<summary> Extra keyboard shorcuts</summary>

- Open menu bar  = ` alt `
- Bookmark sidepanel = ` ctrl + b `
- Bookmark Library = ` ctrl + shift + o `
- Show / Hide bookmark bar = ` ctrl + shift + b `
- History sidepanel = ` ctrl + h `
- Donwloads = ` ctlr + j `
- Find in page = ` ctrl + f `
- Open defautl search open = ` ctrl + e `
- about:addons = ` ctrl + shift + a `

</details>

## Credits
Based off [userChrome.css](https://github.com/ericmurphyxyz/userChrome.css) and [FirefoxCSS-Darknight](https://github.com/BriLHR/FirefoxCSS-Darknight)
