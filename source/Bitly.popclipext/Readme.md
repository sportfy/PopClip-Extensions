# Bitly

A PopClip extension to shorten a URL using [Bitly](https://bitly.com/).

The extension defines a single action called "Bitly", which is enabled when the input contains one or more web URLs. The action shortens all the detected URLs using the logged-in Bitly account, and outputs the resulting text. (If the text is not editable, or Shift is held on the keyboard, PopClip will copy the result to the clipboard instead.)

### Requirements

Requires PopClip 2021.11 or above, and a Bitly account.

### Author

Nick Moore

### Notes

Implemented using the Bitly public API, documented at https://dev.bitly.com.

The SVG icon is from [IconFinder](https://www.iconfinder.com/icons/1298728/bitly_icon).

## Changelog

### v4 — 1 Nov 2021

* Rewritten using PopClip's JavaScript API, for compatibility with macOS Monterey.
* Now shortens all URLs detected in the text, instead of just one.
* Changed icon to a Bitly logo.

### v3 - 5 Jun 2020

* Updated to fix login failure.

### v2 - 7 May 2020

* Updated for Bitly API v4.

### v1 - 19 Feb 2013

* Initial release (written in PHP).