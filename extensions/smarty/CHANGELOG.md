Yii Framework 2 smarty extension Change Log
===========================================

2.0.0-rc under development
--------------------------

- Moved most of Yii custom syntax into `\yii\smarty\Extension` class that could be extended via `extensionClass` property (samdark)
- Added `url` function (samdark)
- Aliases are now automatically used as additional template directories (samdark)
- Added ability to set Smarty options via config using `options` (samdark)
- Added `imports` property that accepts an array of classes imported into template namespace (hwmaier)
- Added `widgets` property that can be used to import widgets as Smarty tags (hwmaier)
- Added `set` function that allows setting commonly used view paramters such as title or layout (hwmaier)
- Added dedicated tags for `title`, `description`, `meta` etc. (hwmaier)
- `Yii::$app->params['paramKey']` values are now accessible as Smarty config variables `{#paramKey#}` (hwmaier)

2.0.0-beta April 13, 2014
-------------------------

- no changes in this release.

2.0.0-alpha, December 1, 2013
-----------------------------

- Initial release.
