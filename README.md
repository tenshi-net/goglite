# GOGlite - A GOG.com Cleanup Filter

GOG, a DRM-free PC games distributor, is a great service and they've made strides toward improving their site's interface and layout. However, the store interface is still pretty messy. There are a lot of redundant elements and self-promotion elements across the site, taking up unnecessary space and making it a bit less enjoyable to navigate the site.

It doesn't remove anything essential, all of the game entries and sections are left untouched, it's purely a means to declutter the interface.

# How to use

There are two ways you can add this. The simplest way is to add the URL of the `goglite.txt` file to your ad blocker's filter lists. Alternatively, you can add a non-updating version by directly copying the data from the file and pasting it as a custom filter rule.

## Brave Shields

Click on the Brave Shields icon in the address bar and selecting the **Filter lists** button at the bottom of that menu. Navigate to **Add custom filter lists** and paste the [URL to the file](https://raw.githubusercontent.com/tenshi-net/goglite/refs/heads/main/goglite.txt) in the text box.

_For the non-updating version:_ copy the data from `goglite.txt`. Navigate to the **Create custom filters** section and enable Developer mode. From there, copy the contents of `goglite.txt` and paste them at the bottom of the **Create custom filters** menu and save your changes.

## uBlock Origin

Open your uBlock settings menu. Navigate to the **Filter lists** tab. Scroll to the bottom, to the section labeled "Import...". Paste [the URL](https://raw.githubusercontent.com/tenshi-net/goglite/refs/heads/main/goglite.txt) into that text box and select **Apply changes**.

_For the non-updating version:_ copy the data from `goglite.txt`. Navigate to the **My filters** tab. Paste the contents of `goglite.txt` to the bottom of the text section. Ensure "Enable my custom filters" is ticked and then **Apply changes**.
