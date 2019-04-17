# Lit-Element and Lit-Html librarys bundled

If you need to use your lit-elements webcomponents without the magic of the polymer-cli you can use this file.
The minimized version has only 27Kb and the no-minimized version 55Kb.

#EXAMPLE

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, minimum-scale=1, initial-scale=1, user-scalable=yes">
    <title>your component demo</title>
    <script src="litElementBundled.min.js"></script>
    <script type="module" src="your-webcomponent.js"></script>
  </head>
  <body>
    <your-webcomponent></your-webcomponent>
  </body>
</html>
```