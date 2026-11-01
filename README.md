# Personal Budget & Expense Tracker

A static Budget Tracker page built with plain HTML and CSS (Week 2). It doesn't calculate or respond to clicks yet. JavaScript comes in later weeks.

## Files

- index.html: the page structure
- style.css: the styling
- logo.svg: the coin logo next to the heading

## What I built

### 1. Expense table
A table with a header row (`<thead>`, `<th>`) and 5 sample rows (`<tbody>`, `<td>`). It is styled with `border-collapse`, cell padding, a colored header, and alternating row colors using `tr:nth-child(even)`.

### 2. Upgraded Add Expense form
The inputs are inside a `<form>`. Category is a `<select>` dropdown with 5 options (Food, Transport, Rent, Entertainment, Other). Every input has a unique `id` and a `<label>` linked with a matching `for` attribute. The "Add Expense" button uses `type="button"` and does nothing yet.

### 3. Multimedia
- An `<img>` logo with `src`, `alt`, `width` and `height`.
- A YouTube budgeting video in an `<iframe>` with `width`, `height`, `title` and `frameborder`.

### 4. Interactive elements
- A collapsible "How to use this tracker" section using `<details>` and `<summary>`.
- A `:hover` style on table rows.
- `cursor: pointer` on the button.

### 5. Advanced CSS selectors
- Descendant selector: `#your-expenses td`
- Direct child selector: `#expense-form > input`
- Position-based pseudo-class: `tr:nth-child(even)`
- Negation pseudo-class: `input:not([type="submit"])`
- Focus state: `input:focus`