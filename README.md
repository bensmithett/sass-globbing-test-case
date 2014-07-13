This works:

```
sass -r sass-globbing test1.sass:test1_compiled.css
```

This doesn't:

```
sass -r sass-globbing stylesheets/test2.sass:test2_compiled.css
```
