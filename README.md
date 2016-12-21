# jnthb_grid
A simple responsive CSS grid

##Grid

Grid uses twelve columns.

```html
<div class="__container">
  <div class="__md-row">
    <div class="__col-8">
      This is a column that spans 2/3 of the container.  It collapses at medium breakpoint.
    </div>
    <div class="__col-4">
      This column spans 1/3 of the container.
    </div>
  </div>
</div>
```

Breakpoints are defined in the rows.

```html
<div class="__container">
  <div class="__lg-row">
    <div class="__col-12">
      Large Row.
    </div>
  </div>
</div>

<div class="__container">
  <div class="__sm-row">
    <div class="__col-12">
      Small Row.
    </div>
  </div>
</div>
```
You can use offsets:

```html
<div class="__container">
  <div class="__lg-row">
    <div class="__col-4 __offset-2">
      Large Column 4, Offset 2
    </div>
  </div>
  <div class="__md-row">
    <div class="__col-4 __offset-4">
      Medium Column 4, Offset 4
    </div>
  </div>
  <div class="__sm-row">
    <div class="__col-4 __offset-6">
      Small Column 4, Offset 6
    </div>
  </div>
</div>
```

Use `.__full-container` for full width container.

##Buttons

There's one style of buttons, just for a starting point.

```html
<a href="#" class="button">Button</a>
```

##Forms

Wrap inputs and labels in a container with class `__form-control-container` to use form styles.

```html
<form>
  <div class="__form-control-container">
    <label for="inputText">Text</label>
    <input type="text" id="inputText">
  </div>
  <div class="__form-control-container">
    <label for="inputNumber">Number</label>
    <input type="number" id="inputNumber">
  </div>
  <div class="__form-control-container">
    <label for="textArea">Textarea</label>
    <textarea id="textArea"></textarea>
  </div>
  <div class="__form-control-container">
    <label for="inputSelect">Select</label>
    <select id="inputSelect">
      <option>Item 1</option>
      <option>Item 2</option>
      <option>Item 3</option>
    </select>
  </div>  
  <div class="__form-control-container">
    <input type="checkbox" id="checkbox">
    <label for="checkbox">Basic Checkbox</label>
  </div>
  <div class="__form-control-container">
    <input type="radio" name="rad" id="rad1">
    <label for="rad1">Basic Radio</label> 
  </div>
  <div class="__form-control-container">
    <input type="radio" name="rad" id="rad2">
    <label for="rad2">Basic Radio</label> 
  </div>
  <div class="__form-control-container">
    <input type="radio" name="rad" id="rad3">
    <label for="rad3">Basic Radio</label> 
  </div>
</form>
```

##Utility Classes

Utility classes include `.text-center`, `.flex-center`, `.block-center`, `.img-responsive`, `.pull-left` and `.pull-right`.
