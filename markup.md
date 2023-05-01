# Headings
To create a heading, add one to six # symbols before your heading text. The number of # you use will determine the hierarchy level and typeface size of the heading.

\# A first-level heading<br>
\#\# A second-level heading<br>
\#\#\# A third-level heading<br>

# A first-level heading
## A second-level heading
### A third-level heading
---

# Code
You can call out code or a command within a sentence with single backticks. The text within the backticks will not be formatted. You can also press the Command+E (Mac) or Ctrl+E (Windows/Linux) keyboard shortcut to insert the backticks for a code block within a line of Markdown.

Some basic Git commands are:<br>
\`\`\`<br>
git status<br>
git add<br>
git commit<br>
\`\`\`

```
git status
git add
git commit
```

# Supported color models
In issues, pull requests, and discussions, you can call out colors within a sentence by using backticks. A supported color model within backticks will display a visualization of the color.

The background color is \`\#ffffff\` for light mode and \`\#000000\` for dark mode.

The background color is `#ffffff` for light mode and `#000000` for dark mode.


# Links
You can create an inline link by wrapping link text in brackets [ ], and then wrapping the URL in parentheses ( ). You can also use the keyboard shortcut Command+K to create a link. When you have text selected, you can paste a URL from your clipboard to automatically create a link from the selection.

You can also create a Markdown hyperlink by highlighting the text and using the keyboard shortcut Command+V. If you'd like to replace the text with the link, use the keyboard shortcut Command+Shift+V.

This site was built using \[GitHub Pages\]\(https://pages.github.com/\).<br><br>
This site was built using [GitHub Pages](https://pages.github.com/).


# Images
You can display an image by adding ! and wrapping the alt text in [ ]. Alt text is a short text equivalent of the information in the image. Then, wrap the link for the image in parentheses ().

\!\[Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.\]\(https://placehold.co/150x100\)

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://placehold.co/150x100)


# Lists
You can make an unordered list by preceding one or more lines of text with -, *, or +.<br>
\- George Washington<br>
\* John Adams<br>
\+ Thomas Jefferson<br>

- George Washington
* John Adams
+ Thomas Jefferson


### To order your list, precede each line with a number.

1. James Madison
2. James Monroe
3. John Quincy Adams

### Task lists
To create a task list, preface list items with a hyphen and space followed by [ ]. To mark a task as complete, use [x].

- \[x\] #739
- \[ \] https://github.com/octo-org/octo-repo/issues/740
- \[ \] Add delight to the experience when all tasks are complete :tada:
<br><br>
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:

---

# Creating a table
You can create tables with pipes | and hyphens -. Hyphens are used to create each column's header, while pipes separate each column. You must include a blank line before your table in order for it to correctly render.

\| First Header   \| Second Header  \|<br>
\| \------------- \| \------------- \|<br>
\| Content Cell   \| Content Cell   \|<br>
\| Content Cell   \| Content Cell   \|<br>

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |
