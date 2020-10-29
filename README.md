# Asciidoc localization
Localization resources for Asciidoc

This repository includes source Asciidoc files (English) and their dummy translations (Spanish), the translated Asciidoc files converted to HTML, a parser (memoQ), XLIFF files (memoQ) and a TMX.

NOTE: The parser is created based on the source Asciidoc files included in this repository. When using it to translate other Asciidoc files, it might need to be modified.

The parser is able to deal with a couple of delicate things in Asciidoc such as:
- alt text in images
- comments
- formatting
- hyperlinks, footnotes
- paragraph delimiters
- xrefs

In order to make everything work properly, authors of Asciidoc files need to:
- avoid multi-line comments
- avoid obsolete newlines
- start every file with a title
- start paragraphs after comments with a delimiter
