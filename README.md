# Bling a collection of `FTD` components
`fifthtry.github.io/bling` is a component library which contains various `ftd` 
componets can be used on your pages. 

To use this `ftd` library on your web package, add below lines into `FPM.ftd` file:
```ftd
-- fpm.dependency: fifthtry.github.io/bling
-- fpm.auto-import: fifthtry.github.io/bling/badge
```

In above example `badge` is being added to your package. Which can be called into your `.ftd` files as given below:

```ftd
-- badge.badge: Primary
primary: true
```
