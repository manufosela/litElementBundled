# Lit-Element and Lit-Html librarys bundled

If you need to use your lit-elements webcomponents without the magic of the polymer-cli you can use this file.
The minimized version has only 27Kb and the no-minimized version 55Kb.

#EXAMPLE

```html
<!doctype html>
<html>
  <head>
    <title>circle-picture demo</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, minimum-scale=1.0, initial-scale=1, user-scalable=yes">
    <script src="./litElementBundled.js"></script>
    <script>
        window.onload = function(){
            var tag = document.createElement("script");
            tag.type = "module";
            tag.src = "../my-element.js";
            document.getElementsByTagName("head")[0].appendChild(tag);
        };
    </script>
  </head>

  <body>
    <my-element></my-element>
  </body>
</html>
```