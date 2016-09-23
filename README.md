# Kirby Paypal Digital Goods

![Version](https://img.shields.io/badge/version-0.1.0-green.svg) ![License](https://img.shields.io/badge/license-GLP3.0-green.svg) ![Kirby Version](https://img.shields.io/badge/Kirby-2.3%2B-green.svg)

*Version 0.1.0-Beta*

A plugin for Kirby CMS that act as class loader of thenbrent/paypal-digital-goods

## Installation

Use one of the alternatives below.

### 1. Clone or download

1. [Clone](https://github.com/fenixkim/kirby-paypal-digital-goods) or [download](https://github.com/fenixkim/kirby-paypal-digital-goods/archive/master.zip) this repository.
2. Unzip the archive if needed and rename the folder to `paypal-digital-goods`.

**Make sure that the plugin folder structure looks like this:**

```
site/plugins/paypal-digital-goods/
```

### 2. Git Submodule

If you know your way around Git, you can download this plugin as a submodule:

```
$ cd path/to/kirby
$ git submodule add https://github.com/fenixkim/kirby-paypal-digital-goods site/plugins/paypal-digital-goods
```

## Usage

Coming soon

## Options

The following options can be set in your `/site/config/config.php` file:

```php
c::set([
  'paypal.mode'          => 'sandbox',
  'paypal.api.username'  => 'your paypal api username',
  'paypal.api.password'  => 'your paypal api password,
  'paypal.api.signature' => 'your paypal api signature,
  'paypal.return.paid'   => 'your/path/?paypal=paid',
  'paypal.return.cancel' => 'your/path/?paypal=cancel',
  'paypal.return.notify' => 'path/to/your/notify/url/or/ipn',
]);
```

### paypal.mode

Use 'sandbox' or 'live'

### paypal.api.username

Your PayPal api username

### paypal.api.password

Your PayPal api password

### paypal.api.signature

Pour PayPal api signature

### paypal.return.paid

Return URL on paid

### paypal.return.cancel

Return URL on cancel

### paypal.return.notify

A URL to notify the payment (IPN)


## Changelog

**0.1.0**

- First version

## Todo

- [ ] A complete guide
- [x] ~~Add the lib as submodule~~

## Requirements

- [**Kirby**](https://getkirby.com/) 2.3+

## Disclaimer

This plugin is provided "as is" with no guarantee. Use it at your own risk and always test it yourself before using it in a production environment. If you find any issues, please [create a new issue](https://github.com/fenixkim/kirby-paypal-digital-goods/issues/new).

## Credits

- [thenbrent](https://github.com/thenbrent/paypal-digital-goods)
- [fenixkim](https://github.com/fenixkim)