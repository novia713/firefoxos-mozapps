# Firefox OS MozApps

This is a promise based library which wraps mozApp methods to make app developer's lives easier. Some things that this library takes care of:

* Proper icon selection.
* Icon text extraction from locale.
* Entry point normalization.

## Usage

Install the files into your project:
```
bower install KevinGrandon/firefoxos-mozapps
```

Include the script (if using bower install):
```
<script src="bower_components/firefoxos-mozapps/fxos_apps.js"></script>
```

Getting app icons:
```
FxosApps.all().then(icons => {
	// Do something with icons.
});
```
