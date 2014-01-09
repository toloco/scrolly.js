SCROLLY.js
===============================================================================


Scrolling lib for those one page or massive pages


Requeriments:
------------------------------------------------------
* Jquery >= 1.8



Configuration:
------------------------------------------------------
Add this javascript on your html code ( after jquery definition )
```javascript
    $(document).ready(function (){
        Scrolly.init(); 
    });
```

Or the full config (just overiding default)
```javascript
    $(document).ready(function (){
        Scrolly.init(
        	{ 
        		//Classes that points the elements
        		"selector" : "scrolly",

        		//Adjust the speed
            	"speed"    : 1000,

        	}
        ); 
    });
```


Use:
------------------------------------------------------
#### How to use

Quite easy to use, just add the class **scrolly** (or the one you chosen before) 

```html
	<a class=" **scrolly**" href="sectionID">
```


[![githalytics.com alpha](https://cruel-carlota.pagodabox.com/24c929b54abb9c96fc971da17c63a0fc "githalytics.com")](http://githalytics.com/toloco/frame)
