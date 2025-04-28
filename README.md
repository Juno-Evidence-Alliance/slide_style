## Custom Reveal.js Styles for Quarto Presentations

This repository contains custom styles for Reveal.js presentations using Quarto. You can easily reuse these styles by cloning this repo and referencing the included CSS file in your own .qmd presentations.

### Files
juno.css: The compiled CSS file for your Reveal.js presentations.

juno-theme.scss: The SCSS source file (for customisation).

README.md: This file explaining how to use the styles.

Demo_of_Juno style.qmd: A demo presentation showcasing the juno.css style.

Demo_of_Juno style.html: The compiled HTML presentation using the juno.css style.

Demo_of_Juno style_files/: A folder containing the compiled assets for the demo presentation.

images/: A folder containing images used in the demo presentation.

## Demo of the slide style

You can find a html demo of the slide style [here](https://juno-evidence-alliance.github.io/slide_style/Demo_of_Juno_style.html#/title-slide)

## How to Use
Option 1: Clone the Repository
Clone this repo to your local machine:

```bash
git clone https://github.com/Juno-Evidence-Alliance/slide_style
```
Reference the juno.css file in your .qmd presentation like this:

```yaml
format:
  revealjs:
    css: juno.css
    slide-number: true
    show-slide-number: all
    logo: images/JUNO_TAGLINE.png
```

Now you can start creating presentations using the custom style!

Option 2: Use the Hosted Version (GitHub Pages)
You can also use the hosted version of the CSS file if you don't want to clone the repo:


```yaml
format:
  revealjs:
    css: https://juno-evidence-alliance.github.io/slide_style/juno.css
    slide-number: true
    show-slide-number: all
    logo: images/JUNO_TAGLINE.png
```

This approach allows you to reference the CSS from anywhere without needing to download it.