
### About

As I rarely need the virtual desktop pager which takes up a lot of space in the panel, I was looking for 
a small widget that just shows the currently active desktop.
 
After not finding such a widget, I decided to build it myself. The widget has no configuration whatsoever, 
just add it to the panel and you are good to go. Although it is possible to add the widget to the desktop 
as well, it is usually of little use since it will be hidden behind any other window. Also, the appearance is 
currently fixed.
 
### Installation

```
> [clone repository] 

> cd virtual-desktop-indicator/

> plasmapkg2 -i .
```


### Development

* plasmoid managment
```
> cd virtual-desktop-indicator/

> plasmapkg2 -i .  # install
> plasmapkg2 -u .  # update
> plasmapkg2 -r .  # remove
```

* test in plasmoidviewer

```
> plasmoidviewer --applet .
```

* restart PLASMA shell to reload changes
```
> killall plasmashell; kstart5 plasmashell
```
