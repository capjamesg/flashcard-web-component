# flashcard-web-component

A HTML web component for displaying flashcards on a web page.

This component is ideal for providing an on-page aid that a reader can use to practice material they have read on a web page.

## Demo

[Try the component](https://capjamesg.github.io/flashcard-web-component/).

Here is an example of the component in use:

https://github.com/capjamesg/flashcard-web-component/assets/37276661/e4f0d2e3-5d48-42f5-abd8-805ea4a80e1f

## Setup

To use this component, first clone this repository:

```
git clone https://github.com/capjamesg/flashcard-web-component
cd flashcard-web-component/
```

Copy the `flashcard.js` file onto your own website.

Add the following code to the web page where you want to use the component. Place the following code before the place where you you want to use the component:

```html
<script src="./path/to/flashcard.js"></script>
```

You can then add the component to the page. To do so, add the following code:

```html
<flashcards-element>
    <flashcard question="What are microformats?" answer="microformats is a method to structure information on web pages with HTML. You can use microformats to mark up personal profiles, content, and more."></flashcard>
    <flashcard question="What is h-entry used for?" answer="h-entry is used to mark up content on the web (i.e. blog posts, reviews). h-entry can be used with attributes like u-like-of to indicate the content is a reaction to another piece of content on the web."></flashcard>
</flashcards-element>
```

Use the `flashcards-element` element to create the parent element. Use `flashcard` to specify your flashcards.

Each `<flashcard>` needs a `question` and an `answer` attribute.

## License

This project is licensed under an [MIT license](LICENSE).
