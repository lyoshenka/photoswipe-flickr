# photoswipe-flickr

Show a Flickr album as a slideshow using [Photoswipe](http://photoswipe.com/).

## Usage

### Get a Flickr API key (if you don't already have one)

[Create a new api key](https://www.flickr.com/services/apps/create/apply/?). You only need the `key` part, not the `secret`.

### Get the album ID



### Check the demo

Look at [the demo](https://github.com/lyoshenka/photoswipe-flickr/blob/master/demo.html) for a very simple example of how to set everything up. The
important parts are to include `photoswipe-flickr.js` after you include the photoswipe JS, and then to call `photoswipeFlickr()` with your API key and
album id (and options for the photoswipe gallery, if you want). There's also a bit of extra code to reopen the gallery after it has been closed, but
that's optional.

## Bugs/Feedback

Email me: lyoshenka@gmail.com
