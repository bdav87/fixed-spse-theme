#Fixing SPSE theme
The theme provided in the SPSE exercise had 2 flaws which prevented it from being bundled.

1) jQuery reference in assets/js/app.js was commented out.
2) Syntax error on line 10 of config.json. There were no quotes for the key "composed_image", only a comma.

Once these were corrected it was possible to bundle the theme. I've uploaded the contents of the unzipped bundle here.
