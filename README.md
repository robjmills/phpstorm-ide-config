# Installation

Before you do this, make sure PhpStorm is not running, or it will overwrite the changed files before shutting down.

Use the following commands to go to the config directory, remove some default directories, and pull the files from my repository:

```bash
cd ~/Library/Preferences/WebIde100

# remove the files and folders that are in this repository
rm -r codestyles/
rm -r fileTemplates/
rm -r inspection/

git init
git remote add origin git@github.com:robjmills/phpstorm-ide-config.git
git fetch
git checkout -t origin/master
```
## Subdirectories of the config folder

Directory | Contents
----------|---------
codestyles | Code Style settings (Editor > Code Style)
colors | Colors & Fonts settings (Editor > Colors & Fonts)
fileTemplates | File and Code Templates (Editor > File and Code Templates)
filetypes | File Types (Editor > File Types)
inspection | Inspection profiles (Editor > Inspections)
keymaps | Keyboard shortcuts (Appearance & Behavior > Keymap)
templates | Live templates (Editor > Live Templates)


## Credits

- most of this readme file has been shamelessly copied from https://github.com/nicwortel/phpstorm-ide-config
- some settings originally taken from https://github.com/ShawnMcCool/PHPStorm-SpacePeacock
