---
title: Theme installation
subtitle: This document covers the setup and options of theme feature described in the doc title
author: sara
tags: [setup]
---


  {% include ad.html type="small-leaderboard" %}

# Hi This is Heading 

Install the dependencies with [Bundler](http://bundler.io/):

```bash
bundle install
```

Run the following to generate your site:
```bash
bundle exec jekyll serve
```
<!-- This is a button toggling the modal -->
<button class="uk-button uk-button-default uk-margin-small-right" type="button" uk-toggle="target: #modal-example">Open</button>

<!-- This is an anchor toggling the modal -->
<a href="#modal-example" uk-toggle>Open</a>

<!-- This is the modal -->
<div id="modal-example" uk-modal>
    <div class="uk-modal-dialog uk-modal-body">
        <h2 class="uk-modal-title">Headline</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        <p class="uk-text-right">
            <button class="uk-button uk-button-default uk-modal-close" type="button">Cancel</button>
            <button class="uk-button uk-button-primary" type="button">Save</button>
        </p>
    </div>
</div>

You can find more on [Deployment Methods](https://jekyllrb.com/docs/deployment-methods/) page on Jekyll website.

## Markdown output 🛫

[CKEditor 5](https://ckeditor.com/) can be configured to output Markdown instead of HTML. Markdown is a lightweight markup language that you can use to add formatting to plain text documents. Use the **Source** button to check and edit the Markdown source code of this content.

The editor-produced Markdown output supports most essential features, like [links](https://ckeditor.com/), **different** kinds of _emphasis_, `inline code formatting`, or code blocks:

```css
p {
    text-align: center;
    color: red;
}
```

<div id="test-target" class="uk-height-large uk-background-cover uk-light uk-flex" uk-parallax="bgy: -200" style="background-image: url('https://i.pinimg.com/originals/bc/8d/02/bc8d026b258afad9a3d4b1b84ed6721f.gif');">
  
    <div class="uk-text-center uk-margin-auto uk-margin-auto-vertical" uk-parallax="target: #test-target; y: 100,0"> {% include ad.html type="small-leaderboard" %}
    </div> 

</div>

## Markdown input 🛬

Thanks to the [autoformatting feature](https://ckeditor.com/docs/ckeditor5/latest/features/autoformat.html), you can use Markdown syntax when writing. Try it out - use these (or any other) Markdown shortcuts in the editor to format the content on the fly 🚀!

| Inline formatting | Shortcut |
| --- | --- |
| **Bold** | Type `**` or `__` around your text. |
| _Italic_ | Type `*` or `_` around your text. |
| `Code` | Type `ˋ` around your text. |
| ~Strikethrough~ | Type `~~` around your text. |

Shh! 🤫 Markdown has very basic support for tables. Some advanced table-related features like table or cell styling were disabled in this demo.

## Block formatting

You can also use Markdown to create various text blocks, such as:

*   Block quotes - Start a line with `﹥` followed by a space.
*   Headings:
    1.  Heading 1 - Start a line with `#` followed by a space.
    2.  Heading 2 - Start a line with `##` followed by a space.
    3.  Heading 3 - Start a line with `###` followed by a space.
*   Lists, including nested ones:
    *   Numbered lists - Start a line with `1.` or `1)` followed by a space.
    *   Bulleted lists - Start a line with `*` or `-` followed by a space.
    *   To-do lists - Start a line with `[ ]` or `[x]` followed by a space to insert an unchecked or checked list item.
*   Code blocks - Start a line with `ˋˋˋ`.
*   Horizontal lines - Start a line with `---`

{% include ad.html type="small-leaderboard" %}