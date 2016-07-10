# Weather icons for ExtJS

ExtJS package to use [Weather icons](https://erikflowers.github.io/weather-icons/) (created by [Erik Flowers](https://twitter.com/erik_flowers))

Current version of weather-icons: 2.0.10

## Adding package to workspace or app
Download [weather-icon.pkg](https://github.com/RichardStyles/weather-icons/releases/download/1.0.5/weather-icons.pkg) from releases [1.0.5]

copy: .pkg file to workspace of your project

run: ```sencha package add weather-icons.pkg```

add 'weather-icons' to your app.json

```
   "requires": [
      "font-awesome",
      "weather-icons"
   ],
```
run: ```sencha app refresh```

## Use

Just like using font awesome you must use the css ```x-wi``` class before the weather icon class you wish to use.

#### Example 

```
iconCls: "x-wi wi-night-alt-cloudy"
```

## Licences
* All licences for weather icons remain for [weather icon package](https://erikflowers.github.io/weather-icons/).  
* Code for ExtJS package release under MIT

## About
This package was created to allow additional fonts to be used, just like font-awesome.

ExtJS Package built by [Richard Styles](https://twitter.com/camerastyles).