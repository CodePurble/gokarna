# Gokarna

Gokarna is an opinionated theme with a focus on minimalism and simplicity. This
fork allows font modifications by setting the appropriate variables in
`static/css/main.css`

To set the font used in blockquotes, the following variables need to be set:
```css
/* URL can also be a filepath to a downloaded font (put it in static/fonts) */
--fontblockquote-url: "https://fonts.googleapis.com/css2?family=Playfair+Display&display=swap";
/* font family name */
--fontblockquote-family: "Playfair Display";
/* serif/sans-serif */
--fontblockquote-serif: serif;
/* default font weight */
--fontblockquote-weight: 400;
/* default font style */
--fontblockquote-style: italic;
```

To set the font used in the rest of the site, the following variables need to
be set:
```css
/* URL can also be a filepath to a downloaded font (put it in static/fonts) */
--fontmain-url: "https://fonts.googleapis.com/css2?family=Playfair+Display&display=swap";
/* font family name */
--fontmain-family: "Playfair Display";
/* serif/sans-serif */
--fontmain-serif: serif;
/* default font weight */
--fontmain-weight: 400;
/* default font style */
--fontmain-style: normal;
```

To propagate font changes, reload the page using <kbd>Shift</kbd> +
<kbd>Ctrl</kbd> + <kbd>r</kbd>

### Authors:

1. [Yash Mehrotra](https://yashmehrotra.com)
2. [Avijit Gupta](https://twitter.com/526avijit)

### Modified by:

[Ramprakash](https://github.com/CodePurble)

### Demo: [https://gokarna-hugo.netlify.app](https://gokarna-hugo.netlify.app)

## Support the developer

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/avijitgupta)

## Features

- Minimalistic & fast
- Customizable header
- Responsive
- Available in light and dark themes
- Native fonts and support for [feather icons](https://feathericons.com/) and [svg icons](https://gokarna-hugo.netlify.app/posts/theme-documentation-advanced/#icons-on-homepage)
- Syntax highlighting
- SEO Ready
- Table of contents which can be configured per page
- Option to add custom javascript and css
- RSS Feed
- Math typesetting using [Katex](https://gokarna-hugo.netlify.app/posts/theme-documentation-advanced/#katex)

## Screenshots

### Homepage

Light Mode                                                      | Dark Mode
:-------------------------:|:-------------------------:
![Light mode](https://raw.githubusercontent.com/526avijitgupta/gokarna/main/images/screenshot-light-home.png "Light mode") | ![Dark mode](https://raw.githubusercontent.com/526avijitgupta/gokarna/main/images/screenshot-dark-home.png "Dark mode")

### Post page

Light Mode                                                      | Dark Mode
:-------------------------:|:-------------------------:
![Light mode](https://raw.githubusercontent.com/526avijitgupta/gokarna/main/images/screenshot-light-post.png "Light mode") | ![Dark mode](https://raw.githubusercontent.com/526avijitgupta/gokarna/main/images/screenshot-dark-post.png "Dark mode")

### List page

Light Mode                                                      | Dark Mode
:-------------------------:|:-------------------------:
![Light mode](https://raw.githubusercontent.com/526avijitgupta/gokarna/main/images/screenshot-light-list.png "Light mode") | ![Dark mode](https://raw.githubusercontent.com/526avijitgupta/gokarna/main/images/screenshot-dark-list.png "Dark mode")



## Installation

Follow details installation steps in the [documentation here](https://gokarna-hugo.netlify.app/posts/theme-documentation-basics/#installation)

```sh
git submodule add https://github.com/526avijitgupta/gokarna.git themes/gokarna
```

## Customization

For a complete guide on customization, please go through our [basic](https://gokarna-hugo.netlify.app/posts/theme-documentation-basics/) and [advanced](https://gokarna-hugo.netlify.app/posts/theme-documentation-advanced/) theme documentation. A gist of things you can customize:

- Navigation menu
- Avatar image and size
- Accent color
- Theme mode (Auto, Light & Dark)
- Custom HTML in head section for loading any scripts
- Syntax highlighting
- Option to show posts recent or popular homepage.
- Footer

## Inspiration

The theme is inspired by and accordingly named after [Gokarna](https://en.wikipedia.org/wiki/Gokarna,_Karnataka), a small and peaceful beach town on the west coast on India.

![Gokarna](https://raw.githubusercontent.com/526avijitgupta/gokarna/main/images/gokarna.jpg)

## Performance

Google Lighthouse check score: 100%

![Lighthouse Score](https://raw.githubusercontent.com/526avijitgupta/gokarna/main/images/lighthouse.png)

## LICENSE

This code is licensed under [GNU GPLv3](https://www.gnu.org/licenses/gpl-3.0.html)
