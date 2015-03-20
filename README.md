# gengojs-sublime-snippets

The official snippets for gengo.js http://www.gengojs.com/ 

##Install

###Package Control:

The easiest way to install gengo.js snippets is through [Package Control](https://packagecontrol.io/installation).  Once you install Package Control, restart Sublime Text 2(3) and open the Command Palette (`Command+Shift+P` on OS X, `Ctrl+Shift+P` on Linux/Windows). Select `Package Control: Install Package`, then search and select `Gengojs`. Once intstalled, Package Control will keep you up to date whenever a new version is released.

###GitHub:

Download the latest source from [GitHub](https://github.com/iwatakeshi/gengojs-sublime-snippets/) and copy the folder to your Sublime Text `Packages` directory.

###Git:

Clone the repository in your Sublime Text `Packages/User` directory:

git clone `https://github.com/iwatakeshi/gengojs-sublime-snippets.git`
The `Packages` directory is located at:

OS X:

`~/Library/Application Support/Sublime Text 2(3)/Packages/User`

Windows:

`%APPDATA%\Sublime Text 2(3)\Packages\User`

Portable version:

`Sublime Text 2(3)\Data\Packages\User\Gengojs`

##Usage:

Just type:

```
__(      -->    __(phrase, [arguments)
__l      -->    __l("locale")
__date   -->    __l("locale").date(options).format(date)
__time   -->    __l("locale").time(options).format(time)
__number -->    __l("locale").number(options).format(number)
__moment -->    __l("locale").moment(string)
```

or open the Command Palette, type `gengo` and select the desired snippet.

Currently, the snippet works in Jade (`.jade`) and Handlebars (`.hbs`). To add support for your favorite template, just fork and pull!
