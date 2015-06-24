
**Doesn't work anymore since Yellow was updated**

# Musiclist snippet

List of music (ogg/mp3) and play them with `<audio>` tag.

1. Download and install [Yellow](https://github.com/markseu/yellowcms).
2. Download and install [include plugin](https://github.com/markseu/yellowcms-extensions/tree/master/plugins/include).
3. Download [musiclist.php](musiclist.php?raw=true), copy it into your `system/themes/snippets` folder.
4. Create a new folder 'music' in your `media` folder.
5. Add .ogg & .mp3 files to your `media/music` folder.

Now you can include the snippet by editing your page: 

    [include snippet musiclist music/.*(ogg|mp3)]

By the way, you can use this CSS in your theme:

    .content .musiclist { margin:0; padding:0; list-style:none; width:100%; }  
    .content .musiclist li {margin:0; padding:0.5em; }  
    .content .musiclist li h5 {margin:0; padding:0; }`
