Magic Table
===========

Center element in Vertical and Horizontal

### HTML
```html
<div class="mg-table box-template">
  <div class="mg-cell">
    <div class="mg-text">
      <p>Your Text</p>  
    </div>
  </div>
</div>
```

### CSS

```css
.mg-table{
  display:table;
  text-align:center;

  *position:relative;
  *display:block;
}
.mg-table .mg-cell{
  display: table-cell;
  vertical-align: middle;

  *display:block;
  *position:absolute;
  *top:50%;
}
.mg-table .mg-text{
  *display:block;
  *position:relative;
  *top:-50%;
  *left:-50%;
}
```

Run in old Browser, example IE 7 +