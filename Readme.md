# **This Repo is for the Bookmarklets I use.**

## How to use:

1. Copy the bookmarklet code below
2. Add something to your bookmark bar.
3. Edit the bookmark (by right clicking the bookmark and choose 'edit')
4. Paste and save.

## Bookmarklets

- AutoScroll

```
javascript:if(localStorage.getItem('scroll')){clearInterval(bkmkscroll);localStorage.removeItem('scroll')}else{var bkmkscroll=setInterval(function(s){scrollBy(0,s||400)},2000);localStorage.setItem('scroll','1')}
```
Click to start scrolling; click again to stop. Edit 's||400' in the code to change the distance of each scroll, edit the '2000' to change interval (in ms).
