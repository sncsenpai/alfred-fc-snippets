# Fraction.Characters Snippet for Alfred

I am an absolute fan of the [Alfred][1] app for ~MacOS~ macOS, and I'm pretty sure that I've only just scraped the surface of its capabilities.

In my current role, I create a tonne of documentation so have always looked for ways to speed up the typing of fraction symbols. Let me explain, I stay away from any rich-text editors (which would usually automatically format the text for you) to create the main skeleton of my documentation and rely heavily on Markdown. This way I am totally focused on the semantics of the documents and not the styling, as that gets in the way.

With that created my own snippet collection of fraction symbols, like ½, ⅛, etc. to ease my experience. So, I felt it wise to share this. I mean, it's not spectacular or a big implementation, but thought someone else may benefit from it.

# Install instructions

1. Head over to [Alfred][1] to download the latest version of their app.
2. Download the latest snippets from the [Release][2] page, then open it.
3. In the import popup deselect (uncheck) the **Strip snippets of ‘auto expand’ flag** option.
4. Click the **Import** button.
5. Select (check) the **Automatically expand snippets by keyword** option.

# Usage

The snippets run with the prefix of `::`, followed by the fraction.

So if you want ⅛ you would type `::1/8` and Alfred will automatically complete it for you. 

## Notes 

I chose to invoke this with a special character, so that it is invoked *when intended*.

Also, I did add some shortcuts for common phrases, including their usual form for consistency.

Examples:

* `::half` and `::1/2` would give you `½`
* `::third` and `::1/3` would give you `⅓`
* `::quarter` and `::1/4` would give you `¼`

[1]: https://alfredapp.com "Get the Alfred app"
[2]: https://github.com/sncsenpai/alfred-fc-snippets/releases "Release page"
