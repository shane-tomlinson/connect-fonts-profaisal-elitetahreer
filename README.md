# connect-fonts-profaisal-elitetahreer

Profaisal-Elite-Tahreer fontpack for [connect-fonts](https://github.com/shane-tomlinson/connect-fonts).

## Usage

1. Include [connect-fonts](https://github.com/shane-tomlinson/connect-fonts) in a node module.
```js
const font_middleware = require("connect-fonts");
```

2. Include the font packs that you want to serve.
```js
const font_pack  = require("connect-fonts-profaisal-elitetahreer");
```

3. Add a middleware by calling the `setup` function.
```js
    app.use(font_middleware.setup({
      fonts: [ font_pack ],
      allow_origin: "https://exampledomain.com"
    }));
```

4. Add a link tag to include the font CSS.
```html
<link href="/profaisal-elitetahreerv1.0/fonts.css" type="text/css" rel="stylesheet"/ >
```


Available fonts:
* profaisal-elitetahreerv1.0

Locale-optimised font sets can be served by specifying the locale in the fonts.css URL.
```html
<link href="/latin/profaisal-elitetahreerv1.0/fonts.css" type="text/css" rel="stylesheet"/ >
```

Available subsets:
* latin
* en

5. Set your CSS up to use the new font by using the "Profaisal-Elite-Tahreer" font-family.
```
    body {
      font-family: 'Profaisal-Elite-Tahreer', 'sans-serif', 'serif';
    }
```

## Font Info
Profaisal-Elite-Tahreer

* Copyright: Copyright (c) 2012 Profaisal.com.
* Trademark: Profaisal is a trademark of profaisal.com
* Designer: Original by Jamil-ur-Rahman and Astigmatic, Merged by Faisal Abbas
* Designer URL: www.profaisal.com 
* Vendor URL: www.profaisal.com

## Development Info
* Homepage: https://github.com/shane-tomlinson/connect-fonts-profaisal-elitetahreer
* Repo: https://github.com/shane-tomlinson/connect-fonts-profaisal-elitetahreer

## Author
* Shane Tomlinson
* shane@shanetomlinson.com
* stomlinson@mozilla.com
* set117@yahoo.com
* https://shanetomlinson.com
* https://github.com/shane-tomlinson
* https://github.com/stomlinson
* @shane_tomlinson


## License

Software: Licenced under version 2.0 of the MPL

  https://www.mozilla.org/MPL/

Fonts: Licensed under version 2.0 of the Apache

  http://www.apache.org/licenses/LICENSE-2.0

