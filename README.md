# Mini Mini Modal

Mini Mini Modal is a super simple JS modal with no dependencies - basically `alert()`, but prettier. Built because [all](https://github.com/FinelySliced/leanModal.js) [the](https://github.com/Nycto/PicoModal) [other](https://github.com/thephuse/vanilla-modal) "tiny" modals were too complicated or ugly. Trigger with `mmm('message')`.

[See an example](http://jacksondc.com/miniminimodal)

## Installation

Download and include the [JS file](https://cdn.rawgit.com/jacksondc/miniminimodal/gh-pages/js/miniminimodal.js) and the (easy to modify) [CSS file](https://cdn.rawgit.com/jacksondc/miniminimodal/gh-pages/css/miniminimodal.css).

## Options

You can also pass an options object:

```
mmm('Lorem Ipsum', {
  closeText: 'Close',
  raw: true,
  transitionDuration: 2
});
```

### closeText

Specifies the text to use on the close button. Defaults to “OK”.

### raw

Treat the message as raw html (it won't get wrapped in a paragraph tag.) Defualts to false.

### transitionDuration

Specifies how long to wait (in seconds) before removing the modal DOM elements after close, so that you can have time to transition. Defaults to 0.5.
