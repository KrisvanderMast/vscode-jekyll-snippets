# <a href="http://jekyllrb.com" title="Jekyll" target="_blank"><img src="http://jekyllrb.com/img/logo-2x.png" atl="Jekyll Logo" width="250"></a> snippets package for Visual Studio Code.

Jekyll snippets for Visual Studio Code. This is a combination of both the the [sublime-jekyll package](https://github.com/23maverick23/sublime-jekyll)
by [@23maverick23.](https://github.com/23maverick23) and the [atom-jekyll package](https://atom.io/packages/jekyll-snippets) by [@jasonhodges](https://github.com/jasonhodges).

## HTML, Liquid, and Markdown Support

If you are downloading the extension for the first time you'll be prompted that the [Liquid Languages Support](https://marketplace.visualstudio.com/items?itemName=neilding.language-liquid) will also be installed. This happens because of the `extensionDependencies` which elminates the need to manaully fetch another extension, which was referenced in issue [#3](https://github.com/ginfuru/vscode-jekyll-snippets/issues/3) by @graffen.

Markdown support has also been added which was referenced in issue [#7](https://github.com/ginfuru/vscode-jekyll-snippets/issues/7) by @Haroenv. I haven't found a markdown grammer file that highlights liquid syntax

HTML support has benen added due to some odd behave from extenions I use which doesn't provide support `liquid`

### Why you might want liquid extension?

1. ✔ Provides syntax highlighing for your liquid tags.
2. ✔ Provides liquid extension and support.
    * ~~By changing your `HTML` syntax to `HTML(Liquid)` will allow this extension/snippets to work as expected. My reasoning for doing this is/was to prevent clutter and possible conflicts with other snippets inside of IntelliSense/autocomplete. _(Who really likes scrolling through and selecting the wrong autocomplete by mistake?)_~~  `¯\_(ツ)_/¯`
3. ✔ Provide syntax highlighting for liquid tags - ie: `{{ site.baseurl }}` & `{% for something in this_file %} {% endfor %}`
     * By changing your `HTML` syntax to `HTML(Liquid)`


If you think this should work with vanilla HTML and Markdown let me know with an issue or create a pull-request with a fix. _(I personally don't see a need because, I enjoy the syntax highlighting)_

## Roadmap & Contributing

I do have plans to continue adding more snippets, based on the [Jekyll Tips Cheat Sheet](http://jekyll.tips/jekyll-cheat-sheet/), but **PLEASE** feel free to contribute and/or file issues with requests. If you do want to contribute please make sure to create a feature branch and when creating a pull request to rebase or squash prior to.

> ##### Thanks again to [@23maverick23.](https://github.com/23maverick23) and [@jasonhodges](https://github.com/jasonhodges)
