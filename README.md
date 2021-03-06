# KE-complex_modifications

complex_modifications for Karabiner-Elements by rcmdnk.

http://rcmdnk.com/KE-complex_modifications/

## Update docs

Run make in terminal.

```
make
```

## Add rules

1. Put a file to [src/json](https://github.com/pqrs-org/KE-complex_modifications/tree/master/src/json). (or [docs/json](https://github.com/pqrs-org/KE-complex_modifications/tree/master/docs/json) directly)
2. Add `file_import_panel` to [src/index.html.erb](https://github.com/pqrs-org/KE-complex_modifications/tree/master/src/index.html.erb).
3. Run `make` in terminal.

Key name definitions are [here](https://github.com/tekezo/Karabiner-Elements/blob/master/src/apps/PreferencesWindow/PreferencesWindow/Resources/simple_modifications.json).

## Local testing

1. Copy a json file to `~/.config/karabiner/assets/complex_modifications`.
2. Import rules from Karabiner-Elements Preferences.

### Example

```
$ cp docs/json/caps_lock.json ~/.config/karabiner/assets/complex_modifications
```

Then open `Karabiner-Elements Preferences > Complex Modifications > Rules > Add rule`

----------

# Karabiner-Elements Usage

## Import file from another site

1. Put a json file to your site.
2. Make a link `karabiner://karabiner/assets/complex_modifications/import?url=<JSON_URL>`.
3. Open the link from web browser.

