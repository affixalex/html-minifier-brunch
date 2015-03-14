# html-minifier-brunch

Adds html-minifier support to brunch.

This plugin simply minifies static HTML in your app/ directory.

## Usage

* Add `"html-minifier-brunch": "x.y.z"` to `package.json` of your brunch app.
  Pick a plugin version that corresponds to your minor (y) brunch version.
* If you want to use git version of plugin, add
`"html-minifier-brunch": "richland/html-minifier-brunch"`.

Or, do manual install:

`npm install --save html-minifier-brunch`.

### Destination

You could specify custom place for compiled HTML pages via the `destination` option. It should be *Function* which takes path of the source file and return destination file path *String* (relative to the public path). All intermediate directories in the path are created automatically.

By default all HTML pages in `app/` are compiled to `public/` with the same directory structure and have `html` extension.


## License

jade-pages-brunch - Adds Jade static pages support to brunch

Written in 2014 by Kagami Hiiragi <kagami@genshiken.org>
Simplified to work exclusively with HTML in 2015 by Alex Caudill <alex@leadtrader.io>

To the extent possible under law, the author(s) have dedicated all copyright and related and neighboring rights to this software to the public domain worldwide. This software is distributed without any warranty.

You should have received a copy of the CC0 Public Domain Dedication along with this software. If not, see <http://creativecommons.org/publicdomain/zero/1.0/>.
