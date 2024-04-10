# Corso Website

Bootstrap website for training courses, workshops, seminars, etc. It has a mixed design with both light and dark colors and a modern look.

<img src="./images/screen.png" />

## Features

- Modern layout with custom colors/styles/backgrounds
- Responsive design
- Sticky navbar with style changes on scroll
- Carousel image slider
- Register & email subscribe forms
- Font Awesome icons

## Usage

This website is built with [Bootstrap](https://getbootstrap.com/) and [Sass](https://sass-lang.com/). It uses [Font Awesome](https://fontawesome.com/) for icons.

In order to customize this website, you need to install [Node.js](https://nodejs.org/en/). Then, clone this repository and run:

```bash
npm install
```

This will install Bootstrap, Sass and Font Awesome. To build your CSS files from Sass, run:

```bash
npm run sass:build
```

To watch your Sass files for changes, run:

```bash
npm run sass:watch
```

You can add Bootstrap variables to the `bootstrap.scss` file. You can look at the file `node_modules/bootstrap/dist/scss/_variables.scss` for a list of all the variables. Do NOT edit the `variables.scss` file directly, as it will be overwritten when you update Bootstrap.

To add your own custom styles, use the `styles.scss` file.

## "Why this project?" and a long advice

Welcome to my cozy online corner, created for the sheer joy of learning and sharpening our skills. Take a peek at [my GitHub profile](https://github.com/edg96), and you'll find projects that highlight my journey with [Python](https://www.python.org/) and [CustomTkinter](https://github.com/TomSchimansky/CustomTkinter).

[Bootstrap](https://getbootstrap.com/) is our hero for those eager to launch a website decked with ready-to-use components straight off the shelf, simplifying the front-end development process significantly. It's the go-to for getting your digital creation up and running with minimal fuss.

Yet, if you are all about putting a personal stamp on things, I wholeheartedly recommend diving into the realms of [HTML](https://www.w3schools.com/html/), [CSS](https://www.w3schools.com/css/), and [JavaScript](https://www.w3schools.com/js/). These tools are your keys to the kingdom of front-end development, unlocking endless possibilities for customization. While Bootstrap offers flexibility, allowing for some customization with SASS to dial down its distinctive look, its essence might still peek through in your project's overall flair.

And here's a little extra advice: take a moment to explore [Tailwind](https://tailwindcss.com/). I view it as Bootstrap's sprightlier sibling, offering an even broader canvas for personalizing your front-end aesthetic. It's definitely worth exploring for those who relish the idea of marrying convenience with creativity.

So, whether you're here to explore, learn, or forge something that's unmistakably yours, remember: the path to personalization isn't just about the end product but the rich experiences and growth you'll encounter along the way.
