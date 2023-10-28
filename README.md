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
