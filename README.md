# flowmetrics
Tool to extract flow metrics from Jira and other ticket systems

Work in progress


Just add this into the URL section of a new bookmark:

```
javascript:(function(){var el=document.createElement('script');el.type='text/javascript';el.src='https://mneuschaefer.github.io/flowmetrics/main.js';el.onerror=function(){alert("Looks like the Content Security Policy directive is blocking the use of bookmarklets\n\nYou can copy and paste the content of:\n\n\"https://mneuschaefer.github.io/flowmetrics/main.js\"\n\ninto your console instead\n\n(link is in console already)");console.log("https://mneuschaefer.github.io/flowmetrics/main.js");};document.getElementsByTagName('body')[0].appendChild(el);})();
```

(Inspired by https://github.com/micmro/performance-bookmarklet )
