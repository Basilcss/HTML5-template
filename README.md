# HTML5 & Basil.css template

Minimal code example to show how Basil.css works with HTML5.

### in the <head> tag put this line:

```
 <link rel="stylesheet" href="https://unpkg.com/basilcss@latest/basil.css" />
```

### The template

```js
<body>
  <section class="row">
    <img
      class="pic col-8 full-width vh-50 big:col-4 big:vh-100"
      src="https://source.unsplash.com/random"
      alt="lorem"
    />
    <div class="m-b-1 col-8 big:col-4 big:flex-col-justifyCenter-alignCenter">
      <div class="big:w-80">
        <h1 class="m-b-1">Lorem, ipsum dolor.</h1>
        <p class="big:w-80">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora quam
          dolores suscipit neque commodi repellat, deserunt temporibus ducimus
          quidem corporis nobis nihil inventore at officia a recusandae quasi ex
          odit.
        </p>
      </div>
    </div>
  </section>
</body>
```
