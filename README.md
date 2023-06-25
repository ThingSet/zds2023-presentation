# ThingSet + Zephyr: Transport-Agnostic Device Connectivity Within 10 Minutes

This is the presentation from Zephyr Developer Summit 2023 by Martin Jäger.

It uses a non-official template made with [remark](https://github.com/gnab/remark).

The presentation runs in the browser and can be easily deployed with GitHub pages (just enable it in the repo settings). To see the rendered version of this template, click the repository website link.

## Edit Content

All content is stored in the file `content.md`. Just edit it and you should be able to see the changes immediately.

Official documentation for remark can be found [here](https://github.com/gnab/remark/wiki)

## Local deployment

Install Python and run:

```
python3 -m http.server
```

Afterwards open [http://0.0.0.0:8000](http://0.0.0.0:8000) in your browser.

You can't just open the HTML file in a browser, as it will not be able to load the content.md file.

## PDF generation

```
decktape remark http://0.0.0.0:8000 slides.pdf --chrome-arg=--disable-web-security --chrome-path /usr/bin/chromium
```
