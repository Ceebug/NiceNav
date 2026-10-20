# NiceNav

A minimal patch for Firefox that unifies the top bar interface layout. 

## What it does
**NiceNav** overrides default firefox styling to make the window navigation controls (Minimize, Maximize, Close) look exactly the same when hovered over as any other button that lives on the browser chrome right next to them.

> [!IMPORTANT]
> **NiceNav is *not* supported on macOS**<br>
> This is because the macOS navigation controls cant have this applied to them and even if they could, it would look bad.

## Comparison

### Before
![What the window navigation controls look without NiceNav.](comparisons/before.avif)
### After
![What the window navigation controls look like with NiceNav.](comparisons/after.avif)


## How to Install
> [!NOTE]
> If you already have a `userChrome.css`, skip all the steps, just append the code inside this repository's `userChrome.css` to the end of your `userChrome.css`.

1. Open a new tab in Firefox and go to `about:config`.
2. Search for `toolkit.legacyUserProfileCustomizations.stylesheets` and set it to **true**.
3. Go to `about:support` and locate your **Profile Directory** row. Click **Open Folder** (or *Show in Finder* on macOS).
4. Create a folder named `chrome` if it does not already exist.
5. Save this repository's `userChrome.css` file directly inside that `chrome` folder.
6. Restart Firefox.

> [!TIP]
> **Don't be an idiot**<br>
> Make sure to save any work you care about.
