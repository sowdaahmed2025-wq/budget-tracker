# Budget Tracker: Visual Design

This project is a Budget Tracker web page. This week I improved its visual design using CSS only. No new functionality was added, and the only HTML change was a `<header>` wrapper around the logo, title, and tagline so the page heading could appear as a card.

## Files

- `index.html`: the page structure
- `style.css`: all the styling
- `logo.svg`: the logo
- `README.md`: this file

## Color palette

The colors are stored as CSS variables in `:root` at the top of `style.css`, so the same colors are used consistently across the page.

| Variable | Color | Used for |
|---|---|---|
| `--primary` | #27ae60 | Buttons, input focus border |
| `--primary-dark` | #1e8449 | Button hover |
| `--heading` | #2c3e50 | Headings, table header |
| `--background` | #f4f4f9 | Page background |
| `--card` | #ffffff | Card and input backgrounds |
| `--text` | #333333 | Body text |
| `--border` | #dfe3e8 | Borders on cards, inputs, and table cells |
| `--row-alt` | #eef7f1 | Alternating table rows, input focus background |

## Typography

Fonts come from Google Fonts and are linked in the `<head>` of `index.html`.

- **Poppins** is used for headings (h1, h2, h3).
- **Inter** is used for body text.
- Inputs, labels, buttons, and table cells use `font-family: inherit` so they match the rest of the page.

The pairing gives a clear visual hierarchy: a bold, rounded heading font with a clean, readable body font.

## Table and form styling

**Expense table**
- Navy header row with white text
- Padding inside every cell
- Light borders for structure
- Light green alternating rows to make rows easier to follow
- Hover color on rows

**Add Expense form**
- Inputs and the category dropdown have padding, a light border, and rounded corners
- A green border and light green background appear when an input is focused
- The Add Expense button is green with rounded corners and darkens on hover

## CSS Box Model

- **Margin** separates the cards from each other.
- **Padding** creates space inside each card.
- **Border** defines the edge of each card.
- **Border-radius** (8px on cards, 6px on inputs and buttons) gives a softer, modern look.
- `box-sizing: border-box` is applied to all elements so widths stay predictable.

The page heading, the Add Expense form, and the Expense table each appear as a separate white card on a light gray background.