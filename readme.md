Group: Markup Masters
Andy Thai
Magdalena Ninette
John Hurst

Writing the version using the JQuery library ended up being pretty much
the same and not any easier than writing the VanillaJS version. 

The file size of the JQuery version is 337.4KB while the VanillaJS version
is 254.6KB. 

The load times of the JQuery version is 198ms while for the VanillaJS
version it is 166ms. 

We used TrackJS to automatically log errors and to check if javascript is loaded in the user browser, 
and if not, it outputs an error to us.

When attempting to load our page as an extension. Chrome does not recognize icons if we list them as an array
But if we do not list them as an array, the page does not pass the lighthouse test. We left it as an array,
so that it would pass the test.

Screenshots are available at:
https://b-b2dcd.firebaseapp.com/markup_masters_trackjs.png
https://b-b2dcd.firebaseapp.com/trackjs1.png
https://b-b2dcd.firebaseapp.com/trackjs2.png