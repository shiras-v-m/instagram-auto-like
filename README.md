## steps
====================

1. Open instagram in pc browser
2. open console by pressing F12                                                                        
1. Copy the code below.
1. paste it on browser console and hit enter key.
1. All set!

**Note : By execute this code may leads to ban your instagram account **
*Happy coding!* :)


```javascript
let likesCount = 0;
setInterval(() => {
    const heartBtn = document.querySelector('svg[aria-label="Like"][width="24"]');
    const navigationBtn = document.querySelector('svg[aria-label="Next"]');
    if (heartBtn) {
        heartBtn.parentNode.parentElement.click()
        likesCount++;
        console.log(`You've liked ${likesCount} post(s)`);
    }
    navigationBtn.parentElement.parentElement.click();
}, 5000);
```
