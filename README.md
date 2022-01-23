# colorful-theme

## Add the theme

You can add the Theme through downloading it manually from https://github.com/KurtSchneider0/colorful-theme and pasting it in your `themes/colorful-theme` directory.
You can also clone it into the `themes/colorful-theme` directory using

```
git clone https://github.com/KurtSchneider0/colorful-theme.git themes/colorful-theme
```

## Configure the theme

There isn't much to configure, just edit the following config.toml

```toml
baseURL = 'http://example.org/' # Your URL
languageCode = 'en-us'
title = 'My New Hugo Site' # Name of your site
theme = "colorful-theme"

[menu]
  [[menu.main]]
    name = "Home"
    pre = "home" # name of the icon on https://feathericons.com/
    url = "/"
    weight = 1 # Position in the nav bar
  [[menu.main]]
    name = "Posts"
    pre = "pen-tool"
    url = "/posts/"
    weight = 2
  [[menu.main]]
    name = "Tags"
    pre = "tag"
    url = "/tags/"
    weight = 3
```
