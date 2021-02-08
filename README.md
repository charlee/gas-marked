gas-marked
===============


This project is a GAS (Google Apps Script) version of the [markedjs/marked](https://github.com/markedjs/marked) library.

## How to use

In your Apps Script editor, find the **Libraries** panel in the left side bar.
Click the "+" button to show the **Add a Library** dialog.

Search script id `1fzttWGjmX33TjG8oMBCRmUb-8FkMeDA4imuLPf6c8yi49aKJD5c-93iP` and click **Look up**.
After the library is found, set **Version** to the greatest number (currently `2`),
and give it an **Identifier** (or use default `marked`). Click **Add**.

Then you should be able to call this library with the following code:

```
var markdown = '**bold** `code`';
var html = marked.marked(markdown);
console.log(html);

// output:
// <p><strong>bold</strong> <code>code</code></p>
```

## Versions

The deployment versions and the library versions are mapped as below.

| Gooogle Apps Script Library deployment verison | marked version |
|------------------------------------------------|----------------|
|                                              2 |   marked@1.2.9 |

