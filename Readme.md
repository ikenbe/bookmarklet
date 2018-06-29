# **This Repo is for the Bookmarklets I use.**

## How to use:

1. Copy the bookmarklet code below
2. Add something to your bookmark bar.
3. Edit the bookmark (by right clicking the bookmark and choose 'edit')
4. Paste and save.

## Bookmarklets

### AutoScroll - Step by step

```
javascript:if(!_Scroll){var _Scroll={'a':'scrollBehavior' in document.documentElement.style,'b':function(){window.scrollBy({"behavior": "smooth","top":600})}}};if(_Scroll.c){_Scroll.c=0;clearInterval(_Scroll.d)}else{_Scroll.c=1;if(!_Scroll.a){_Scroll.b=function(x){scrollBy(0,x||600)}}_Scroll.d=setInterval(function(){_Scroll.b()},3300);_Scroll.b()}
```
Features:

-   Click to start scrolling; click again to stop.
    
-   Enables smooth scrolling when the browser supports it.

### AutoScroll - Continous

```
javascript:if(!_Scroll){var _Scroll={'e':'scrollBehavior' in document.documentElement.style,'f':function(){window.scrollBy({"behavior": "smooth","top":5})}}};if(_Scroll.g){_Scroll.g=0;clearInterval(_Scroll.h)}else{_Scroll.g=1;if(!_Scroll.e){_Scroll.f=function(x){scrollBy(0,x||5)}}_Scroll.h=setInterval(function(){_Scroll.f()},20);_Scroll.f()}
```
