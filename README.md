# Networking Due Diligence

## Simple File Editing Guide

### Before You Start

Open the file in any text editor such as:

- Notepad
- VS Code
- TextEdit

Use the search feature to quickly find text:

| System | Shortcut |
|---|---|
| Windows | `Ctrl + F` |
| Mac | `Command + F` |

---

## 1. Add a Checklist Item

Search for:

```js
items: [
```

Copy an existing item, paste it below, and update the following fields:

- `task`
- `docTask`

---

## 2. Rename a Section

Search for the current section title and replace it.

### Example

```js
title: "Emergency Services"
```

Change to:

```js
title: "Emergency Equipment"
```

---

## 3. Edit Existing Text

Use search to find the wording you want to change and edit it directly.

### Example

```js
task: "Check Pool Gate"
```

Change to:

```js
task: "Inspect Pool Gate"
```

---

## 4. Add a New Section

Copy an existing section block like this:

```js
{
  id: "...",
  icon: "...",
  title: "...",
  items: [...]
}
```

Paste it below another section and update:

- `id`
- `title`
- `items`

---

## Tips

- Keep commas, brackets, and quotation marks in place.
- Save often and make a backup before editing.
- If the file breaks, check for:
  - Missing commas
  - Missing quotation marks
  - Missing brackets

---

## Quick Reference

| Goal | Search For |
|---|---|
| Add checklist item | `items: [` |
| Rename section | Existing title |
| Change wording | Existing text |
| Add new section | `{ id: ..., icon: ..., title: ..., items: [...] }` |
The file is already organized well, so most changes are simply copying existing examples and replacing text.
