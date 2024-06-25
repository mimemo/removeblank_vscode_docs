# RemoveBlank for vscode

![icon](images/icon.png)
Continuous blank lines are deleted when saving the document.

## How to use

- install.

- It is executed automatically when saving.

---

## Behavior

```
- Replace continuous blank lines with selected type.

- from: (^(?([^\r\n])\s)*\r?\n){2,}
- to : document.eol ( or \r\n or \n or \r)

on save.

```
---

## Settings

change [replace to] type at setting panel.

Options include:

- "EOL" (default) : same as document. 
- "\r\n" 
- "\n"
- "\r"

---

## Change Log

### 1.0.0

Initial release.

---

## links

Visual Studio Marketplace

🔗 [RemoveBlank for Visual Studio](https://marketplace.visualstudio.com/items?itemName=ChisatoK.RemoveBlank3)

