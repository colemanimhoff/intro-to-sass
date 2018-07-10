##How to install SASS

[Install SASS](https://sass-lang.com/install)

Despite what tutorials tell you, DO NOT use the sudo commands when installing SASS!


    1. Create a new project directory.
    2. Navigate into that directory.
    3. Install SASS with the via command line with `npm install --save-dev node-sass`.
    4. Initialize a new package manager json file with the command `npm init -y`.
    5. Open the json file in your text editor and add two more scripts: `"build:sass": "node-sass <input> <output>"` and `"build:sass:watch": "<input> <output>"`. Refer to the sass project file in the repo for a reference.
    6. Via the command line, enter `npm run build:sass` to build your files.
    7. Via the command line, enter `npm run build:sass:watch`. SASS will watch for changes made in your input files and compile them to your output files.
    
    8. Via the command line, open a new tab, and run `http-server` or `lite-server`.


##Getting Started

    1. Link your <output>.CSS file to your html.file(s). If you are using multiple <input> files, use the `@import` property on your main <imput> file. Use this tutorial as a reference [https://www.youtube.com/watch?v=GI1BhlDtoUs&t=3s](#)
    2. Enter your styles in your SASS or SCSS file. When you save your file, look at the <output>.css file to see your SASS/SCSS compiled!
    3. Open up your project to see your changes!

##SASS Documents and Articles
- Hampton Catlin - 
[Hampton Catlin](http://hamptoncatlin.com/)

- Lighting Talk Slides -
[Lighting Talk Slides](https://docs.google.com/presentation/d/15-HS_Ek4_XJo7qa5cZMzrz27J4_V-BT3oDEytiqZ8AM/edit?usp=sharing)

- SASS Wiki -
[SASS Wiki](https://en.wikipedia.org/wiki/Sass_(stylesheet_language))

- SASS Docs -

[Sass Docs](https://sass-lang.com/)

- SASS vs SCSS

[SASS vs SCSS](http://www.thesassway.com/editorial/sass-vs-scss-which-syntax-is-better)

- SMACSS (Scalable and Modular Architecture for CSS)

[Scalable and Modular Architecture for CSS](https://smacss.com/)

- SASS BASICS
[SASS Basics](https://sass-lang.com/guide)

##Tutorials

Brad Hussey

    A really good series of tutorial vidoes usings SASS syntax (skip the first video (bloopers))

[Tutorial Videos](https://www.youtube.com/watch?v=aFWhf2wjJYo&list=PLUoqTnNH-2XxOt7UsKlTqbfrA2ucGosCR)

Dev Tips

    Overview of how to use SASS, SCSS vs SASS syntax, how to control CSS output, and preprocessors

[Tutorial Videos](https://www.youtube.com/watch?v=1XmUUa_pWw8&list=PLqGj3iMvMa4LE0uTAwo9wIFQYuGhIu7Gw)

Derek Banas

    A tutorial using SCSS syntax

[Tutorial Videos](#https://www.youtube.com/watch?v=wz3kElLbEHE)

Help People

[Help People](https://www.youtube.com/watch?v=P1G4_zxOxtk&t=17s)