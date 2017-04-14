
# React Native Phone Verification

[![PayPal Donate][paypal-donate-image]][paypal-donate-url]
[![Slack Status][slack-image]][slack-url]
[![Standard JS Style][standard-image]][standard-url]
[![MIT License][license-image]][license-url]

The best React Native example for phone verification (an alternative to [Twitter Digits][twitter-digits]). This package was built for [CrocodileJS][crocodile-url].

![React Native Phone Verification][demo]

## Features

* :boom: Works with iOS and Android! :100: 100% Cross-platform baby :baby:!
* :flags: Built-in country picker (uses [react-native-country-picker-modal][react-native-country-picker-modal])!
* :wrench: Completely customizable form (uses [react-native-form][react-native-form], but you could also use [tcomb-form-native][tcomb-form-native])!
* :crystal_ball: Spinner overlay (uses [react-native-loading-spinner-overlay][react-native-loading-spinner-overlay])!

## Wishlist

* :sparkles: Optional Android support for reading verification codes automatically (uses [react-native-android-sms-listener][react-native-android-sms-listener])!

## Usage

1. Install [React Native][react-native]:

  ```bash
  npm install -g react-native-cli
  ```

2. Initialize a new project:

  ```bash
  react-native init myproject
  ```

3. Install dependencies:

  > If you're using `npm` to install packages:

  ```bash
  npm install --save frisbee niftylettuce/react-native-country-picker-modal react-native-form react-native-loading-spinner-overlay
  ```

  > Or, if you're using `yarn` to install packages:

  ```bash
  yarn add frisbee niftylettuce/react-native-country-picker-modal react-native-form react-native-loading-spinner-overlay
  ```

4. See [example][example] directory for how to integrate into your codebase (you can also just clone this repo and run the example to test it out).


## License

All code is licensed under [MIT][license-url]


[paypal-donate-image]: https://img.shields.io/badge/paypal-donate-orange.svg
[paypal-donate-url]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=FE3EFQ5X9RHT6
[license-image]: http://img.shields.io/badge/license-MIT-blue.svg
[license-url]: LICENSE
[crocodile-url]: https://crocodilejs.com
[slack-image]: http://slack.crocodilejs.com/badge.svg
[slack-url]: http://slack.crocodilejs.com
[standard-image]: https://img.shields.io/badge/code%20style-standard%2Bes7-brightgreen.svg
[standard-url]: https://github.com/crocodilejs/eslint-config-crocodile
[react-native-country-picker-modal]: https://github.com/xcarpentier/react-native-country-picker-modal
[react-native]: https://facebook.github.io/react-native/
[react-native-android-sms-listener]: https://github.com/CentaurWarchief/react-native-android-sms-listener
[tcomb-form-native]: https://github.com/gcanti/tcomb-form-native
[react-native-form]: https://github.com/julianocomg/react-native-form
[react-native-loading-spinner-overlay]: https://github.com/niftylettuce/react-native-loading-spinner-overlay
[demo]: https://cdn.rawgit.com/niftylettuce/react-native-phone-verification/master/media/example.png
[example]: example/index.ios.js
[twitter-digits]: https://get.digits.com/
