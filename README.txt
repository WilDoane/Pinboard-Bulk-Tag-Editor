This is a very rough v0.0.0.1 version of a bulk tag editor for http://Pinboard.in

Simply open the HTML file locally and you'll be prompted for your username/password by the Pinboard site (the code does not ask for your credentials or use them in any way. The username/password request is coming from the Pinboard server.)

Edit any tags you want to change. If you enter an already existing tagname, Pinboard takes care of folding the changed items into the existing set.

When ready, click the "UPDATE CHANGED TAGS" link at the top of the page.

You'll see a div showing the progress of the update. Updates are rate-limited to 1 change every 2 seconds, to comply with Pinboard's API terms of use.