# Build Responsively

## Media Queries

### Media Types

* **all** - Suitable for all devices.
* **print** - Intended for paged material and for documents viewed on screen in print preview mode. Please consult the section on paged media for information about formatting issues that are specific to paged media.
* **screen** - Intended primarily for color computer screens.
* **speech** - Intended for speech synthesizers. Note: CSS2 had a similar media type called 'aural' for this purpose. See the appendix on aural style sheets for details.

### Media Features

* **width** - The width media feature describes the width of the rendering surface of the output device (such as the width of the document window, or the width of the page box on a printer).
* **height** - The height media feature describes the height of the output device's rendering surface (such as the height of the viewport or of the page box on a printer).
* **device-width** - Describes the width of the output device (meaning the entire screen or page, rather than just the rendering area, such as the document window).
* **orientation** - Indicates whether the viewport is in landscape (the display is wider than it is tall) or portrait (the display is taller than it is wide) mode.
* **aspect-ratio** - Describes the aspect ratio of the targeted display area of the output device.

**Level 4 Media Features** (coming soon)

* **update-frequency ** - Used to query the ability of the output device to modify the apearance of content once it has been rendered.
* **overflow-block** - Describes the behavior of the device when content overflows the initial containing block in the block axis.
* **overflow-inline** - Describes the behavior of the device when content overflows the initial containing block in the inline axis.
* **(any-)pointer** - Identical to the pointer media features, but corresponds to the union of capabilities of all the pointing devices available to the user.
* **(any-)hover** - identical to the hover media features, but corresponds to the union of capabilities of all the pointing devices available to the user.
* **light-level** - Used to query about the ambient light-level in which the device is used, to allow the author to adjust style of the document in response. 
* **scripting** - Used to query whether scripting languages, such as JavaScript, are supported on the current document.


## Further Reading

* [Responsive Web Design](http://alistapart.com/article/responsive-web-design), *A List Apart*
* [Structuring & Serving Styles for Older Browsers](http://seesparkbox.com/foundry/structuring_and_serving_styles_for_older_browsers), *Ethan Muller, Sparkbox*
* [Object Oriented CSS](http://www.smashingmagazine.com/2011/12/12/an-introduction-to-object-oriented-css-oocss/), *Louis Lazaris, Smashing Magazine*
* [Element Queries](http://www.xanthir.com/b4PR0), *Tab Atkins*
* [Viewport Sized Typography](http://css-tricks.com/viewport-sized-typography/), *Chris Coyier, CSS-Tricks*
* [Srcset and Sizes](http://ericportis.com/posts/2014/srcset-sizes/)
* [Creating Intrinsic Ratios for Video](http://alistapart.com/article/creating-intrinsic-ratios-for-video), *A List Apart*

## Resources

* [Sass News](https://twitter.com/sassnews)
* [Pure Grids](http://purecss.io/grids/)
* [Off Canvas](http://jasonweaver.name/lab/offcanvas/)
* [Responsive Images Community Group](http://responsiveimages.org/)
* [Media Query Bookmarklet](http://seesparkbox.com/foundry/media_query_bookmarklet)