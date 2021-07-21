# boost.css
Predefined selectors library.

**IDEA:**

Using Boost CSS allow you to write style declarations succinctly.

**USAGE:**

`Boost attribute declaration:`

Classic code:

```html
<span style="display: none"></span>
```

with boost.css:

```html
<span :display="none"></span>
```
 
`Boost class declaration:`

Classic code:

```html
<span class="foo" style="width: 100px !important"></span>
```

with boost.css:

```html
<span class="foo width:100!"></span>
or
<span class="foo" :width="100!"></span>
```

**OUTRO:**

boost.css contains limited definitions of predefined selectors, so you can add own selectors for your web project if need for future usage.
