ScalableCSS !
====================

ScalableCSS is a CSS framework based on LESS CSS preprocessor (http://lesscss.org). It's main purpose is to let you manage and extend website's stylesheets easily.

It comes with integrated OOCSS Grid (http://github.com/stubbornella/oocss/wiki/Grids) by default, however you can use any Grid System you like instead if you need any at all.

Code and comments are self explanatory so you should feel fine by reading through the source. A good starting point is 'less/base.less', which is an example of root stylesheet file. You can create multiple siblings of base.less and all of them will use the same codebase which is highly flexible when it comes to managing multiple stylesheets. However, in most cases it's recommended to have only one stylesheet (like base.less) per website for non-responsive designs. Read the comments in base.less for more info.

Install ScalableCSS from within your main repo
--------------------

You most likely would want to integrate ScalableCSS into your existing project. So we assume you've already changed directory to your project.

``` html
$ git submodule add git://github.com/scalablecss/scalablecss.git scalablecss/system
$ cp -r scalablecss/system/setup_files/* scalablecss/
$ git add .gitmodules scalablecss/*
$ git commit -m 'Installed ScalableCSS as a Submodule'
```

Upgrade ScalableCSS from within your main repo
--------------------

``` html
$ cd scalablecss/system && git pull && cd ../../
$ git add scalablecss/system
$ git commit -m 'Upgraded ScalableCSS to the latest state'
```


Cloning your repo
--------------------

Use --recursive flag in order to retrieve submodules files together with your main repo

``` html
$ git clone --recursive git://your_main_repo_path
```

Credits
--------------------

Following projects are the original inspiration for ScalableCSS:

+ LESS CSS
+ HTML5-Boilerplate
+ Semantic.gs
+ 320andup
+ Twitter Bootstrap
+ Workless
+ Inuit.css
+ oocss by stubbornella
+ Debugging CSS Media Queries by Johan Brook

License
--------------------

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to <http://unlicense.org/>
