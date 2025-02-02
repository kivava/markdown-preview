# Chrome Markdown Extension

Automatically parses markdown files  into HTML. This is useful
if you're writing markdown (ultimately targeting HTML) and want a quick
preview.


# Usage

1. Install extension from [webstore][] (creates no new UI)
2. Check "Allow access to file URLs" in `chrome://extensions` listing: ![fileurls](http://i.imgur.com/qth3K.png)
3. Open local or remote .md file in Chrome.
4. See nicely formatted HTML!

# Note

If you cannot open the files in the chrome, it might due to the file extiension. 
Change the file extension from .md to .mkd or markdown and try again. Previewing the markdown file might be worked.

# Thanks

Thanks to Kevin Burke for his [markdown-friendly stylesheet][style],
to John Fraser for his [JavaScript markdown processor][showdown] and to
Swartz and Gruber for [Markdown][md].

[webstore]: https://chrome.google.com/webstore/detail/jmchmkecamhbiokiopfpnfgbidieafmd
[style]: http://kevinburke.bitbucket.org/markdowncss
[showdown]: https://github.com/coreyti/showdown
[md]: http://en.wikipedia.org/wiki/Markdown
