# Short Response Questions

Answer the following questions in your own words. Each response should be 2-4 sentences.

## Question 1: HTML Structure

What is the difference between the `<head>` and `<body>` sections of an HTML document? What kind of content goes in each?

**Your Answer:**

The `<head>` section contains info about the webpage that is not shown directly on the page, such as the title the title the mata data, links to the Css files and font, The `<body>` section contains everything that is visible to the user, like text, images, button, links, and headings.

## Question 2: Semantic HTML

Why should we use semantic elements like `<header>`, `<main>`, and `<footer>` instead of using `<div>` tags for everything?

Semantic elements like `<header>`, `<main>`, and `<footer>` describe the meaning of the content inside them. They make the code easier to read, improve accessibility for screen readers, and help search engines understand the structure of the page. Using semantic elements is better than using <div> for everything because <div> has no meaning on its o

## Question 3: CSS Selectors

Given the following HTML:

```html
<ul>
  <li class="vegetable">Carrots</li>
  <li class="vegetable">Broccoli</li>
  <li class="fruit" id="favorite">Mango</li>
</ul>
```

Write THREE different CSS rules:

1. One that makes ALL list items have a `yellow` background
2. One that makes only the vegetables have `green` text color
3. One that makes only the Mango `bold`

**Your Answer:**

```css
li {
  background-color: yellow;
}

.vegetable {
  color: green;
}

#favorite {
  font-weight: bold;
}
```

## Question 4: The Box Model

In your own words, explain the four parts of the CSS box model (content, padding, border, margin). What is the purpose of each part?

- The `content` is the actual text or image inside an element.
- The `padding` is the space between the content and the border.
- The `border` wraps around the padding and content and can be styled.
- The `margin` is the space outside the border that seperates the element from other elements.

## Question 5: Box-Sizing

What problem does `box-sizing: border-box` solve? Why do we include it in a CSS reset at the top of our CSS files?

`box-sizing: border-box` makes the width and height of an element include padding and border. This prevents elements from becoming larger than expected and makes layouts easier to control. We include it in a CSS reset so sizing is consistent and predictable across the entire age.

## Question 6: Display Property

What is the difference between `display: block`, `display: inline`, and `display: inline-block`? Give an example of when you might use `inline-block`.

`display: block`- takes up the full width and starts on a new line.

`display: inline`- stays in the same line and cannot have width or height set.

`display: inline-block`- stays inline but allows width, height, padding and margin.

you might use `inline-block` for buttons or navigation items that should sit next to eachother but still be styled like blocks.
