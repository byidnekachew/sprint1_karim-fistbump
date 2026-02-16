## Bug 1: Fists bumps do not disappear after using them

**Bug cause:** Intentional  

**Fix:**  

Added this code:

```javascript
// Remove if not clicked
setTimeout(() => {
    if (pic.parentElement) {
        pic.remove();
    }
}, 60000);

and

pic.remove(); to:

pic.addEventListener('click', () => {
    pic.remove();
    startTimingMeter();
});
