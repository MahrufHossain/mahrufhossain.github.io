# Markdown

**Markdown** is a lightweight markup language for creating a formatted text using a plain-text editor, created by **John Gruber** in **2004**. It is widely used for *blogging* and *instant messaging*, and also used elsewhere in *online forums*, *collaborative software*, *documentation pages*, and *readme files*.

**File extension**: `.md` or `.markdown`

## Basic Markdown Syntax

### Headings

There are 6 types of headings in markdown ranging from H1 to H6. The number of `#` symbol before a heading determine its level.

```md
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

#### `Output`

---

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

---
---
---

### Text Formatting

Markdown support various text formatting options such as bold, italic, strike-through and so on.

```md
**Bold text**  
*Italic text*  
~~Strike-through~~  
__Bold using underscores__  
_Italic using underscores_  
`Inline code`
```

#### `Output`

---

**Bold text**  
*Italic text*  
~~Strike-through~~  
__Bold using underscores__  
_Italic using underscores_  
`Inline code`

---
---
---

### Lists

#### Unordered Lists

Unordered lists are created using `*`, `+`, or `-` followed by a whitespace.

```md
- Item1
- Item2
  - SubItem2.1
  - SubItem2.2
- Item3
```

`Output`

---

- Item1
- Item2
  - SubItem2.1
  - SubItem2.2
- Item3

#### Ordered Lists

Ordered lists use numbers (`1`, `2`, `3`) followed by a period (`.`) and a whitespace.

```md
1. Item1
2. Item2
```

`Output`

1. Item1
2. Item2

---
---
---

### Links

Links can be added using `[Placeholder text](link)`.

```md
- [Google](https://www.google.com)
- [Github Profile](https://github.com/username)
```

`Output`

- [Google](https://www.google.com)
- [Github Profile](https://github.com/username)

---
---
---

### Images

Images can be added using `![alt text](path_to_image)`.

```md
![some_programming_languages](https://www.cybher.org/wp-content/uploads/2023/08/top-programming-languages-980x500.jpg)
```

`Output`

![some_programming_languages](https://www.cybher.org/wp-content/uploads/2023/08/top-programming-languages-980x500.jpg)

---
---
---

### Blockquote

Blockquote can be created using `>` at the beginning of a line. They can also span multiple lines.

```md
> This is a blockquote.
> It can span multiple lines.
```

`Output`

> This is a blockquote.
> It can span multiple lines.

---
---
---

### Codeblocks

Codeblocks can be added in two distinct ways.

- Inline Code
- Multiline Code

#### Inline Code

Use single backticks (`) to format inline code.

```md
`print()` function is used in python to print something.
```

`Output`

`print()` function is used in python to print something.

#### Multiline Code

Use triple backticks to (```) to add multiline code. 

```md
Start
```c 

// A simple c program

#include <stdio.h>

int main(int argc, char *argv[]){

  printf("Hello World\n");
  return 0;

} 

``` End

```

For syntax highlighting, specify the language after three backticks(```).

`Output`

```c
// A simple c program

#include <stdio.h>

int main(int argc, char *argv[]){

  printf("Hello World\n");
  return 0;

}
```

---
---
---

## Advanced Markdown Features

### Horizontal Lines

```md
---
```

`Output`

---

### Tables

```md
| Name  | Age | Country  |
|-------|----:|---------|
| Alice |  25 | USA     |
| Bob   |  30 | Canada  |
| Eve   |  22 | Germany |
```

`Output`

| Name  | Age | Country  |
|-------|----:|---------|
| Alice |  25 | USA     |
| Bob   |  30 | Canada  |
| Eve   |  22 | Germany |

---
---
---

### Task lists

```md
- [x] Learn Markdown
- [ ] Write a GitHub README
- [ ] Explore more features

```

`Output`

- [x] Learn Markdown
- [ ] Write a GitHub README
- [ ] Explore more features

---
---
---

## Markdown Extensions

Some platforms support additional features beyond standard markdown.

### Footnotes

```md
Here is a sentence with a footnote[^1].

[^1]: This is the footnote.
```

`Output`

Here is a sentence with a footnote[^1].


