# Concise GitHub Markdown Reference
==================

Refer to [GitHub Help](https://help.github.com/categories/writing-on-github/) for detailed information.

## Contents
1. Headings
2. Inline Styles
3. Links
4. Code Blocks
5. Images
6. Tables
7. Separators

## 1. Headings
Put appropriate number of '#' before the heading text.

# H1 ('# H1')
## H2 ('## H2')
### H3 ('### H3')

## 2. Inline Styles
Enclose `inline code` in backticks: \`inline code\`

Enclose *italicized text* in single asterisks: \*italicized text\*

Enclose **bold text** in double asterisks: \*\*bold text\*\*

Escape special characters with a backslash: \\ (For example, write two backslashes to output one backslash)

## 3. Links
### 3.1 External Links
GitHub makes links of URLs: www.duckduckgo.com

To make a linke like [Duck Duck Go](http://www.duckduckgo.com): \[Duck Duck Go\]\(http://www.duckduckgo.com)

### 3.2 Internal Links
To make a target<a name="myTarget"/>: \<a name="myTarget" /\>

To link to that target: \[link text\]\(#myTarget)

## 4. Code
### 4.1 Inline code
Enclose `inline code` in backticks: \`inline code\`

### 4.2 Code Blocks
Enclose code blocks in backticks. Use a keyword for syntax highlighting.

\`\`\`javascript<br>
if (myAnswer == 42) {<br>
  Console.log("Now what was that question again?");<br>
}<br>
\`\`\`

```javascript
if (myAnswer == 42) {
  Console.log("Now what was that question again?");
}
```

## 5. Images

