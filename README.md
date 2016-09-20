# Pull Utility #

The pull utility is responsive for handling grid's after offset.


### Installation ###

```
npm install --save iotacss-pull
```


### Dependencies ###

* [Settings.Default](https://github.com/iotacss/settings.default)
* [Settings.Column](https://github.com/iotacss/settings.column)
* [Settings.Breakpoint](https://github.com/iotacss/settings.breakpoint)


### Options ###

```
$iota-pull-namespace  : pull !default;
$iota-pull--res       : false !default;
```


### Classes ###

```
.u-pull-[column-number]/[total-columns-number]  // Example: .u-pull-1/3


// Responsive Classes Syntax

.u-pull-[column-number]/[total-columns-number]@[breakpoint-name]  // Example: .u-pull-1/3@sm
```
