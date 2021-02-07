# Sublime setup for React and Laravel

## Genearl Packages 
- Package control
- Materialize
-  A file icon
- Emmet
- SideBarEnhancement
- sublime Linter
- Pretty JSON
- Terminus
- Git Gutter

## React Packages
- Bable (Use Monokai for proper syntax highlight.)
- JsPrettier
- Sublime Es7 React Redux js snippet
- SublimeLinter-eslint

**Note** : For react packages to wotk properly you'll need to install below npm packages globally.
```
elsint  => npm install -g eslint
prettier  => npm install -g prettier
```

## Laravel Packages
- PHP Companion
- phpfmt
- sublimeLinter-PHP

**Note** : For phpfmt to work as expected, `Preference` > `Package Setting` > `phpfmt` > `Settings Default` > add below:
```
{
"version": 4,
"php_bin":"/usr/bin/php",
"format_on_save":true,
"option": "value"
}

```


### Syntax Specific Preference
Select PHP : Open `Preference` > `Settings-Syntax Specific` > add below: 
```
{
	"extensions": [	"PHP"],
	"tab_size": 4,
  "translate_tabs_to_spaces": true,
  "detect_indentation": false
}
```

Select Javascript : Open `Preference` > `Settings-Syntax Specific` > add below: 
```
{
	"extensions":["js"],
	"tab_size": 2,
  "translate_tabs_to_spaces": true,
  "detect_indentation": false
}

```