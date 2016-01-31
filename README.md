# GitHub-Markdown.tmbundle
Provides some [GitHub Flavoured Markdown](https://help.github.com/articles/github-flavored-markdown/) extensions for TextMate to make working with GitHub Flavoured Markdown nicer.

## Features
- Add a new "Preview" command using [Redcarpet](https://github.com/vmg/redcarpet) to render GitHub Flavoured Markdown
- Use Helvetica for the Markdown editor font and make it match the preview size
- Render all Markdown editor headings the same relative size as in the preview
- Use the default font (i.e. Helvetica) for the Markdown editor settings
- Use the default font size for the Markdown editor hash/pound prefix
- Set a grey background colour and reduce the size of the monospaced text in the Markdown editor
- Support triple-backtick raw blocks and support syntax highlighting for GitHub's top 10 languages and shell scripts (others can be added trivially)
- Support and highlight GitHub Flavoured Markdown strikethroughs, tables, references and italics

## Installation
### TextMate 2
```bash
mkdir -p ~/Library/Application\ Support/Avian/Bundles
cd ~/Library/Application\ Support/Avian/Bundles
git clone https://github.com/mikemcquaid/GitHub-Markdown.tmbundle
```

### TextMate 1
```bash
mkdir -p ~/Library/Application\ Support/TextMate/Bundles
cd ~/Library/Application\ Support/TextMate/Bundles
git clone https://github.com/mikemcquaid/GitHub-Markdown.tmbundle
osascript -e 'tell app "TextMate" to reload bundles'
```

## Status
The above features are tested and working for my day-to-day.

Tested using TextMate 2. May work in TextMate 1 or Sublime Text; I've no idea.

[Patches welcome](https://github.com/mikemcquaid/GitHub-Markdown.tmbundle/pulls).

## Contact
[Mike McQuaid](mailto:mike@mikemcquaid.com)

## License
GitHub-Markdown.tmbundle is licensed under the [MIT License](http://en.wikipedia.org/wiki/MIT_License). The full license text is
available in
[LICENSE.txt](https://github.com/mikemcquaid/GitHub-Markdown.tmbundle/blob/master/LICENSE.txt).
