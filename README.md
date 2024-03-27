# Markdown Cheatsheet<a name="TOP"></a>

# Hightlight 
```
This is `mark` text
```
This is `mark` text

## Heading 1 to 6 `#`

```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

# Text_Formatting

## Italic text `_`, `*`
```
This is _Italic_ text or *Italic*
```
This is _Italic_ text or *Italic*

## Strong text `__`, `**`
```
This is __Strong__ text or **Strong**
```
This is __Strong__ text or **Strong**

## Strong & Italic `___`, `***`
```
This is ___Strong & Italic___ text or ***Strong Italic***
```
This is ___Strong & Italic___ text or ***Strong Italic***

## Strickethrough `~~`
```
This is ~~Strikethrough~~ text
```
This is ~~Strikethrough~~ text

## Line Break `<br>`
```
This is one line <br> with this text <br> but result in multiple line
```
This is one line <br> with this text <br> but result in multiple line

# Link `[link-name](path, "title")`

1. [MSK Institute](https://mskinstitute.github.io "Click here for visit website")
2. https://mskinstitute.github.io

# Table `|` or `-`

```
Student Name  | Post
------------- | -------
Sumit  | Manager
Amit  | Developer
```

Student Name  | Post
------------- | -------
Sumit  | Manager
Amit  | Developer

### Show a pipe `|` in a cell using `\` :

```
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content \| 
```
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content \|

## Aligned Table
## Left `:---`, right `---:` and center `:---:`
```
| Left aligned | 
|   :---   | 
| Content  | 
| Content  | 
```
| Left aligned | 
|   :---   | 
| Content  | 
| Content  | 

```
| Right aligned | 
|  ---:   | 
| Content | 
| Content |  
```
| Right aligned | 
|  ---:   | 
| Content | 
| Content | 

```
| Center aligned |
|  :---:  |
| Content |
| Content |
```
| Center aligned |
|  :---:  |
| Content |
| Content |

# List `*`, `-`

~~~md
* Bullet list
    * Nested bullet
        * Sub-nested bullet etc
* Bullet list item 2
~~~

* Bullet list
    * Nested bullet
        * Sub-nested bullet etc
* Bullet list item 2

```md
- Bullet list
    - Nested bullet
        - Sub-nested bullet etc
- Bullet list item 2 
```

~~~md
1. A numbered list
    1. A nested numbered list
    2. Which is numbered
2. Which is numbered
~~~

1. A numbered list
    1. A nested numbered list
    2. Which is numbered
2. Which is numbered


```mmd
- [ ] An uncompleted task
- [x] A completed task
```

- [ ] An uncompleted task
- [x] A completed task

~~~md
- [ ] An uncompleted task
    - [ ] A subtask
~~~

- [ ] An uncompleted task
    - [ ] A subtask


# Horizontal line :
```md
---
```

---

<br>

# Image with alt `![text](image path "title")`:

## Right Image Path ✅
```md
![picture alt](https://mskinstitute.github.io/assets/img/hello.png "Title is optional")
```
![picture alt](https://mskinstitute.github.io/assets/img/hello.png "Title is optional")

## Wrong Image Path ❌
```md
![picture alt](http://via.placeholder.com/200x150 "Title is optional")
```
![picture alt](http:via.placeholder.com/200x150 "Title is optional")

# Foldable Text `<details>` & `<summary>`

```HTML
<details>
  <summary>HTML</summary>
  <p>Content 1 Content 1 Content 1 Content 1 Content 1</p>
</details>

<details style="cursor: pointer">
  <summary>CSS</summary>
  <p>Content 2 Content 2 Content 2 Content 2 Content 2</p>
</details>
```
<details>
  <summary>HTML</summary>
  <p>Content 1 Content 1 Content 1 Content 1 Content 1</p>
</details>

<details style="cursor: pointer">
  <summary>CSS</summary>
  <p>Content 2 Content 2 Content 2 Content 2 Content 2</p>
</details>

<br>

~~~
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Document</title>
</head>
<body>
    <h1>MSK Institute</h1>
</body>
</html>
```

~~~
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Document</title>
</head>
<body>
    <h1>MSK Institute</h1>
</body>
</html>
```

~~~
```css
h1{
    font-size: 50px;
}
```
~~~

```css
h1{
    font-size: 50px;
}
```


# Hotkey (keyboard button) `<kbd>`:

<kbd>⌘ + H</kbd>

<kbd>🪟 + H</kbd>

<kbd>Ctrl + A</kbd> = Select All 

Hotkey list:

| Key | Symbol |
| --- | --- |
| Option | ⌥ |
| Control | ⌃ |
| Command | ⌘ |
| Shift | ⇧ |
| Caps Lock | ⇪ |
| Tab | ⇥ |
| Esc | ⎋ |
| Power | ⌽ |
| Return | ↩ |
| Delete | ⌫ |
| Up | ↑ |
| Down | ↓ |
| Left | ← |
| Right | → |

Emoji:

:exclamation: Use emoji icons to enhance text. :+1:  Look up emoji codes at [here](http://emoji-cheat-sheet.com/)

Markup : Code appears between colons :EMOJICODE:

# Blockquote `>`
```md
> Blockquote
```
> Blockquote

```md
> MSK Institute
>> Best for learn coding & computer course
```
> MSK Institute
>> Best for learn coding & computer course


```md
> Blockquote fksdlkjflkdsjflk skdfjlksd skldjfksdfkjsdd klsjdfslkdjfsnksldfksdm,sddfklsdjf sdnfkn,mvxncm,vnklslfkl kkslkj sdbmnsfb sshkfsdf ksjjflksdjf sdkdfjlksddf Tjdskf lksdjf ksdflks djklsjdf lkjlsdf jkjhkj kjsjdjfks kjkljsdfkj kdfs
>> Nested Blockquote
>>> Blockquote fksdlkjflkdsjflk skdfjlksd skldjfksdfkjsdd klsjdfslkdjfsnksldfksdm,sddfklsdjf sdnfkn,mvxncm,vnklslfkl kkslkj sdbmnsfb sshkfsdf ksjjflksdjf sdkdfjlksddf Tjdskf lksdjf ksdflks djklsjdf lkjlsdf jkjhkj kjsjdjfks kjkljsdfkj kdfs
```
> Blockquote fksdlkjflkdsjflk skdfjlksd skldjfksdfkjsdd klsjdfslkdjfsnksldfksdm,sddfklsdjf sdnfkn,mvxncm,vnklslfkl kkslkj sdbmnsfb sshkfsdf ksjjflksdjf sdkdfjlksddf Tjdskf lksdjf ksdflks djklsjdf lkjlsdf jkjhkj kjsjdjfks kjkljsdfkj kdfs
>> Nested Blockquote
>>> Blockquote fksdlkjflkdsjflk skdfjlksd skldjfksdfkjsdd klsjdfslkdjfsnksldfksdm,sddfklsdjf sdnfkn,mvxncm,vnklslfkl kkslkj sdbmnsfb sshkfsdf ksjjflksdjf sdkdfjlksddf Tjdskf lksdjf ksdflks djklsjdf lkjlsdf jkjhkj kjsjdjfks kjkljsdfkj kdfs
