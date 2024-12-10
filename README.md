# JxBrowser in a Maven-based Swing desktop application

This example demonstrates how to configure a Maven project with JxBrowser to embed a `BrowserView` widget into a Swing desktop application to display web pages.

## Prerequisites

* Java 17 or newer.
* Your JxBrowser license key, or a [free 30-day evaluation key][web-form].

## Run the Swing application

Use the following command to start the application:

```bash
mvn clean compile exec:java -Djxbrowser.license.key=<your_license_key>
```

Once launched, the app loads the [HTML5 test page][html5-test-page]:

![Swing BrowserView][swing-browser-view]

[web-form]: https://www.teamdev.com/jxbrowser#evaluate
[html5-test-page]: https://html5test.teamdev.com
[swing-browser-view]: https://jxbrowser-support.teamdev.com/img/articles/awt-swing-view.webp
