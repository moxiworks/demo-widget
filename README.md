# MoxiWorks Demo Widget

This project is a demonstration widget for the MoxiWorks widget platform. The
purpose of this demo is to provide an example of how to use the widget platform
and its capabilities. It currently consists of a single `index.html` file that
showcases the usage of URL variables and the
[MoxiWorks Design System](https://moxiworks.github.io/mds/).

# Usage

This project is hosted on GitHub Pages at
https://moxiworks.github.io/demo-widget/. However, it is not intended to be
viewed directly in the browser. The URL should be entered into the developer
portal and viewed within the MoxiWorks platform.

The full widget URL to enter into the developer portal should look like this:
https://moxiworks.github.io/demo-widget/?mls-number={MLS_NUMBER}&nrds-number={NRDS_NUMBER}&full-name={FULL_NAME}

Note the query string at the end:

```php
?mls-number={MLS_NUMBER}&nrds-number={NRDS_NUMBER}&full-name={FULL_NAME}
```

This query string is used to pass data from the MoxiWorks platform to the
widget. The widget can then use this data to customize the user experience.
