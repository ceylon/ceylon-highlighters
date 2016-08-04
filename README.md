List of supported Syntax Highlighters:

## CodeMirror

https://codemirror.net/

This is used on the Ceylon Web IDE, and pushed upstream.

Source: https://github.com/codemirror/CodeMirror/tree/master/mode

Our source: https://github.com/codemirror/CodeMirror/blob/master/mode/clike/clike.js#L725

## GeSHi

http://qbnz.com/highlighter/

This is not pushed upstream yet.

Our source: https://github.com/GeSHi/geshi-1.0/pull/50

## Highlight.js

https://highlightjs.org/

Source: https://github.com/isagalaev/highlight.js/blob/master/src/languages/ceylon.js

## Pygments

http://pygments.org/

Source: https://bitbucket.org/birkenfeld/pygments-main/src/655dbebddc23943b8047b3c139c51c22ef18fd91/pygments/lexers/jvm.py?at=default

## Rainbow

https://craig.is/making/rainbows

This is used on ceylon-lang.org, ceylon-herd and ceylondoc output, but apparently we did not push a PR

Source: https://github.com/ccampbell/rainbow/tree/master/js/language

Our source: https://github.com/ceylon/ceylon-compiler/blob/master/src/com/redhat/ceylon/ceylondoc/resources/ceylon.js

## Rouge

This will be used by GitHub pages as of May 1st 2016 (with Jekyll 3). It looks like it's also used by GitLab.

Ceylon support was merge 2016-06-02: https://github.com/jneen/rouge/pull/414

## SyntaxHighlighter

http://alexgorbatchev.com/SyntaxHighlighter/

This was used in ceylon-lang.org, ceylondoc and Herd. Not pushed upstream.

Source: https://github.com/syntaxhighlighter

Our source: https://github.com/ceylon/ceylon-compiler/blob/5fb179e85acde3078e6dbdaf6f5ac785d0761834/src/com/redhat/ceylon/ceylondoc/resources/shBrushCeylon.js

## Sublime Text

http://www.sublimetext.com

This is used in GitHub syntax highlighting.

Source: https://github.com/jeancharles-roger/ceylon-sublimetext

## Vim

This it not pushed upstream yet.

Source: http://code.google.com/p/vim/source/browse/runtime/syntax/java.vim (for example)

Our source: https://github.com/chochos/ceylon-vim

## Visual Studio Code

https://code.visualstudio.com

Published on the official marketplace: https://marketplace.visualstudio.com/items/bjansen.Ceylon, install using:

    ext install Ceylon

Our source : https://github.com/bjansen/vs.language.ceylon
