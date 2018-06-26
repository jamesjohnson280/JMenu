# JMenu
A simple responsive CSS Menu library. JMenu requires no Javascript and it's 
easy to customize.

## Usage

### A Simple Menu

1. Add the JMenu stylesheet to the header of your site:
```
<link rel="stylesheet" href="css/jmenu.css">
```

2. Add the basic markup for your menu:

```
<nav class="jmenu">
    <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Categories</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Contact</a></li>
    </ul>
</nav>
```

## Customization

### Typography

JMenu is designed to pick up typographic styles from your website's
stylesheet. By default the menu items will inherit your `body` style. You can 
change them by overriding the `.jmenu` class.

```
.jmenu {
    font: bold 1.125em 'Helvetica', sans-serif;
}
```

To change the color of the menu item links, simply override `.jmenu a` with 
your colors.

```
.jmenu a {
    color: coral;
}

.jmenu a:hover {
    color: red;
}
```

### Menu Bar

To change the style of the menu bar override the background style of the
`.jmenu` class.
``` 
.jmenu {
    background: #ccc; /* Changes menu bar to a light gray */
}
```

