## Auto-Spacing  
> fork from https://github.com/xwartz/Auto-Spacing  

Paranoid text spacing for good readability, to automatically insert whitespace between CJK (Chinese, Japanese, Korean) and half-width characters (alphabetical letters, numerical digits and symbols).

[中文说明](./README-ZH.md)

## Installation

### Via Git

Just clone the repo via git to Sublime's package directory.

### Via Package Control

To install via Package Control, do the following:

Within Sublime Text, bring up the Command Palette and type install. 
Among the commands you should see Package Control: Install Package. 
If that command is not highlighted, use the keyboard or mouse to select it. 
There will be a pause of a few seconds while Package Control fetches the list of available plugins.

When the plugin list appears, type Auto Spacing. 
Among the entries you should see Auto-Spacing. 
If that entry is not highlighted, use the keyboard or mouse to select it.



## Commands
**Command palette:**

- Auto-Spacing: Spacing this file

**Shortcut key:**

* Linux/Windows: [Ctrl + Shift + B]
* Mac: [Cmd + Shift + B]


## Settings

By default, Auto-Spacing will supply the following settings:

```javascript
{
  // Automatically format when a file is saved.
  "format_on_save": false,

  // Only attempt to format files with whitelisted extensions on save.
  // Leave empty to disable the check
  "format_on_save_extensions": [
    "md",
    "txt"
  ]
}
```

* Modify any settings within the `Preferences -> Package Settings -> Auto-Spacing -> Settings - User` file.

## Contributing

If you find any bugs feel free to report them [here](https://github.com/xwartz/Auto-Spacing/issues).

Pull requests are also encouraged.

## Thanks

[@vinta](https://github.com/vinta/pangu.py)


## License

MIT
