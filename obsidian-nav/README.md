## Obsidian Portal custom navigation

See this Obsidian Portal docs article for more information:
https://help.obsidianportal.com/article/186-customizing-the-campaign-navigation

See this Obsidian Portal page for a list of all possible icons:
https://opfonticons.obsidianportal.com/wikis/main-page

The HTML snippet `obsidian-nav.html` is a custom navigation bar for the Shadow of the Seer
Obsidian Portal campaign. It adds navigation menu items for two pages that are not part of
the default Obsidian Portal navigation: the "Guilds" page and the "NPCs" page.

You can edit the icons Obsidian shows for the menu items by editing the
`obsidian-nav.html` to change the tags that begin like `icon-` or `op-icon-` to the name
of the icon you want to use. You can find the list of available icons at the page linked
at the top of this README.

When on the icons page, to find the name of the icon you want to use:

1. Open Chrome's Developer Tools (F12)
2. Click the "Elements" tab
3. Click the "Select an element in the page to inspect it" button (Ctrl+Shift+C on PC, or
   Cmd+Shift+C on Mac)
4. Click the icon you want to use
5. Look for the `class` attribute in the HTML element that represents the icon
6. The class name will be something like `op-icon-<icon-name>` or `icon-<icon-name>`
7. Copy the icon  class name and use it in the `obsidian-nav.html` file

### The icons page

![The icons page](iconsPage.png)

### Chrome DevTools browsing the icons page

![Chrome DevTools browsing the icons page](devTools.png)

### Viewing the class name of an icon in Chrome DevTools

![Viewing the class name of an icon in Chrome DevTools](classNames.png)