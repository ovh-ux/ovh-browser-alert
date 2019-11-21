# ng-ovh-browser-alert

> Display an alert when your browser isn't supported.

[![Downloads](https://badgen.net/npm/dt/@ovh-ux/ng-ovh-browser-alert)](https://npmjs.com/package/@ovh-ux/ng-ovh-browser-alert) [![Dependencies](https://badgen.net/david/dep/ovh-ux/ng-ovh-browser-alert)](https://npmjs.com/package/@ovh-ux/ng-ovh-browser-alert?activeTab=dependencies) [![Dev Dependencies](https://badgen.net/david/dev/ovh-ux/ng-ovh-browser-alert)](https://npmjs.com/package/@ovh-ux/ng-ovh-browser-alert?activeTab=dependencies) [![Gitter](https://badgen.net/badge/gitter/ovh-ux/blue?icon=gitter)](https://gitter.im/ovh/ux)

## Install

```sh
$ yarn add @ovh-ux/ng-ovh-browser-alert
```

## Usage

```js
// index.js
import ovhBrowserAlert from '@ovh-ux/ng-ovh-browser-alert';
import angular from 'angular';

angular
  .module('myApp', [
    ovhBrowserAlert,
  ]);
```

```html
<!-- index.html -->
<ovh-browser-alert></ovh-browser-alert>
```

```xml
<!-- translations/Messages_en_GB.xml -->
<translation id="browser_alert_not_supported">Your browser is not supported and may contain security vulnerabilities.</translation>
<translation id="browser_alert_deprecated">Your browser is not up to date and may contain security or compatibility vulnerabilities.</translation>
<translation id="browser_alert_update">We recommend you to<a href="http://outdatedbrowser.com/fr" class="alert-link" target="_blank">update your browser</a> in order to benefit a better experience.</translation>
<translation id="browser_alert_close">Close</translation>
```

## Test

```sh
$ yarn test
```

## Contributing

Always feel free to help out! Whether it's [filing bugs and feature requests](https://github.com/ovh-ux/ng-ovh-browser-alert/issues/new) or working on some of the [open issues](https://github.com/ovh-ux/ng-ovh-browser-alert/issues), our [contributing guide](CONTRIBUTING.md) will help get you started.

## License

[BSD-3-Clause](LICENSE) © OVH SAS
