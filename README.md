# Sidebery Configuration
Install from [here](https://addons.mozilla.org/it/firefox/addon/sidebery/).

## 1. Enable Firefox features

Go to `about:config` and set all of the following to `true`:
```
    toolkit.legacyUserProfileCustomizations.stylesheets
    layers.acceleration.force-enabled
    gfx.webrender.all
    gfx.webrender.enabled
    layout.css.backdrop-filter.enabled
    svg.context-properties.content.enabled
    
    # LINUX ONLY - WORKAROUND FOR BAR HIDING ON DRAG EVENT
    widget.gtk.ignore-bogus-leave-notify = 1
```

## 2. Write your userChrome.css

1. Find your Firefox profile folder (`about:support` --> "Profile Folder") 
2. Create a folder named `chrome` inside it.
3. Paste the content you found into the `chrome` folder of this repository

## 3. Edit Sidebery settings
Open the Sidebery Settings and import the settings you found into the `sidebery` folder of this repository.

## Links
- https://github.com/mbnuqw/sidebery/wiki/Sidebery-Styles-Snippets#tab-favicons-on-the-right
- https://www.reddit.com/r/FirefoxCSS/comments/rmi8dg/yet_another_sidebery_setup/
- https://github.com/CristianDragos/FirefoxThemes/tree/master/Simplify%20Darkish/Simplify%20Purple
- https://firefox-source-docs.mozilla.org/devtools-user/browser_toolbox/index.html
