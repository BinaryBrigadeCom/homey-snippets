# Using HTML snippets in Homey dashboards

Every `.html` file in this folder contains its own HTML, CSS, and JavaScript. You can use the same file in Homey Dashboards or HDashboards.

## Find the address for any snippet

If the file is named `NAME.html` and is in this `dashboard` folder, its live address is:

`https://binarybrigadecom.github.io/homey-snippets/dashboard/NAME.html`

Replace `NAME.html` with the exact file name. For example, [the rotating gallery](https://binarybrigadecom.github.io/homey-snippets/dashboard/rotating-gallery.html) is `rotating-gallery.html`. Open the address in a browser first to check that it works.

## Homey Dashboards

1. Open the **Homey mobile app** on your tablet and go to **Dashboards**. Open a dashboard or create one.
2. Edit the dashboard and add the built-in **Web Page** or **Web Frame** widget.
3. Paste the snippet’s live address into the widget’s URL field.
4. Resize the widget and save the dashboard.

## HDashboards

1. Open a dashboard in **HDashboards**, enter edit mode, and add a **Webview** card.
2. To use the published page, choose **URL** as the card’s **Source** and paste the snippet’s live address.
3. To use the code directly instead, choose **HTML** as the card’s **Source**. Open the `.html` file on GitHub, click **Raw**, copy all its contents, and paste them into the card’s **HTML code** field.
4. Resize the card and save the dashboard.

The URL method uses this repository’s GitHub Pages site and needs internet access on the tablet. HDashboards’ HTML method does not need GitHub Pages, but a snippet may still need internet access for its images or other content.

## Edit a snippet on GitHub

Open the `.html` file in this folder, click the pencil icon, make your change, and click **Commit changes**. If a dashboard still shows the old version, reload it. When you use HDashboards’ HTML method, paste the updated code into the Webview card again.

This repository and its GitHub Pages site are public. Do not put Homey credentials, access tokens, private image links, or other secrets in these files.

## First snippet: rotating gallery

[Open `rotating-gallery.html`](rotating-gallery.html). Its `CONFIG` section near the top controls the images and appearance. The included `picsum.photos` addresses are sample images; replace them with your own image URLs.
