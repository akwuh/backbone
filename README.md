# Overview

What is it? - Backbone **on steroids**.

**List of improvements***:

* Error callback in Backbone.sync now receives response.responseJson instead of response. Thus, you could parse server response in the same way as in success callback.
* `fetch`, `destroy`, `save` methods return Promise instead of raw xhr. It is on your own to use Promise polyfills if you need wider browser support.

# License

MIT