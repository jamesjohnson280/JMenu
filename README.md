# JMenu
A simple responsive CSS Menu library. JMenu requires no Javascript and it's 
easy to customize.

## Usage

### A Simple Menu

1. Add the JMenu stylesheet to the header of your site:
```html
<link rel="stylesheet" href="css/jmenu.css">
```

2. Add the basic markup for your menu:

```html
<nav class="jmenu">
  <ul>
    <li><a href="#">Home</a></li>
    <li><a href="#">Categories</a></li>
    <li><a href="#">About</a></li>
    <li><a href="#">Contact</a></li>
  </ul>
</nav>
```

### Dropdowns
1. To add a dropdown add the `.jm-dropdown` class to the menu item:
```html
<nav class="jmenu">
  <ul>
    <li><a href="#">Home</a></li>
    <li class="jm-dropdown"><a href="#">Categories</a></li>
    <li><a href="#">About</a></li>
    <li><a href="#">Contact</a></li>
  </ul>
</nav>
```

2. Nest the dropdown list inside of the `li` element after the anchor:
```html
<nav class="jmenu">
  <ul>
    <li><a href="#">Home</a></li>
    <li class="jm-dropdown">
      <a href="#">Categories</a>
      <ul>
        <li><a href="#">Apples</a></li>
        <li><a href="#">Bananas and Pears</a></li>
        <li><a href="#">Oranges</a></li>
      </ul>
    </li>
    <li><a href="#">About</a></li>
    <li><a href="#">Contact</a></li>
  </ul>
</nav>
```

## Customization

### Typography

JMenu is designed to pick up typographic styles from your website's
stylesheet. By default the menu items will inherit the `body` style. You can 
change that by overriding the `.jmenu` class.

```css
.jmenu {
  font: bold 1.125em 'Helvetica', sans-serif;
}
```

To change the color of the menu item links, simply override `.jmenu a` with 
new colors.

```css
.jmenu a {
  color: coral;
}

.jmenu a:hover {
  color: red;
}
```

### Menu Bar

To change the look of the menu bar override the background style of the
`.jmenu` class.
```css 
.jmenu {
  background: #ccc; /* Changes menu bar to a light gray */
}
```

## Compatibility

JMenu has been tested in the following browsers:
* Chrome 67
* Firefox 60
* Safari
* Internet Explorer 10
* Edge 42

