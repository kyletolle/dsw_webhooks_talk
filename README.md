# The Power Behind Real-Time Push Notifications Using Webhooks

Slides for my webhooks talk given given at Denver Startup Week on September 29, 2015.

The slides were generated with [markdown_to_reveal](https://github.com/kyletolle/markdown_to_reveal).

This talk is based on [reveal.js](https://github.com/hakimel/reveal.js).

## Installation

- Clone this talk
   ```sh
   $ git clone https://github.com/kyletolle/ruby_webhooks_intro.git
   ```

### Just viewing

You can view the entire presentation by opening the `index.html` file.

```
$ open index.html
```

### Full setup for making changes

1. Install [Node.js](http://nodejs.org/)

2. Install [Grunt](http://gruntjs.com/getting-started#installing-the-cli)

3. Navigate to the folder
   ```sh
   $ cd ruby_webhooks_intro
   ```

4. Install dependencies
   ```sh
   $ npm install
   ```

5. Serve the presentation and monitor source files for changes
   ```sh
   $ grunt serve
   ```

6. Open <http://localhost:8000> to view your presentation

   You can change the port by using `grunt serve --port 8001`.

## PDF Export

Note: I've included a PDF version of the talk at `ruby_webhooks_intro.pdf`.

Presentations can be exported to PDF via a special print stylesheet. This feature requires that you use [Google Chrome](http://google.com/chrome) or [Chromium](https://www.chromium.org/Home).
Here's an example of an exported presentation that's been uploaded to SlideShare: http://www.slideshare.net/hakimel/revealjs-300.

1. Open your presentation with `print-pdf` included anywhere in the query string. This triggers the default index HTML to load the PDF print stylesheet ([css/print/pdf.css](https://github.com/hakimel/reveal.js/blob/master/css/print/pdf.css)). You can test this with [lab.hakim.se/reveal-js?print-pdf](http://lab.hakim.se/reveal-js?print-pdf).
2. Open the in-browser print dialog (CMD+P).
3. Change the **Destination** setting to **Save as PDF**.
4. Change the **Layout** to **Landscape**.
5. Change the **Margins** to **None**.
6. Click **Save**.

![Chrome Print Settings](https://s3.amazonaws.com/hakim-static/reveal-js/pdf-print-settings.png)

## License

MIT licensed

Reveal.js copyright (C) 2015 Hakim El Hattab, http://hakim.se
GIFs are copyright their owners

