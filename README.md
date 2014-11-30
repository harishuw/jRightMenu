jRightMenu
=========

This script is used to create a menu on right click
###Script
```
<script src="js/jRightMenu.min.js"></script>
```

###Usage
```
 var menu =new rightMenu();
 menu.add('#cmenu','#rmtable');
```
###To close menu
```
menu.close() 
```
###To open menu
```
menu.open() 
```
###To destroy menu
```
menu.destroy() 
```
###Callback
For call back before showing menu each time
Use Attribute data-callback or callback in menu element
For this callback function current pointer event.target will be passed as argument
###Manual z-index
To give manual z index use attribute data-zindex or zindex in menu element
