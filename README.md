Blend-Shortcode
===============

WordPress plugin for converting Blend.io project URLs into embedded players.


## How to use

- Download the [ZIP](https://github.com/Montoya/Blend-Shortcode/archive/master.zip)
- Unzip / extract the folder on your computer
- Upload the folder to your Wordpress plugins directory `wp-content/plugins/`
- Visit the plugins menu in your Wordpress dashboard and click _Activate_

Now you can enter the following into any post: 

```
[blend]https://blend.io/project/54611406124aec59070070c4[/blend]
```

And it will be converted to an embedded player automatically! 

## Optional parameters

You can customize the width of the embed in the shortcode. The widget will fill the width of your post by default, but if you need to give it a fixed with, just add the parameter `width` to the shortcode like this: 

```
[blend width="500"]https://blend.io/project/54611406124aec59070070c4[/blend]
```

You can also set a default width and height to be used for all shortcodes. Just visit the settings page for the plugin (Settings > Blend)
