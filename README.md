# NiceNav

A minimal patch for Firefox that unifies the top bar interface layout. 

## What it does
**NiceNav** overrides default firefox styling to make the window navigation controls (Minimize, Maximize, Close) look exactly the same when hovered over as any other button that lives on the browser chrome right next to them.

```css
.titlebar-buttonbox-container {
  padding: 6px;
  padding-left: 0px;
}
.titlebar-button {
  padding: 8px 16px !important;
  border-radius: 50%;
}
```

## How to Install
1. Open a new tab in Firefox and go to `about:config`.
2. Search for `toolkit.legacyUserProfileCustomizations.stylesheets` and set it to **true**.
3. Go to `about:support` and locate your **Profile Directory** row. Click **Open Folder** (or *Show in Finder* on macOS).
4. Create a folder named `chrome` if it does not already exist.
5. Save this repository's `userChrome.css` file directly inside that `chrome` folder.
6. Restart Firefox.
