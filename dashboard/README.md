# Dashboard snippets

Each HTML file in this folder is self-contained. The first is `rotating-gallery.html`.

## Customize the gallery

Open `rotating-gallery.html` on GitHub, click the pencil icon, and edit only `CONFIG` near the top. Replace the sample `picsum.photos` image URLs with your own HTTPS image URLs. Click **Commit changes** to save. Do not put private image links, access tokens, or Homey credentials in this public repository.

## Homey Dashboards

1. Open the Homey mobile app and go to **Dashboards**. Edit or create a dashboard.
2. Add the built-in **Web Page** or **Web Frame** widget.
3. Enter `https://binarybrigadecom.github.io/homey-snippets/dashboard/rotating-gallery.html` as the URL.
4. Resize the widget to your preferred shape and save the dashboard.

## HDashboards

1. Open your dashboard in HDashboards and add a **Webview** card.
2. For **Source**, choose **URL** and enter the same GitHub Pages URL above.
3. Alternatively, choose **HTML** and paste the entire contents of `rotating-gallery.html` into **HTML code**.
4. Set a title and resize the card.

The URL option needs GitHub Pages enabled for this repository. The HTML option in HDashboards does not. Images still need to be reachable from the tablet.
