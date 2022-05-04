# replit-themes
Here's a list of all the repl themes me and other contributors currently making!


## Installation
To install any theme, you must have a CSS injector.

Copy the CSS stylesheet of your liking and take the code and paste it into your injector.

You can also use this following script in the console:
```js
let el = document.createElement('link');

el.setAttribute('rel', 'stylesheet');
el.setAttribute('type', 'text/css');
el.setAttribute('href', 'https://cdn.jsdelivr.net/gh/buddy-codes/replit-themes/<filename>.min.css');
// Example of this URL: https://cdn.jsdelivr.net/gh/buddy-codes/replit-themes/discord.repl.theme.min.css

document.head.appendChild(el);
```
or this bookmarklet:
```js
javascript:void%20function(){const%20t=document.createElement(%22link%22);t.setAttribute(%22rel%22,%22stylesheet%22),t.setAttribute(%22type%22,%22text/css%22),t.setAttribute(%22href%22,%22https://cdn.jsdelivr.net/gh/buddy-codes/replit-themes/%22+prompt(%22Write%20the%20file%20name%20as%20it%20appears%20on%20the%20github%20repo%20(without%20.css)%22)+%22.min.css%22),document.head.appendChild(t)}();
```

## Contributions
If you would like to contribute you can make a PR.

MAKE SURE YOU TEST IT FIRST BEFORE MAKING A PR
