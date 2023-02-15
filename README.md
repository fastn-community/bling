# Bling is a collection of `FTD` components

> Bling is for making most content pages more interesting. Normally content pages, like a blog post, or news article etc, only have headings, single quote, image and code block. With bling we are trying to create rich variety of components to spice up such blog posts.

`fifthtry.github.io/bling` is a `ftd` component library which contains various `ftd` 
componets can be used on your pages. 

To use this `ftd` library on your web package, add below lines into `FASTN.ftd` file:
```ftd
\-- fastn.dependency: fifthtry.github.io/bling
\-- fastn.auto-import: fifthtry.github.io/bling/badge
```

In above example `badge` is being added to your package. Which can be called into your `.ftd` files as given below:

```ftd
\-- badge.badge: Primary
primary: true
```
