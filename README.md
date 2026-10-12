# NiceNav

A minimal patch for Firefox that unifies the top bar interface layout. 

## What it does
**NiceNav** overrides default firefox styling to make the window navigation controls (Minimize, Maximize, Close) look exactly the same when hovered over as any other button that lives on the browser chrome right next to them.

This only changes windows and linux, since macos uses a completely seperate system (heck  I don't even know if this actually affects Linux, and won't try since I'm not installing Linux to test).

## How to Install
> [!NOTE]
> If you already have a userChrome.css, skip all the steps, just append the code inside this repository's `userChrome.css` to the end of your userChrome.css

1. Open a new tab in Firefox and go to `about:config`.
2. Search for `toolkit.legacyUserProfileCustomizations.stylesheets` and set it to **true**.
3. Go to `about:support` and locate your **Profile Directory** row. Click **Open Folder** (or *Show in Finder* on macOS).
4. Create a folder named `chrome` if it does not already exist.
5. Save this repository's `userChrome.css` file directly inside that `chrome` folder.
6. Restart Firefox.
