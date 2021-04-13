# Blur Serverlist
a snippet that blurs servers for whatever reason

```css
[aria-label="Servers"] {
    filter: blur(4px);
}
```

if you want a version that unblurs on hover, you can grab this one:
```css
[aria-label="Servers"] {
    filter: blur(4px);
    transition: filter .25s ease-in-out;
}

[aria-label="Servers"]:hover {
    filter: none;
    transition: filter .25s ease-in-out;
}
```
