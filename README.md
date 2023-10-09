# Firefox Vertical Tabs

A collection of custom styles to enhance the Firefox user interface, including specific styles for the [Sidebar Tabs](https://github.com/asamuzaK/sidebarTabs) extension.

## Description

This repository houses the `userChrome.css` which modifies the look and feel of Firefox's user interface to have vertical tabs behave like [Brave Browser](https://brave.com/vertical-tabs/) / [Microsoft Edge](https://www.microsoft.com/en-us/edge/features/vertical-tabs?form=MT00D8).

Additionally, it contains styles for the [Sidebar Tabs extension](https://addons.mozilla.org/en-US/firefox/addon/sidebartabs/) to enhance its behavior.

## Installation/Setup

1. Navigate to your Firefox profile directory.
2. If it doesn't exist, create a `chrome` directory.
3. Copy the `userChrome.css` from this repository into that directory.
4. Restart Firefox to see the changes.
5. For Sidebar Tabs styles, navigate to the [extension's settings](moz-extension://bb862881-b440-466e-9965-91c46a6fe164/html/options.html), select `Apply user stylesheet`, and copy the contents of `sidebartabs.user.css` from this repository into the text box.
6. Ensure `Sidebar Tabs` is enabled, and able to run in Private Windows

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](LICENSE)
