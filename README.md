# Dataview Property Styler for Obsidian

Style your notes based on Dataview property values.

## What does it do?

This plugin adds dataview property values as data-attributes to dataview inline classes in the notes. This means you can style your notes dynamically as values change.

## Examples of what you can do

- Color-code task priorities (high priority = red background)
- Style different project statuses (completed = green text)
- Highlight specific categories (personal = blue border)
- Format dates differently (overdue = bold red)
- Hide elements
- Replace titles with icons
- and much more…

## Getting Started

1. Get the plugin to your plugins folder.
2. Make sure you have Dataview installed
3. Start adding properties to your notes
4. Create custom CSS styles for your property values

## Styling Guide

Once installed, the plugin adds CSS attribute `data-dv-value="your value here"` to class `.dataview.inline-field` but only for `[propery:: value]` not `(propery:: value)` because `data-dv-key` is not displayed which can lead to conflicts if two properties have same value.

CSS format:`.dataview.inline-field[data-dv-value="your value here"]`

## Todo

- [ ] frontmatter property values to the note probably to `cm-content` class

## Donate

If you like this plugin, please consider buying me a coffee. ;)
[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](buymeacoffee.com/simonF)
