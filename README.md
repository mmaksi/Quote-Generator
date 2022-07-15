## Demo ⚡
I have memorized tons upon tons of quotes from my extensive readings in philosophy over the years, so I decided to create this simple web app that generates a random quote from an API. You have the option to generate a new quote or share the quote you like with your social network on Twitter. [Enjoy!](https://markmaksi74.github.io/quote-generator/)

![quote-generator](https://i.ibb.co/Bw4tHD9/quotes-generator.jpg)

## Features 🥁
- Random Quotes [API](https://type.fit/api/quotes)
- [Loader](https://www.w3schools.com/howto/howto_css_loader.asp) for initial load created by w3schools
- Choose [vector background](https://heropatterns.com/)

## Techniques 🛠
- API `fetch()` and `async await` function

## Lessons Learned 📚
### CSS
- `:focus` controls when the element is currently targeted by the keyboard (tab), or activated by the mouse

- `:active` while clicking on the button

- [The Difference between :focus and :active](https://stackoverflow.com/questions/1677990/what-is-the-difference-between-focus-and-active)

- `width: auto;` means the value is adjusted automatically according to the content

- `justify-content: center` centers the children horizontally

- `align-items: center;` centers the children vertically

- `text-align` is used to align the inner content of `block` elements: body, div, p, header, section, main, form, li, ol, ul, nav

- `box-shadow` offset-x | offset-y | blur-radius | spread-radius | color

- We use `rem` for responsive design because the user might change the font size of html element

- Target Tablet screens or smaller: `@media screen and (max-width: 1000px) {}`

- Create an interactive button:
```
button:hover {
  filter: brightness(110%);
}
```
