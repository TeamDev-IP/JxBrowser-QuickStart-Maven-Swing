# JxBrowser in Swing Maven project

This example demonstrates how to configure a Maven project with JxBrowser to embed a Swing `BrowserView` widget into a Swing desktop application to display web pages.

## Prerequisites

To compile and run this example please make sure you use Java 17 or higher.

## Download the project

Clone this repository using the following command:

 ```bash
 git clone https://github.com/TeamDev-IP/JxBrowser-QuickStart-Maven-Swing.git
 cd JxBrowser-QuickStart-Maven-Swing
 ```

## Get license

Download a free 30-day evaluation license key by sending a request via the [web form](https://www.teamdev.com/jxbrowser#evaluate).

## Run the Swing application

Use the following command:

```bash
mvn clean compile exec:java -Djxbrowser.license.key=<your_license_key>
```

It will build and start a Swing desktop application with Swing `BrowserView` inside that displays https://html5test.teamdev.com as shown below:

![Swing BrowserView](https://jxbrowser-support.teamdev.com/img/articles/awt-swing-view.png)
