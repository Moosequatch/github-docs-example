## github-docs-example

[Jump to references](#references)

# GFM - Useful Quick References

## Code Blocks

Codeblocks are best marked by using the **back tick (```)** or **tilde (~~~)**, at the head and foot of the code block. Language used can be tagged in line with the header.

``` python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Example usage:
number = 5
result = factorial(number)
print(f"The factorial of {number} is {result}")

```

## Formatting

### HTML

HTML can be used to:

* Format
* Insert images

This:
``` html
<img width=300px src="https://github.com/Moosequatch/github-docs-example/blob/main/Screenshot%202023-09-23%20134842.png?raw=true">
```

Produces This:

<img width=300px src="https://github.com/Moosequatch/github-docs-example/blob/main/Screenshot%202023-09-23%20134842.png?raw=true">

HTML can be used for workarounds such as image resizing.

### Formatting, Quoting and Emojis

|Format                  |GFM Code                  |
|------------------------|--------------------------|
|       **Bold**         |       `**Bold**`         |
|       *Italics*        |       `*Italics*`        |
|  ***Bold + Italics***  |  `***Bold + Italics***`  |
|   ~~Strikethrough~~    |   `~~Strikethrough~~`    |
|  <sub>Subscript</sub>  |  `<sub>Subscript</sub>`  |
| <sup>Superscript</sup> | `<sup>Superscript</sup>` |
|   Smile Emoji :smile:  |  `Smile Emoji :smile:`   |

Text can be quoted by using `>` at the start of the line.
>Text can be quoted by using `>` at the start of the line.

```>Text can be quoted by using `>` at the start of the line.```

## References

[Basic Writing and Formatting Doc](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

[Official GFM Documentation](https://github.github.com/gfm/)

