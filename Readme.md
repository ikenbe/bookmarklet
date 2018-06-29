# **This Repo is for the Bookmarklets I use.**

## How to use:

1. Copy the bookmarklet code below
2. Add something to your bookmark bar.
3. Edit the bookmark (by right clicking the bookmark and choose 'edit')
4. Paste and save.

## Bookmarklets

### AutoScroll

```
javascript:if(!_){var _={'a':'scrollBehavior' in document.documentElement.style,'b':function(){window.scrollBy({"behavior": "smooth","top":600})}}};if(_.c){_.c=0;clearInterval(_.d)}else{_.c=1;if(!_.a){_.b=function(x){scrollBy(0,x||600)}}_.d=setInterval(function(){_.b()},3300);_.b()}
```
Features:

-   Click to start scrolling; click again to stop.
    
-   Enables smooth scrolling when the browser supports it.
