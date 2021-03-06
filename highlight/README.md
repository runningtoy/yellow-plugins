Highlight plugin 0.6.4
======================
Highlighting for source code.

<p align="center"><img src="highlight-screenshot.png?raw=true" alt="Screenshot"></p>

## How do I install this?

1. [Download and install Yellow](https://github.com/datenstrom/yellow/).
2. [Download plugin](https://github.com/datenstrom/yellow-plugins/raw/master/zip/highlight.zip). If you are using Safari, right click and select 'Download file as'.
3. Copy `highlight.zip` into your `system/plugins` folder.

To uninstall delete the plugin files.

## How to highlight source code?

Wrap your code blocks in \`\`\`, add an optional language identifier for highlighting. For line numbers add a colon separated number to the language. The visual design of programming languages can be adjusted in your theme.

The plugin uses [GeSHi 1.0.8.12](https://github.com/GeSHi/geshi-1.0) by Benny Baumann and Nigel McNie, which supports about 200 programming languages. It's licensed under [GPLv2](https://opensource.org/licenses/GPL-2.0). The following languages are included: [C](https://en.wikipedia.org/wiki/C_(programming_language)), [CPP](https://en.wikipedia.org/wiki/C++), [CSS](https://en.wikipedia.org/wiki/CSS), [HTML](https://en.wikipedia.org/wiki/HTML), [JavaScript](https://en.wikipedia.org/wiki/JavaScript), [PHP](https://en.wikipedia.org/wiki/PHP), [Python](https://en.wikipedia.org/wiki/Python_(programming_language)), [Ruby](https://en.wikipedia.org/wiki/Ruby_(programming_language)). You can download more [language files](https://github.com/GeSHi/geshi-1.0/tree/master/src/geshi), copy them into your `system/plugins/highlight` folder.

## Example


Highlighting of JavaScript code:

    ``` javascript
    var ready = function() 
    {
        console.log("Hello world");
        // Add more JavaScript code here
    }
    if(window.addEventListener) {
        window.addEventListener('load', ready, false);
    } else {
        window.attachEvent('onload', ready);
    }
    ```

Highlighting of HTML code, with and without line numbers:
    
    ``` html:1
    <body>
    <p>Hello world!</p>
    </body>
    ```

    ``` html
    <body>
    <p>Hello world!</p>
    </body>
    ```

## Developer

Datenstrom featuring Benny Baumann and Nigel McNie
