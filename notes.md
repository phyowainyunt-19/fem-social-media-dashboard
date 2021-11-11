# Functional requirements and notes

## Requirements

- Light/Dark mode toggle -- takes system pref by default, but can 
override by toggle

- Html
(https://scottaohara.github.io/a11y_styled_form_controls/)

- Use fieldset, legend, radio input

- Switching between light and dark mode via JS and 
prefer color-scheme(media query)
(https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-color-scheme)


- Three options toggle: light/dark/system 
(https://codepen.io/renddrew/pen/bRomab)

- CSS variables
(https://css-tricks.com/updating-a-css-variable-with-javascript/)

- Accessibility
Heading tags
Screenreader-only text for card titles/username    
(https://www.accessibility-developer-guide.com/examples/hiding-elements/)

### A single card

- BEM (Block Element Modifier)
- Block(Card)
- Element(icon, platform, count, change)
- Modifier(Fb,Twitter)

- Card
- Card_platform
- Card_icon
- Card_icon--facebook
- Card_username

- Card_count
- Card_count(big or small)
- Card_label

- Card_change
- Card_change(increase or decrease)
