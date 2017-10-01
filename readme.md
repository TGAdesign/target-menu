
# Creative menu / navigation made with :target 
This is a creative menu made only with css3, no javascript

Example : [Target Menu](http://tgadesign.ro/github/target-menu/)

The menu is very easy to install and its compatible with any project, get the style in your project from dist folder

```
	<link href="dist/assets/css/target-menu.css" rel="stylesheet">
```

After the CSS is in his place, you just have to add some HTML in the body element. 

```
	<nav>
        <a href="#menu">Menu</a>
        <div id="menu" data-direction="left">
            <p><a href="#closemenu"></a></p>
            <ul>
                <li><a href="#">Work</a></li>
                <li><a href="#">Who we are</a></li>
                <li><a href="#">What we do</a></li>
                <li><a href="#">Our thinking</a></li>
                <li><a href="#">Our events</a></li>
                <li><a href="#">Contact</a></li>
                <li><a href="#">Careers</a></li>
            </ul>
        </div>
    </nav> <!-- end navigation -->
```

You can adjust the direction of menu with the 'data-direction' attribute; 
```	
	data-direction="left"
	data-direction="right"
```

## Play with source
If you would like to download the source and play around with it feel free

```
	npm install gulpjs/gulp#4.0 --save-dev

	npm install

	npm install -g browser-sync

	npm install browser-sync --save-dev

	gulp
```

You are ready, have fun!