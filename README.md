# Trailer page

A single static page that plays a YouTube trailer by video id:

    index.html?v=<videoId>          normal player
    index.html?v=<videoId>&mode=bg  muted, looping, no controls

It exists so an app that runs from local files (and so has no web address of
its own) can show trailers: YouTube's embedded player only plays when the page
embedding it can identify itself with an address.

Served with GitHub Pages. No data is collected or stored by this page.
