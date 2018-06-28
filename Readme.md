# **This Repo is for the Bookmarklets I use.**

1. AutoScroll

```
javascript:if(localStorage.getItem('scroll')){clearInterval(bkmkscroll);localStorage.removeItem('scroll')}else{var bkmkscroll=setInterval(function(s){scrollBy(0,s||400)},2000);localStorage.setItem('scroll','1')}
```
