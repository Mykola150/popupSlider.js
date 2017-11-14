# popupSlider.js
Simple RAW JavaScript popup slider. Based on https://codepen.io/gabrieleromanato/pen/pIfoD

Some features are commented in the code:

- load the slider to the container with id #popupSlider;
- closing the popup clicking outside;
- make the carousel (auto slide changing with interval 5 seconds) - stop when the slide was changed manually.

# Integration to the site
1. Copy the catalog to the site directory.
2. Add the next line to the HTML code of your site before the </body> tag:

```html
<script type="text/javascript" src="/path_to_slider_dir/popupSlider.js"></script>
```

3. If you want to attach the slider to the specified container, you should add the id #popupSlider to it:

```html
<div id="popupSlider"></div>
```

Also you can change the value of the id in the code of the popupSlider.js

# Planned in the future
- make the external config file;
- change the makeup for the situations when the slider would be embedded.
- asynchronous slider loading
