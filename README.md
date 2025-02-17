# GitHub Markdown Snippets
Helpful Sublime Text snippets to get you started with GitHub flavored Markdown by letting you type the plain old HTML tags.

Supports english and russian keyboard layouts (by [dclimber](https://github.com/dclimber/)).

## Installation

### Manual

- Clone the repository or download the [ZIP](https://github.com/dclimber/github-markdown-snippets/archive/master.zip)
- Extract the archive
- Put it in your **Packages**( `Preferences > Browse Packages...` ) directory.  

### Using with Emmet
If you have Emmet installed, tab triggers may not function as expected due to [this](https://github.com/sergeche/emmet-sublime#tab-key-handler).

To get around the problem, go to 
```
Preferences > Package Settings > Emmet > User Settings 
```
and add the following in your settings file.

```
{
    "disable_tab_abbreviations_for_scopes": "text.html.markdown"
}
```

This should let markdown snippets take precedence over emmet's tab to expand abbreviations feature and provide correct snippets.

Note that any tab trigger not set by this plugin will be converted to HTML tags which is convenient for people
who want to use HTML tags inside Markdown files.

## Usage
A consolidated guide is available [here](http://praveenpuglia.github.io/github_markdown_snippets). 

Type a tag name and hit tab. That's it! :relaxed:

:snowflake: Long tags like `blockquote` are shortened for power use.

## List of Tab Triggers

```
h1 | р1     // Heading 1
h2 | р2     // Heading 2
h3 | р3     // Heading 3
h4 | р4     // Heading 4
h5 | р5     // Heading 5
h6 | р6     // Heading 6
```
# Heading 1  
## Heading 2  
### Heading 3  
#### Heading 4  
##### Heading 5
###### Heading 6
```
b | и         // Bold
i | ш         // Italic
bq | ий        // Blockquote
strike | ыекшлу    // Strikeout
hr | рк        // Horizontal Rule, Divider
```
**Bold Text** 

*Italic Text* 

> Put a nice, beautiful
> quote here...

~~Strike Through~~ 

---

```
code | сщву    // Inline Code
pre | зку     // Code Block with language based highlighting.
```
`Inline Code Snippet`

```javascript
var message = "Code Block";
alert( message );
```

```
a | ф      // Anchor
img | шьп    // Image
```
[Link Title](Link) 

![Puppies are cute](https://c1.staticflickr.com/5/4112/5170590074_714d36db83_b.jpg) 

```
ol | щд       // Ordered List
ul | гд       // Unordered List
table | ефиду    // Table
```

1. First Item
2. Second Item
3. Third Item


- I
- Love
- Markdown

| Column 1 | Column 2 |
| ------------- | ------------- |
| Cell 1-1 | Cell 1-2 |
| Cell 2-1 | Cell 2-2 |
