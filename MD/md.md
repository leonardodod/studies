# Headings

To create a heading, add number signs (#) in front of a word or phrase. The number of number signs you use should correspond to the heading level. For example, to create a heading level three < h3 > (without spaces), use three number signs (e.g., ### My Header).

| Markdown               | Rendered Output |
| ---------------------- | --------------- |
| # Heading level 1      | <h1>Title</h1>  |
| ## Heading level 2     | <h2>Text</h2>   |
| ### Heading level 3    | <h3>Title</h3>  |
| #### Heading level 4   | <h4>Text</h4>   |
| ##### Heading level 5  | <h5>Title</h5>  |
| ###### Heading level 6 | <h6>Text</h6>   |

# Heading Best Practices

Markdown applications don’t agree on how to handle a missing space between the number signs (#) and the heading name. For compatibility, always put a space between the number signs and the heading name.

# Paragraphs

To create paragraphs, use a blank line to separate one or more lines of text.

# Paragraph Best Practices

Unless the paragraph is in a list, don’t indent paragraphs with spaces or tabs.

# Line Breaks

To create a line break (<br>), end a line with two or more spaces, and then type return.

# Line Break Best Practices

You can use two or more spaces (commonly referred to as “trailing whitespace”) for line breaks in nearly every Markdown application, but it’s controversial. It’s hard to see trailing whitespace in an editor, and many people accidentally or intentionally put two spaces after every sentence. For this reason, you may want to use something other than trailing whitespace for line breaks. If your Markdown application supports HTML, you can use the <br> HTML tag.

For compatibility, use trailing white space or the <br> HTML tag at the end of the line.

There are two other options I don’t recommend using. CommonMark and a few other lightweight markup languages let you type a backslash (\) at the end of the line, but not all Markdown applications support this, so it isn’t a great option from a compatibility perspective. And at least a couple lightweight markup languages don’t require anything at the end of the line — just type return and they’ll create a line break.

# Emphasis

You can add emphasis by making text bold or italic.

## Bold

To bold text, add two asterisks or underscores before and after a word or phrase. To bold the middle of a word for emphasis, add two asterisks without spaces around the letters.

## Bold Best Practices

Markdown applications don’t agree on how to handle underscores in the middle of a word. For compatibility, use asterisks to bold the middle of a word for emphasis.

## Italic

To italicize text, add one asterisk or underscore before and after a word or phrase. To italicize the middle of a word for emphasis, add one asterisk without spaces around the letters.

## Italic Best Practices

Markdown applications don’t agree on how to handle underscores in the middle of a word. For compatibility, use asterisks to italicize the middle of a word for emphasis.

## Bold and Italic

To emphasize text with bold and italics at the same time, add three asterisks or underscores before and after a word or phrase. To bold and italicize the middle of a word for emphasis, add three asterisks without spaces around the letters.

## Bold and Italic Best Practices

Markdown applications don’t agree on how to handle underscores in the middle of a word. For compatibility, use asterisks to bold and italicize the middle of a word for emphasis.

# Tables

To add a table, use three or more hyphens (---) to create each column’s header, and use pipes (|) to separate each column. For compatibility, you should also add a pipe on either end of the row.

| Syntax    | Description |
| --------- | ----------- |
| Header    | Title       |
| Paragraph | Text        |

# Fenced Code Blocks

The basic Markdown syntax allows you to create code blocks by indenting lines by four spaces or one tab. If you find that inconvenient, try using fenced code blocks. Depending on your Markdown processor or editor, you’ll use three backticks (```) or three tildes (~~~) on the lines before and after the code block. The best part? You don’t have to indent any lines!

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

# Syntax Highlighting

Many Markdown processors support syntax highlighting for fenced code blocks. This feature allows you to add color highlighting for whatever language your code was written in. To add syntax highlighting, specify a language next to the backticks before the fenced code block.

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

# Task Lists

Task lists allow you to create a list of items with checkboxes. In Markdown applications that support task lists, checkboxes will be displayed next to the content. To create a task list, add dashes (-) and brackets with a space ([ ]) in front of task list items. To select a checkbox, add an x in between the brackets ([x]).

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

### Basic Syntax

All of it came from https://www.markdownguide.org/basic-syntax

### Extended Syntax

All of it came from https://www.markdownguide.org/extended-syntax/#fenced-code-blocks
