# loader-css3
## Find the pure css3 loader with just some simple line of coding.

### HTML

Create a `<ul>` element, with a `<li>`. Paste this HTML code.

```html
<ul>
  <li>
    <div class="loader-move"></div>
  </li>
</ul>
```



### Css
```css
.loader-move {
  display: inline-block;
  background: #ad0c91;
  border-radius: 50%;  
  width: 100px;
  height: 100px;
  -webkit-animation: move 1s ease infinite;
  animation: move 1s ease infinite;
}
@-webkit-keyframes move {
  0% { transform: rotate(0deg);}
  50% { transform: rotate(50deg); border-radius: 0%;}
  100%{ transform: rotate(100deg); border-radius: 50%;}
}

@keyframes move {
  0% { transform: rotate(0deg);}
  50% { transform: rotate(50deg); border-radius: 0%;}
  100%{ transform: rotate(100deg); border-radius: 50%;}
}

```

### And you have done.
