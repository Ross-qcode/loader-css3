# CSS3 Loaders
## Find the pure css3 loaders with just some simple line of coding.

### Step:1 -  HTML

Create a `<ul>` element, with a `<li>`. Paste this HTML code.

```html
<ul>
  <li>
    <div class="loader-move"></div>
  </li>
</ul>
```


### Step:2 - CSS

Add the given code to you project in css file.

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

### Step:3 - Save and Run your project.

This is one of the loader code. For complete loader project download the complete project and use, who give you a perfect view to your user.

### Live Demo At Codepen: https://codepen.io/kravisingh/pen/xqaObG
