# Enhanced Tracking Query Remover

This is a fork of the great work by [Luis Marroquin's](https://github.com/LuisEnMarroquin) [Tracking Query Remover](https://github.com/LuisEnMarroquin/tracking-query-remover)

A Firefox extension that removes trackers from query for a simpler and cleaner URL

![image-not-found](readme.jpg)

This extension will remove the following trackers from web requests:

* gclid
* fbclid
* utm_source
* utm_medium
* utm_campaign
* utm_term
* utm_content
* trackingId
* trk
* trkEmail
* lipi

This extension is not designed to hide from the website you are visiting with the tracking queries (you can see in Network tab on DevTools that request is done before the extension removes the query), but is intended for the user to see a cleaner url to share or save it to a document. I would like to add this feature on a future release, if you have the time to do so, send a pull request

## Install

You can install the extension/add-on for the following browsers:

* [Mozilla Firefox](https://addons.mozilla.org/en-US/firefox/addon/enhanced-tracking-query-remover/)

## Tests

You can test without a web browser using **NodeJS** running

```shell
node content.js
```

Or you can test that it changes the url visiting this `https://blog.marroquin.dev/tests/?fbclid=FBFBFB&couponCode=COCOCO&gclid=GCGCGC`

In order to test this extension:

For Firefox at `about:debugging#/runtime/this-firefox` clicked **Load Temporary Add-on…**

## Links

Some links that may help you if you are also new to building extensions

* [Manifest File Format](https://developer.chrome.com/extensions/manifest)

## Icon

The icon was created with **Gimp** on a 16x16 pixels square with size 1 Pencil, you can edit by openning [icon.xcf](icon.xcf)

## Package extension
