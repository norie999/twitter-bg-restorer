# Twitter Background Restorer

A temporary solution to the web twitter's very good decision to make the home background a horrible grey colour. Lol

[Download .crx file](https://github.com/Autophagy/twitter-bg-restorer/blob/master/twitter-bg-restorer.crx?raw=true)

## Installation

Go to [chrome://extensions/](chrome://extensions/) and drag the .crx file into it. If it refuses to install because its not from THE OFFICIAL GOOGLE STORE then clicking the checkbox that says 'Developer Mode' should work, I think.  Then click on 'Options' below the extension.

This is where it gets a little unwieldy, but whatever. Go to a link that contains your tweet (so you can see your background), press ctrl+u to view the source.

Ctrl+f for 'js-user-style-bg-img'. There should be a bit that says `body.user-style-<YOUR USERNAME>`. Inside this there should be a css rule that says `background-image: url(X)`.

Copy and paste this URL for your background image into the extension settings, and choose whether it is a tiled image or not. You can also just set it to use a less horrible background colour by filling in the colour textbox with a hex value, and changing the dropdown to 'background colour'. Refresh twitter and it should work

until twitter gets rid of backgrounds entirely but hey
