---
title: 'CSS'
updatedAt: '2021-05-09 19:39:02'
published: true
---

# CSS

## Snippets

### Align items vertically

```css
.flex {
  display: flex;
  align-items: center;
}
```

To push an element to the right – for example in a navigation – use:

```css
.pushed {
  margin-left: 0;
}
```

### Sticky element

```css
.sticky {
  position: sticky;
  top: 0;
}
```

### Line clamp

```css
.line-clamp {
  overflow: hidden;
  text-overflow: ellipsis;
  display: -webkit-box;
  -webkit-line-clamp: 3;
  -webkit-box-orient: vertical;
}
```

### Make grid rows of equal height

```css
.grid {
  display: grid;
  grid-auto-rows: 1fr;
}
```
