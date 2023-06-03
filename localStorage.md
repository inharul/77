#636f6465
### Introduction
`localStorage` , web storage object similar to  `sessionStorage`  allows to store key-value pairs in the browser. `localStorage` however stores the data in the browser even when the page is closed or the browser is restarted unless manually changed/deleted by the user or by the webpage.

- Most modern browsers allow at least 5 megabytes of data (or more) and have settings to configure that.
- Shared between all tabs and windows from the same origin.
- The data does not expire (unlike `sessionStorage`). It remains after the browser restart and even OS reboot.

It's best for data storage (for data storing in a browser). Instead of needing a database with a serve and an internet connection, `localStorage` uses the browser and depends on it which is pretty reasonable. The data stored in `localStorage` can be accessed easily through `JavaScript`.

To access `localStorage`, go to any webpage and open Developer Tools.
From there, (depending upon your browser) Go to Application or Storage menu and expand the dropdown and select one listed there. You'll see a window with key and data values.
This is `localStorage` and the data you'll be seeing will be the stored data on your browser for that specific webpage.

[Figure 1: localStorage window]

### Methods (using it)
We can manipulate this web storage object easily just by simple  `JavaScript`. Use the console if you'd like to play around.

```javascript
localStorage.setItem('test', 1);
```

The above statement sets/adds a new key with value to the `localStorage`. In this example, we set the `'test'` key to have an integer value of `1`. This value now will be stored even when you restart your computer or leave it to go idle when your stomach calls for a quick lunch. In any time, if you need to access that value after coming back with a full stomach then just get it by
```javascript
localStorage.getItem('test')
```
