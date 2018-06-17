# paperspaceBrowserStart

Start your [Paperspace](http://www.paperspace.com/) cloud computer using a regular web browser (e.g. on a Fire TV stick) by accessing a simple website, without entering your credentials or clicking through menus.

## Reason
I use my Paperspace machine for cloud gaming on my Amazon Fire TV Stick. I wanted to be able to boot the machine without using my regular computer, smartphone or entering my credentials anywhere, so I created this simple script. It uses the Paperspace API to send a start command to the desired machine.

## Instructions
1. Get an API key in the Paperspace console.
2. Upload `index.html` to your server or webspace.
3. Add the machine id and the api-key to the URL of the file (e.g. `http://myserver.com/index.html?machine=ab1c2n345&key=1234567890`).
4. (Save this URL to your bookmarks to call it easily. On a Fire TV, use the [Bookmarker App](http://www.aftvnews.com/introducing-my-new-bookmarker-apps-for-the-amazon-fire-tv-load-websites-in-just-one-click-from-the-home-screen/).)
