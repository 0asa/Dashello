# Dashello 

## Turn a Trello Board into a dashboard screen manager

The simple standalone HTML file allow to turn:

- a Trello list into a [reveal.js](http://lab.hakim.se/reveal-js) slideshow/dashboard screen,
- a Trello card from the above list into a single slide/a message on a dashboard screen.
- card title becomes the slide title,
- card description (HTML allowed) becomes the slide content.

For instance, this can be useful to:

- display a Trello list content in fullscreen,
- make a presentation,
- feed a dashboard display.

### Setup

1. Get your Trello application key [here](https://developers.trello.com/get-started). Use it instead of `__TRELLO_APPLICATION_KEY__` in `index.html`
2. Get your Trello list ID. Use it instead of `__TRELLO_LIST_ID__` in `index.html`

### Dependencies

- Trello [client.js](https://developers.trello.com/clientjs)
- jQuery.js
- [reveal.js](http://lab.hakim.se/reveal-js)

### Raspberry Pi configuration (optional)

The idea is to plug a Raspberry Pi to a TV screen. And then launch Chromium in kiosk mode. For more information see [this post](https://www.danpurdy.co.uk/web-development/raspberry-pi-kiosk-screen-tutorial/).

### What's next?

- Make use of card due date to start or stop displaying a message,
- Make use of cart attachments to display image slideshow,
- Make use of label to change background color,
- ... 
