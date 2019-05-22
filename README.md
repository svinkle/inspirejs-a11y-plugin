# Inspire.js A11y Plugin

Accessibility plugin for [Inspire.js slide deck framework](https://github.com/LeaVerou/inspire.js).

## What does it do?

- Resets focus indicator to be visible on `Tab` key press
- Removes `outline` on slide focus
- Includes CSS helper classes
- Sets `role` for each slide for semantic context
- Sets `aria-roledescription` for each slide for extra context
- Sets `aria-label` for each slide to provide an accessible name
- Outputs a link list for keyboard controls to load previous and next slides
- Shifts focus to slide content container on link click

## Usage

1. Place `plugin.css` and `plugin.js` file in `/plugins/a11y/` directory.
2. Add plugin entry to `pluginTest` object in `inspire.js` file.

  ```javascript
  pluginTest: {
    // …
    "a11y": "*"
	},
  ```

## Browser support

* Chrome
* Edge
* Firefox
* ~~Internet Explorer~~
* Safari
* Opera

## License

This project and its source code is licensed under the [MIT](LICENSE.txt) license.
