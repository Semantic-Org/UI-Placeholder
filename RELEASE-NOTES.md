### Version 2.4.0 - Sep 17, 2018

> `2.4.0` includes a new component `placeholder`. To use this component in your existing SUI site, be sure to add `@placeholder: 'default';` to your `theme.config`. You can see an example in `theme.config.example`

- **Placeholder** - Added `ui placeholder` that can be used to show where content will soon appear.
- **Segment** - Added new `ui placeholder segment` used to reserve space for UI when content is missing or empty.

### Version 2.2.0 - June 26, 2016

- **Dropdown** - Added new convenience method `restore placeholder text`
- **Site** - Added new `@inputColor` and `@inputPlaceholderColor` global variables that now control placeholder text styles across all components.
- **Button/Dropdown** - Button dropdowns using `default text` no longer receive incorrect font styling for placeholder text
- **Visibility** - Using `type: fixed` will now correctly remove all special classes and placeholder content on `destroy` [#3548](https://github.com/Semantic-Org/Semantic-UI/issues/3548)

### Version 2.1.3 - Sep 03, 2015

- **Input** - Fixes typo in focused placeholder text color preventing the value from being used [#2939](https://github.com/Semantic-Org/Semantic-UI/issues/2939)

#### Features

- **Dropdown** - Added `get default text` and `get placeholder text` behaviors for returning text values.

#### Bugs

- **Dropdown** - Fixes issues with setting "" (empty quote) values when `placeholder: false` is used. Fixes issues with using `clear` and `restore defaults` without placeholders. [#2637](https://github.com/Semantic-Org/Semantic-UI/issues/2637)
- **Form / Input** - Fixes `::placeholder` text color for `ui error input`, modifies form error placeholder color to distinguish from form value error color [#2786](https://github.com/Semantic-Org/Semantic-UI/issues/2786)
- **Dropdown** - When `useLabels: false` placeholder text will now show up when 0 items selected, instead of the text "0 items selected"

### Version 2.0.0 - June 30, 2015

- **Embed** - New embed component allows for responsive iframe embeds that maintain their aspect ratio. Embed can be used with YouTube or Vimeo videos, along with placeholder content to avoid loading third party libraries until a user chooses to interact with the video.
- **Visibility** - Using `.visibility({ type: 'fixed'})` will now automatically add a placeholder element which will swap places with an element when it is attached to the viewport. This should make fixed content drastically simpler.
- **Dropdown** - Dropdown has new `placeholder` setting for setting placeholder text in javascript
- **Form** - Added placeholder color rules for IE, `ms-input-placeholder`
- **Input** - Added placeholder color rules for IE, `ms-input-placeholder`
- **Input** - Fixed `placeholder` color not changing correctly on focus **Thanks @zxfwinder**

### Version 1.12.1 - April 26, 2015

- **Input** - Fixes placeholder text color prefixes for `webkit` **Backport from 2.0**

### Version 1.8.0 - January 23, 2015

- **Dropdown** - Dropdown now stores `placeholder text` (prompt text) as separate from `default text` (text set on page load). You can now reset placeholder conditions using `$('.ui.dropdown').dropdown('clear');``

### Version 1.7.0 - January 14, 2015

- **Dropdown** - `restore defaults` will now set placeholder styling and remove active element. Added example in docs.

### Version 1.3.0 - December 17, 2014

- **Dropdown** - Search Dropdown now correctly replaces placeholder text when backspacing to empty value

### Version 0.12.0 - Jan 06, 2014

- **Input** - Fixes input placeholder styles to work (accidental regex replace)

### Version 0.9.0 - Nov 5, 2013

- **Form** - Darkens placeholder text color to be more visible

### Version 0.1.0 - Sep 25, 2013