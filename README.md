# Heading

```md
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

Hasil:

# H1

## H2

### H3

---

# Paragraf

Cukup tulis teks biasa.

```md
Ini paragraf pertama.

Ini paragraf kedua.
```

---

# Bold / Tebal

```md
**bold**
__bold__
```

Hasil:
**bold**

---

# Italic / Miring

```md
*italic*
_italic_
```

Hasil:
*italic*

---

# Bold + Italic

```md
***bold italic***
```

Hasil:
***bold italic***

---

# Strikethrough / Coret

```md
~~text~~
```

Hasil:
~~text~~

---

# Blockquote

```md
> quote
>> nested quote
```

Hasil:

> quote
>
> > nested quote

---

# List Unordered

```md
- item
* item
+ item
```

Hasil:

* item
* item
* item

---

# List Ordered

```md
1. item
2. item
3. item
```

Hasil:

1. item
2. item
3. item

---

# Checklist / Task List

```md
- [ ] belum
- [x] selesai
```

Hasil:

* [ ] belum
* [x] selesai

---

# Inline Code

```md
`code`
```

Hasil:

`code`

---

# Code Block

<pre>
```python
print("hello")
```
</pre>

Hasil:

```python
print("hello")
```

---

# Horizontal Line / Divider

```md
---
***
___
```

Hasil:

---

# Link

```md
[Google](https://google.com)
```

Hasil:

[Google](https://google.com)

---

# Image

```md
![alt text](image.png)
```

---

# Table

```md
| Nama | Umur |
|------|------|
| Rio  | 20   |
```

Hasil:

| Nama | Umur |
| ---- | ---- |
| Rio  | 20   |

---

# Escaping Character

Buat nampilin simbol markdown sebagai teks biasa.

```md
\# bukan heading
\* bukan italic
```

Hasil:

# bukan heading

---

# Nested List

```md
- item
  - sub item
    - sub sub
```

---

# HTML di Markdown

Markdown support HTML.

```md
<b>bold</b>
<br>
<hr>
```

---

# Footnote

```md
ini teks[^1]

[^1]: isi footnote
```

---

# Highlight

Tidak semua parser support.

```md
==highlight==
```

---

# Superscript

```md
x^2^
```

---

# Subscript

```md
H~2~O
```

---

# Collapsible / Details

GitHub support.

```md
<details>
<summary>Klik</summary>

Isi tersembunyi

</details>
```

---

# Emoji

```md
:smile:
```

Hasil:
😄

---

# Heading ID (beberapa parser)

```md
## Judul {#custom-id}
```

---

# Mermaid Diagram

GitHub & beberapa editor support.

<pre>
```mermaid
graph TD
A --> B
```
</pre>

---

# Math Formula (LaTeX)

```md
$$
E = mc^2
$$
```

Inline:

```md
$E=mc^2$
```

---

# Callout (Obsidian/GitHub tertentu)

```md
> [!NOTE]
> Ini note
```

---

# YAML Frontmatter

Biasanya buat static site/blog.

```md
---
title: Artikel
date: 2026-05-07
tags: [markdown]
---
```

---

# Ringkasan Prefix Penting

| Prefix      | Fungsi        |       |
| ----------- | ------------- | ----- |
| `#`         | Heading       |       |
| `>`         | Quote         |       |
| `-` `*` `+` | List          |       |
| `1.`        | Ordered list  |       |
| `- [ ]`     | Checklist     |       |
| `` ` ``     | Inline code   |       |
| `````       | Code block    |       |
| `---`       | Divider       |       |
| `[]()`      | Link          |       |
| `![]()`     | Image         |       |
| `           | `             | Table |
| `~~`        | Strikethrough |       |
| `**`        | Bold          |       |
| `*`         | Italic        |       |
