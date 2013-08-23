Magic Table
===========

Magic Table is a simple CSS framework that allows you to center 
an element both vertically and horizontally, without the need to use a real table 
(thus the 'Magic Table' name) or the line-height trick.

### HTML
```html
<div class="mg-table">
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
  /* IE 7 */
  *position:relative;
  *display:block;
}
.mg-table .mg-cell{
  display: table-cell;
  vertical-align: middle;
  /* IE 7 */
  *display:block;
  *position:absolute;
  *top:50%;
}
.mg-table .mg-text{
  /* IE 7 */
  *display:block;
  *position:relative;
  *top:-50%;
  *left:-50%;
}
```

[Demo](http://gmoura.com.br/magic-table/)

Magic Table is compatible with all modern browsers and IE7+