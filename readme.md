# favfarm.deno.dev

A little website that serves up Favicon emojis.

It works by wrapping an emoji in SVG text like so:

```svg
<svg xmlns='http://www.w3.org/2000/svg' width='48' height='48' viewBox='0 0 16 16'><text x='0' y='14'>😽</text></svg>
```

Handy!

Works like this:

```html
<link rel="icon" href="https://favfarm.deno.dev/💩" />
<link rel="icon" href="https://favfarm.deno.dev/🌶" />
<link rel="icon" href="https://favfarm.deno.dev/🔥" />
<link rel="icon" href="https://favfarm.deno.dev/🥰" />
<link rel="icon" href="https://favfarm.deno.dev/🖥" />
<link rel="icon" href="https://favfarm.deno.dev/👓" />
```

Also works with CSS:

```css
a {
  cursor: url("https://favfarm.deno.dev/🖕") 15 0, auto;
}
```

## Development

run `deno task dev`
