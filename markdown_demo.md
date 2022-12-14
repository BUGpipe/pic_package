# [COMPSCI235] Markdown Demo

## Extension

Markdown files are raw text file with a `.md` extension.
You can find them in every GitHub repository.

## Headings

Use the number sign (Hash tag) "#" for headings. From 1, up to 6 "#".

```
# This is Heading 1
## This is Heading 2
### This is Heading 3
###### This is the smallest Heading which you probably never need
```

## Bold and Italic

- Double asterisk `**<text>**` for **Bold**;
- Single asterisk `*<text>*` for *Italic*;
- Triple asterisk `***<text>***` for ***Bold and Italic***;

## List

A line starts with a dash sign `-`:

```
- Item one
- Item two
- Item three
```

- Item one
- Item two
- Item three

## Ordered List

A line starts with `1.`:

```
1. Item one
1. Item two
1. Item three
```

1. Item one
1. Item two
1. Item three

### Include code in the text

- Inline code surround with backtick E.g. `number = 4`.
- Add a code block using triple backticks;

```python
# This is a code block

if __name__ == "__main__":
    print('Hello world!')
```

## Link

[Here](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) is the Markdown quick start guide from GitHub.

```
[Here](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) is the Markdown quick start guide from GitHub.
```

## Image

Similar to an URL but with an exclamation mark at the front.

![This is an image](resources/the-university-of-auckland-logo-svg-vector.png)

```
![This is an image](resources/the-university-of-auckland-logo-svg-vector.svg)
```

## How to render a Markdown file

- Both VS Code and PyCharm can render markdown pages.
- You can directly view rendered Markdown page from GitHub.
- Use the "Markdown PDF" extension from VS code or an online tool to convert Markdown to PDF.
