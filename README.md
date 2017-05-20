# Detect InApp

detect browser or in-app information for mobile

# Code Example

```
import InApp from 'detect-inapp';

const inapp = new InApp(navigator.userAgent || navigator.vendor || window.opera);
```

# Installation

`yarn add detect-inapp`

# API Reference

- `inapp.isMobile()`

- `inapp.isTablet()`

- `inapp.isDesktop()`

- `inapp.inBot()`

- `inapp.isInApp()`

- `inapp.isApplePay()`

- `inapp.isInstalled('APP_NAME')`

- `inapp.os`

`values: 'android', 'ios', 'windows'`

- `inapp.device`

- `inapp.browser`

`values: 'messenger', 'facebook', 'line', 'twitter', 'wechat', 'miui', 'instagram', 'chrome', 'safari', 'ie', 'firefox'`

- `inapp.addMatch('NAME', 'Regex')`

# License

MIT License
