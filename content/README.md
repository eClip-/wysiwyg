# /content
will be displayed in the eClip Course Viewer

## content.html
contains the HTML to display. You can use plain HTML with AngularJS here.
- Settings can be accessed via `{{settings.yourKey}}`
- To include / reference files from this ModulePackage use `{{base_url}}`
- Additionally you have access to `{{config.epKey}}`, where `epKey` can be any eClip configuration variable (like *polymer_assets_url*)

## content.js
contains the logic for content.html
Basically this is just the code for *content.html*'s controller.

Your can access the scope – as usual for AngularJS – with `$scope`.
Additionally you have access to the eMP API.