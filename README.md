# Doctor Antelope Space

Table of contents:

1. TOC
{:toc}

## Basic setup

The first line of the file should start with a "*level 1 heading*".

Jekyll requires blog post files to be named according to the following format:

`YYYY-MM-DD-filename.md`

## Basic formatting

You can use *italics*, **bold**, `code font text`, and create [links](https://www.markdownguide.org/cheat-sheet/). Here's a footnote [^1]. Here's a horizontal rule:

---

### Lists

Here's a list:

- item 1
- item 2

And a numbered list:

1. item 1
1. item 2

### Boxes and stuff

> This is a quotation

{% include alert.html text="You can include alert boxes" %}

...and...

{% include info.html text="You can include info boxes" %}

### Images

![](/images/logo.png "fast.ai's logo")

### Code

General preformatted text:

    # Do a thing
    do_thing()

Python code and output:

```python
# Prints '2'
print(1+1)
```

    2

### Tables

| Column 1 | Column 2 |
|-|-|
| A thing | Another thing |

### Footnotes

[^1]: This is the footnote.
