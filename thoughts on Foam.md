# Thoughts on Foam

It's still in it's early days, but so far I like it.

The writing experience is fantastic. I love working with raw Markdown files in VS Code rather than dealing a clunky web app GUI.

I don't love how the notes look when published to GitHub Pages (I'm not doing anything special here, just publishing the raw .md files). The reason you'll see some [square brackets] when one note links to another is because of the way that [backlinking](https://foambubble.github.io/foam/backlinking) is implemented in the tool, which relies on a wiki-links style.

In the future I might add a small build step in between writing and publishing that strips out the brackets (could probably do this with a GH action that replaces the wiki-link style with a standard markdown link). I'd _like_ the content of the site to not expose unnecessary information about how it was composed, but for now, it will do. I am trying to just **write more** rather than constantly yak-shaving/bikeshedding.
