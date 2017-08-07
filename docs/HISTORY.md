# checktree History

### 1.2.0 - 2017-Aug-07

* Changed `autoOpen` to support both a boolean value and an unsigned integer number.
* Updated documentation to show how to use unsigned integer with `autoOpen`.

---
 
### 1.1.1

* Added History.md
* Broke the API into its own file [API.md](API.md).
* Changed name of uncompressed file to `checktree-raw.html`
* Added compressed version of file as `checktree.html`
* Added `isChecked` and `setChecked` methods. (Thanks to [Adam](https://github.com/zvakanaka) for the suggestion)

---

### 1.1.0

* Added ability to `autoOpen` a branch while adding.
* Added `changeLabel` functionality.
* Prevent failure of a `document fragment`

---

### 1.0.3 - Fixed 1.0.2

* Same features as 1.0.2
* Fixed a `this` pointer bug.

---

### 1.0.2 - Broken build

* Added 'Partial' state for parent checkboxes when some, but not all, of their children are checked.

---

### 1.0.1

* Minor Doc improvements.
* Removed the value attribute for the `<input>` tags

---

### 1.0.0

* Initial release with basic functionality.
* Ability to show a tree if checked items and ability to know when to load children for a specific node.
