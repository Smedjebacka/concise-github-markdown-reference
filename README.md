# Concise GitHub Markdown Reference

Refer to [GitHub Help](https://help.github.com/categories/writing-on-github/) for detailed information.

## Contents
[1. Headings](#Headings)<br>
[2. Inline Styles](#InlineStyles)<br>
[3. Links](#Links)<br>
[4. Code](#Code)<br>
[5. Images](#Images)

## 1. Headings <a name="Headings" />
Put appropriate number of '#' before the heading text.

# H1 ('# H1')
## H2 ('## H2')
### H3 ('### H3')

## 2. Inline Styles <a name="InlineStyles" />
Enclose `inline code` in backticks: \`inline code\`

Enclose *italicized text* in single asterisks: \*italicized text\*

Enclose **bold text** in double asterisks: \*\*bold text\*\*

Escape special characters with a backslash: \\ (For example, write two backslashes to output one backslash)

## 3. Links <a name="Links" />
### 3.1 External Links
GitHub makes links of URLs: www.duckduckgo.com

To make a link like [Duck Duck Go](http://www.duckduckgo.com): \[Duck Duck Go\]\(http://www.duckduckgo.com)

### 3.2 Internal Links
To make a target<a name="myTarget"/>: \<a name="myTarget" /\>

To [link](#myTarget) to that target: \[link text\]\(#myTarget)

## 4. Code <a name="Code" />
### 4.1 Inline Code
Enclose `inline code` in single backticks: \`inline code\`

### 4.2 Code Blocks
Enclose code blocks in triple backticks. Use a [keyword](https://github.com/github/linguist/blob/master/lib/linguist/languages.yml) for syntax highlighting.

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

## 5. Images <a name="Images" />
Place a '!' before the image link: !\[My image title\]\(/images/test.png)

Use PNG, JPEG or GIF images.

### 5.1 Image URLs on github\.com
Use relative links starting from the project root: /my-folder-in-root/my-file.png

### 5.2 Image URLs on GitHub Pages \(username\.github\.io)
Use full URL: 
Not sure if this is best pratice, but it works :)






