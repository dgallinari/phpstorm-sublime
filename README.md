# phpstorm-sublime
A PhpStorm keymap strongly inspired on Sublime Text 3 (some packages' keymaps included).


## Installation
Copy the file `Sublime.xml` and paste into your `config/keymaps`\* directory ([see docs here](https://www.jetbrains.com/help/phpstorm/2017.1/configuring-keyboard-shortcuts.html)).
- Windows and *NIX systems: `<User home>/.PhpStorm<xx>/config/keymaps`
- macOS: `~/Library/Preferences/PhpStorm<xx>/keymaps/`

`* You may have to create the keymaps directory if it doesn't exist.`

Restart your PhpStorm and you should see a new option under `File > Settings > Keymap > Keymaps` named **Sublime**. Select it and click `Apply`. Close this dialog box and you should now be able to use all the configured key bindings.

## Key Bindings List
The list below tries to summarize the key bindings configured by `Sublime.xml` file.

| Action ID | Key Binding | Notes |
| --- | --- | --- |
| CloseContent | ctrl w | Closes current tab |
| EditorAddOrRemoveCaret | control button1 | Emulates Sublime multi-select editor (using ctrl + mouse click) |
| EditorDeleteLine | shift ctrl k | Deletes entire current line |
| EditorDuplicate | shift ctrl d | Duplicates current line |
| EditorJoinLines | ctrl j | Join lines between current caret cursor |
| EditorToggleCase (Uppercase) | ctrl k + ctrl u | Changes selected text to UPPERCASE |
| EditorToggleCase (Lowercase) | ctrl k + ctrl l | Changes selected text to lowercase |
| FileStructurePopup | ctrl r | Lookup variables and methods of current file |
| FindNext | f3 | Finds next occurrence |
| GotoAction | shift ctrl p | Similar to actions search from Sublime |
| GotoDeclaration | f12 | Go to a method declaration |
| GotoDeclaration (alternative) | shift control button1 | Go to a method declaration |
| GotoFile | ctrl p | Searches in project file names |
| OpenFile | ctrl o | Open a file |
| ReopenClosedTab | shift ctrl t | Reopen last closed tab |
| SelectAllOccurrences | alt f3 | Select all occurrences of selected text |
| SelectNextOccurrence | ctrl d | Finds next occurence of selected text |
| Editor Redo | ctrl y | Redo last action within editor |


## Optional PhpStorm Plugins
Some configured bindings require the installation of PhpStorm plugins. It is up to you to install them or not, since the keymap will work fine except for these specific bindings. They are listed here so you may decide whether you install or not a specific PhpStorm plugin.

### [MIA (Missing In Actions)](https://plugins.jetbrains.com/plugin/9257-missing-in-actions)
| Action ID | Key Binding | Notes |
| --- | --- | --- |
| NextWordStartWithSelection | shift ctrl right | Enhances the experience with text selection using shift ctrl arrows |
| PreviousWordEndWithSelection | shift ctrl left | Enhances the experience with text selection using shift ctrl arrows |

### [String Manipulation\*](https://plugins.jetbrains.com/plugin/2162-string-manipulation)
| Action ID | Key Binding | Notes |
| --- | --- | --- |
| osmedile.intellij.stringmanip.swap.SwapAction | ctrl t | Equivalent to Sublime `transpose` |
| StringManipulation.ToSnakeCaseOrCamelCase | shift ctrl minus (or ctrl underscore) | Toggle between cases |

\* This plugin also has a ToggleCamelCase action, which I've tested and chosen *\.

### [CamelCase](https://plugins.jetbrains.com/plugin/7160-camelcase)
