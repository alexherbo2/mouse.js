# mouse.js

mouse.js is a JavaScript library to simulate mouse input.

## Installation

Add [`mouse.js`](scripts/mouse.js) to your project.

## Usage

**Example** – Click a link:

``` javascript
Mouse.click(link)
```

**Example** – Open link in new tab:

``` javascript
Mouse.click(link, { ctrlKey: true })
```

**Example** – Hover a video:

``` javascript
Mouse.hover(video)
```

**Example** – Same, but infinite:

``` javascript
const mouse = new Mouse

// Infinite hovering
mouse.hover(video)

// Stop after 10 seconds
setTimeout(() => mouse.unhover(video), 10000)
```

See the [source](scripts/mouse.js) for a complete reference.
