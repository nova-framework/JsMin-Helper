# JsMin Helper for SMVC

JSMin.php - modified PHP implementation of Douglas Crockford's JSMin.

This helper allows an easy way to minify javascript code.

##Install
Add JsMin.php to app/Helpers 

##Usage

Create an Alias
````
use Helpers\JsMin;
````

Minify Example
````
JsMin::minify($filePath);
````
