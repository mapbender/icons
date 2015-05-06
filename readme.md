# Mapbebder3 icon library

Icon set is created and generated with [iconmon](https://icomoon.io/). web app.<br/>
Used at least by [mapbender](http://mapbender3.org/) GIS project.

## Integration 

### Composer

Add requirement to [composer](https://getcomposer.org/).
Config "component-dir" is the path where font files would be copied.
```javascript
{
  "require": {
    "mapbender/icons",: "*"
  },
  "config": {
       "component-dir": "web/components"
  }
}
```

Update and install requirements.

```sh
composer update 
```


## Change font

To get change the icons use [iconmon](https://icomoon.io/).

* Click on import files
* Select and load [selection.json](selection.json) project file.
* Edit icons
* Click "Generate-Font" on bottom panel
* Download "zip" and extract it into this GIT project folder
* Commit, Push/Pull-request


