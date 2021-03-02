# Making a Personal Website

We are going to code up a personal website, largely from scratch. On this website I would like to include:

- a CV (eventually web-based)
- links to my social media accounts (make sure I have nothing to hide)
- writing about things I learn
- web-based projects (can I link to other GitHub projects?)

For this, I will use a mixture of HTML, SCSS, and other things?

## Sass
To compile all `.scss` files in a `sass` folder to a `.css` based folder called `stylesheets`, use:
> `sass --watch sass/:stylesheets`

One can import a Sass file, say `fonts.scss` into another Sass file using:
> `@use 'fonts';`

To create a variable, use `$`. For instance, to define a default font name, use:
> `$default: Helvetica, sans-serif` 

## Ideas 

- Similarly, give the user the option to have a *maximalist* or *minimalist* experience
- Sort out smartphone compatibility (especially, how will 'margin-notes work' - links with pop up info)
- Learn how to reuse blocks of code
- Figure out how to sort writings (maybe they are all just links to other places?)
- Add music!
- Sticky nav bar 
- website icon 
