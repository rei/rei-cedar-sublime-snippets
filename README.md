# rei-cedar-sublime-snippets
Snippets for sublime support REI Cedar markup

## Installation

1. Install [Package Control for Sublime Text](https://packagecontrol.io/installation "Package Control").

2. Open the command palette
 * OSX: <kbd>&#8984;</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd>
 * Win,Linux: <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd>

3. Find `Package Control: Add Repository` in the command palette and select it.

4. Copy/paste the URL of this repository (`https://github.com/rei/rei-cedar-sublime-snippets`) into the input at the bottom of the window and hit enter.

5. Open the command palette again and find `Package Control: Install Package` and select it.

6. Find the package named `rei-cedar-sublime-snippets` and select it.

7. After the package installs, restart Sublime Text.

## Documentation and usage

Documentation with code examples and the snippet shortcut string can be found [here](https://rei.github.io/rei-cedar-sublime-snippets/ "Cedar Sublime Docs"). Names map almost directly to what is used on the patterns site if you need to refer to usage or notes about the markup.

Completion can be fuzzy typed once auto complete is opened with <kbd>Ctrl</kbd> + <kbd>Space</kbd>


Example:
Inline list with feature links `(list-inline-feature-link)` -- you don't need to type out that long name to get it.

1. Type `li`
2. Press <kbd>Ctrl</kbd> + <kbd>Space</kbd> to bring up auto complete for matching snippet names that begin with `li`.
3. Keep typing other parts of the name such as: `in` for inline or `fea` for feature.
4. If you see it in the list you can use the arrow keys to select it or keep typing until you get down to just the one.
5. Press <kbd>Enter</kbd> to trigger the snippet expansion.

## Updating

If there are updates, they will be automatically applied at startup.

If you need to manually update, you can do so by opening the command palette and selecting `Package Control: Upgrade Package` then select the package if there is an update available.
