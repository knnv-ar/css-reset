# CSS resets

## CSS reset 2024-ene-05 (KP)

https://youtu.be/cCAtD_BAHNw?si=nvzKi3t_lvjfW1ej

```css
/* makes sizing simpler cos include padding and border in size calculation */
*,
*::before,
*::after {
  box-sizing: border-box;
}

/* remove default spacing */
/* force styling of type through styling, rather than elements */
* {
  margin: 0;
  padding: 0;
  font: inherit;
}

/* dark mode user-agent-styles */
/* improves punctuation in supported browsers */
html {
  color-scheme: dark light;
  hanging-punctuation: first last;
}

/* min body height */
body {
  min-height: 100svh;
}

/* responsive images/videos */
img,
picture,
svg,
video {
  display: block;
  max-width: 100%;
}

/* Improved heading in supported browsers */
h1,
h2,
h3,
h4,
h5,
h6 {
  text-wrap: balance;
}

/* improve readability with max-width on paragraphs and lists */
/* prevent orphans in supported browsers */
p,
li {
  max-width: var(--p-max-width, 65ch);
  text-wrap: pretty;
}
```

## img reset 2023-nov-07 (KP)

https://youtu.be/345V2MU3E_w?si=jfwzqX3snLamucSq

```css
img {
  max-width: 100%;
  height: auto;
  vertical-align: middle; /* reemplazo de 'display:block;' */
  font-style: italic;
  background-repeat: no-repeat;
  background-size: cover;
  shape-margin: 1rem;
}
```

## CSS reset 2024-ene-15 (midudev)

```css
/* CSS reset 2024 */
* {
  box-sizing: border-box;
  min-width: 0;
}

body {
  min-height: 100dvh;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  text-wrap: balance;
  ;
}

p {
  text-wrap: pretty;
}
```

## CSS full reset 2022-nov-30 (KP)

https://www.youtube.com/shorts/2lyDv0wOQuQ

```css
/* makes sizing simpler */
*,
*::before,
*::after {
  box-sizing: border-box;
}

/* remove default spacing */
/* force styling of type through styling, rather than elements */
* {
  margin: 0;
  padding: 0;
  font: inherit;
}

/* dark mode user-agent-styles */
html {
  color-scheme: dark light;
}

/* min body height */
body {
  min-height: 100vh;
}

/* responsive images/videos */
img,
picture,
svg,
video {
  display: block;
  max-width: 100%;
}
```

## CSS minimal reset 2022-nov-30 (KP)

https://www.youtube.com/shorts/2lyDv0wOQuQ

```css
/* makes sizing simpler */
*,
*::before,
*::after {
  box-sizing: border-box;
}

/* responsive images/videos */
img,
picture,
svg,
video {
  display: block;
  max-width: 100%;
}

/* same font in form elements */
input, textarea, button, select {
  font: inhertit;
}
```

A better image reset for your CSS