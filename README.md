# photoswipe-flickr

Show a Flickr album as a slideshow using [Photoswipe](http://photoswipe.com/).

## Usage

### Get a Flickr API key (if you don't already have one)

[Create a new api key](https://www.flickr.com/services/apps/create/apply/?). You only need the `key` part, not the `secret`.

### Get the album ID

Open the photoset in Flickr, then look at the URL. It should look something like `https://www.flickr.com/photos/your_name/sets/7225764364613184/`. That
string of numbers at the end is the album ID.

### Check the demo

[Live demo here](http://lyoshenka.github.io/photoswipe-flickr/demo.html#key=4ca3b9ef09d104c57ecd6f017d7d6c42&aid=72157648364623184)

Look at the [source for the demo](https://github.com/lyoshenka/photoswipe-flickr/blob/master/demo.html) for a very simple example of how to set everything up. The
important parts are to include `photoswipe-flickr.js` after you include the photoswipe JS, and then to call `photoswipeFlickr()` with your API key and
album ID (and options for the photoswipe gallery, if you want). There's also a bit of extra code to reopen the gallery after it has been closed, but
that's optional.

Here's [another demo](http://i.grin.io/iceland/slideshow.html) of the slideslow in action.

## Bugs/Feedback

Email me: alex@grin.io
