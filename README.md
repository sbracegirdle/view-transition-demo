# View transition demo

This is a demo of multi-page view transitions using a simple Flask app.

The `<meta name="view-transition" content="same-origin" />` tag indicates that the browser should attempt to transition between pages of the same origin. So, if you click on a link to a page on the same origin, the browser will attempt to transition to that page instead of doing a full page refresh.

## Running

```sh
python app.py
```

Then access via [localhost:5000](http://localhost:5000).

You may need the chrome flags, depending on your version:

```
chrome://flags#view-transition
chrome://flags#view-transition-on-navigation
```

## Reference

- [Getting started with View Transitions](https://daverupert.com/2023/05/getting-started-view-transitions/)
