# Lab8_WE_Git

**Course:** Web Engineering - Laboratory 8
**Topic:** CSS Grid Layouts & Git/GitHub Version Control
**Institution:** UET Taxila

## Project Description

A responsive E-Commerce product gallery web page built with HTML and CSS Grid.

## Features

- Auto-responsive product grid using `repeat(auto-fit, minmax(250px, 1fr))`
- **No media queries**: the layout adapts to any screen width automatically
- Minimum card width of 250px
- Hover animations: card lift with shadow, image zoom, and button colour change
- Clean, readable card design (image, title, description, price, button)

## Files

| File         | Purpose                           |
|--------------|-----------------------------------|
| `index.html` | Page structure and product cards  |
| `style.css`  | Grid layout, styling, animations  |
| `README.md`  | Project documentation             |

## How to Run

1. Clone or download this repository.
2. Open `index.html` in any web browser.
3. Resize the browser window to see the grid reflow automatically.

## Key CSS

```css
.product-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 24px;
}
```

## Tools Used

Visual Studio Code, Git, GitHub
