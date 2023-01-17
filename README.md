<h1 align="center" >Synthwave x Fluoromachine & epic animations & contrast<br/><br/>
</h1>

<p align="center"><strong>This theme brings crazy 80's animations into your VS Code 🚀🎉 </strong></p>

<br/><br/>

_This is a fork of @thecodemonkey's <a href="https://github.com/thecodemonkey/synthwave-x-fluoromachine-epic-animations">synthwave-x-fluoromachine-epic-animations</a>, which is a fork of <a href="https://github.com/webrender/synthwave-x-fluoromachine">synthwave-x-fluoromachine</a>, which is also fork of @robbowen's [Synthwave '84 theme](https://marketplace.visualstudio.com/items?itemName=RobbOwen.synthwave-vscode), merged with @fullerenedream's [Fluoromachine](https://colorsublime.github.io/themes/FluoroMachine/) theme and @74th's [Monokai Charcoal high contrast](https://github.com/74th/vscode-monokaicharcoal) purple theme for VSCode._

<br/>

<p align="center">
  <img src="https://raw.githubusercontent.com/coltwillcox/synthwave-x-fluoromachine-contrast/master/screens/main.gif" /><br/>
  <i style="font-size: .8em">Main screen with animated background, logo and shiny text</i>
</p>
<br/><br/>
<p align="center">
  <img src="https://raw.githubusercontent.com/coltwillcox/synthwave-x-fluoromachine-contrast/master/screens/editor.gif" /><br/>
  <i style="font-size: .8em">Editor screen with glowing cursor and selection</i>
</p>

<br/> <br/>

## Why?

The job of a software developer is hard and often too serious. You always have to be productive and effective. But sometimes you need to take the time to just be a nerd 🤓 or to just have fun again. This theme is exactly for such times! Such nerdy times need to be celebrated accordingly 🎉🦄

<br/> <br/>

## Installation

Unfortunately, the current installation is a bit complicated.
A hassle-free installation is already in development.
Until then, the following steps must be performed to install the theme:

1. Install this theme
2. Install [Custom CSS and JS Loader](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css) VS Code extension
3. Link the CSS file from this extension in your VS Code settings.json:

```
On Mac it might look something like the snippet below:

{
  "vscode_custom_css.imports": [
    "file:///Users/{your username}/.vscode/extensions/coltwillcox.synthwave-x-fluoromachine-contrast/synthwave-x-fluoromachine.css",
    "file:///Users/{your username}/.vscode/extensions/coltwillcox.synthwave-x-fluoromachine-contrast/epic-80s-transitions.css",
    "file:///Users/{your username}/.vscode/extensions/coltwillcox.synthwave-x-fluoromachine-contrast/logo.css"
  ]
}

Windows might resemble:

{
  "vscode_custom_css.imports": [
    "file:///C:/Users/{your username}/.vscode/extensions/coltwillcox.synthwave-x-fluoromachine-contrast/synthwave-x-fluoromachine.css",
    "file:///C:/Users/{your username}/.vscode/extensions/coltwillcox.synthwave-x-fluoromachine-contrast/epic-80s-transitions.css",
    "file:///C:/Users/{your username}/.vscode/extensions/coltwillcox.synthwave-x-fluoromachine-contrast/logo.css"
  ]
}
```

4. `epic-80s-transitions.css` is optional and brings crazy 80's animations into your VS Code!
5. `logo.css` is also optional and changes VS Code logo.
6. Edit settings.json and add:

```
"workbench.colorCustomizations": {
	"minimap.background": "#00000000",
	"tab.inactiveBackground": "#0c0e14"
}
```

7. From the command panel, select `Reload Custom CSS and JS`. You'll need to run this command every time vscode updates.

<br/><br/>

## Font

The font being used in the screenshot above is [Victor Mono](https://rubjo.github.io/victor-mono/).

<br/><br/>

## Themes

Icon theme is [Sweet vscode Icons](https://marketplace.visualstudio.com/items?itemName=EliverLara.sweet-vscode-icons).
<br/>
XFCE/GTK theme is [Sweet](https://www.xfce-look.org/p/1253385).

<br/><br/>

## Contibution

All contributions are welcome, including issues, new docs as well as updates and tweaks, blog posts, workshops, and more.

<br/><br/>

## License

i ❤️ MIT
