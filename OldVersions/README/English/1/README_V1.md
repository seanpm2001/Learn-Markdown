
***

![/MD.png](/MD.png)

### Learning Markdown

I am pretty experienced with markdown at the moment, but I still have more to learn. This document will go over my current knowledge of the markdown markup language.

This document uses version 0.30 of the CommonMark markup specification for the markdown markup language.

#### Comments in Markdown

Comments in Markdown are the same as most other markup languages (such as XML, HTML, etc.) they are written like this:

```markdown
<!-- This is a comment !-->
<!-- The same syntax for single-line
comments is also used in block comments.
!-->
```

#### Break keyword in Markdown

Markdown does not support the break statement/keyword, it has no need for it.

To this day, I am still not entirely sure what the `break` keyword does, but most languages support it.

#### Headings in Markdown

Headings in Markdown work like so:

# Heading 1

```markdown
# Heading 1
```

## Heading 2

```markdown
## Heading 2
```

### Heading 3

```markdown
### Heading 3
```

#### Heading 4

```markdown
#### Heading 4
```

##### Heading 5

```markdown
##### Heading 5
```

###### Heading 6

```markdown
###### Heading 6
```

Just like HTML and other document standards, a 7th heading level does not exist. Attempting to do so will result in plain unformatted text, rather than a heading

####### Heading 7 (non-existant)

```markdown
####### Heading 7 (non-existant)
```

#### Lists in Markdown

Lists can be formed in Markdown in multiple ways. The following examples showcase bullet lists, and numbered lists.

##### Bullet list

```markdown
* Bullet list entry 1

* Bullet list entry 2
```

Originally, I learned that every line has to have a space between it and the previous line, due to bugs with markdown at the time on GitHub. It still applies in some areas, but not here:

```markdown
* Condensed bullet list entry 1
* Entry 2
```

##### Numbered list

```markdown
1. Start of list
2. GitHub
3. Python
4. CommonMark
5. CMark
6. Java
7. HTML5
8. GitHub
9. XML
10. End of list
```

Additionally, you can combine bullets and numbers to form roman numeral lists:

```markdown
* 1. Roman 1 (I)
* 2. Roman 2 (II)
* 3. Roman 3 (III)
* 4. Roman 4 (IV)
* 5. Roman 5 (V)
* 6. Roman 6 (VI)
* 7. Roman 7 (VII)
* 8. Roman 8 (VIII)
* 9. Roman 9 (IX]
* 10. Roman 10 (X)
```

#### Quote blocks in markdown

Quote blocks/indented blocks can be made in markdown like so:

```markdown
> "Imagination is more important than knowledge" - Albert Einstein

> > It doesn't have to be a quote

> > > Layer 3

> > > > Layer 4

> > > > > Layer 5

> > > > > > Layer 6

> > > > > > > This type of formatting isn't limited to 6 levels

> > > > > > > > Layer 8

> > > > > > > > > Layer 9

> > > > > > > > > > Layer 10 (I will stop here)
```

#### Bold in Markdown

Text can be bolded in Markdown by doing the following:

```markdown
This text is not bold

**This text is bold**

<b>This text is also bold</b>

<em>Additionally, this text is also bold</em>
```

#### Italics in Markdown

Text can be italicized in Markdown by doing the following:

```markdown
This text is not italicized

*This text is italicized*

_This text is also italicized_

<i>Additionally, this text is also italicized</i>
```

#### Code blocks in Markdown

A code block can be formed in Markdown by doing the following:

````markdown

```markdown
To add a markdown codeblock inside a markdown codeblock, use an extra apostrophe on the first codeblock.
```

```
This codeblock has no language definition, so it is plain text
```

```python
print("Hello, Markdown")
```

```javascript
console.log("Hello, Markdown");
```

There are too many to list, so I will stop here for now.

````

##### Images in Markdown

Referencing an image in Markdown is very easy, and is done like so:

```markdown
![Alt text](/MD.png)

[This is a link. It is not to be confused with an image. Make sure not to forget the exclamation point!](/MD.png)
```

#### Horizontal Lines in Markdown

Horizontal Lines/divider lines are supported in Markdown. They can be defined like so:

```markdown

***

Section 1

---

Section 2

***

```

#### Hyperlinks in Markdown

Hyperlinks are supported in Markdown. They can be defined like so:

```markdown
[GitHub](https://github.com/)
```

#### Dropdowns in Markdown

Since Markdown can embed HTML5, most HTML features are readily available. Here is how you make a dropdown in markdown:

```markdown
<details><summary>Click/tap here to expand/collapse this section</summary>

Lorem Ipsum

</details>
```

Here is how you make a dropdown that is open by default:

```markdown
<details open><summary><p lang="en">Click/tap here to expand/collapse this section</p></summary>

Lorem Ipsum

</details>
```

#### Tables in Markdown

Tables can be defined like so in Markdown:

##### 2 column table

This is a 2 column table:

```markdown
| Column 1 | Column 2 |
|---|---|
| Row 1 | Lorem |
| Row 2 | Ipsum |
```

##### 3 column table

This is a 3 column table:

```markdown
| Column 1 | Column 2 | Column 3 |
|---|---|---|
| Row 1 | Lorem | Ipsum |
| Row 2 | Lorem | Ipsum |
```

You must fill every entry in the table, or it won't render.

#### Videos in Markdown

I don't know how to embed videos in markdown yet, as I never tried.

#### Audio in Markdown

I don't know how to embed audio files/clips in markdown yet, as I never tried.

#### Source

The majority of my Markdown knowledge comes from experimenting, viewing other peoples markdown, and reading commonmark documentation on the commonmark specification page and Wikipedia.

This is a pretty ambitious task, and I am hoping I didn't forget anything.

#### Other knowledge of Markdown

1. Markdown is not a curly bracket language, and also does not use semicolons at the end of each line

2. Markdown is a lighweight markup language

3. Markdown is most widely used for documentation.

4. Markdown uses 4 different file extensions: `*.md` `*.mkd` `*.mdown` and `*.markdown`

5. Markdown is a language recognized by GitHub, but you have to use a `.gitattributes` file to recognize it in the GitHub Linguist

6. Markdown is a markup language

7. Markdown can be shortened to either MDown or MD

8. Before I started using GitHub and came across markdown files, I was very confused by them, as I didn't know how to open them, or view them. Less than a year later, I joined GitHub, and started using them excessively.

9. I was unsure if it was possible to write a documetn about learning markdown in markdown, as I didn't know how to encapsulate a code block inside a code block. Turns out all you need is to have 4 apostrophes in the main block, instead of 3.

10. I may not have listed everything I know here. I feel like I am missing something, but I currently can't determine what it is.

11. No other knowledge of Markdown at the moment.

***

**File version:** `1 (2022, Monday, April 18th at 12:31 am PST)` - Prepared 1 day early.

***
