homepage kicksecure.com

# Warning! This repository will soon be deprecated!

This is because this html website will be converted to mediawiki format.

# Development Goals

## No Third Party Resources

- Not fetching anything other than from kicksecure.com.

## Compatibility

ordered roughly by priority:

- Tor Browser
- Tor Browser with security slider set to maximum
- Chromium
- Firefox
- mobile Chromium
- mobile Firefox
- other browsers

## passing html5 W3C Markup Validation

https://validator.w3.org

# Misc

* Image conversion, resize and optimization is left to `ngx_pagespeed`.
* Not using relative links.
  * Using hardcoded, direct, full links to kicksecure.com images.
  * `ngx_pagespeed` filter `trim_urls` will convert them to relative links on the server on the fly.

# Links

## Standard

* https://www.kicksecure.com
* https://www.kicksecure.com/home.css

## Debugging

* https://www.kicksecure.com?PageSpeedFilters=+debug
* https://www.kicksecure.com?PageSpeed=off

## Caching Issues?

* https://www.kicksecure.com?PageSpeed=off
* https://www.kicksecure.com/home.css?PageSpeed=off
