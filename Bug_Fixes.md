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


pic.addEventListener('click', () => {
    **pic.remove();**
    startTimingMeter();
});
```

## Bug 2: Game crashes after 800+ Nayans

**Bug cause:** Not intentional  

**Fix:**  

Added `&& item.count <= 200` so that visually the Nayans cap at 200, but the user can still purchase more.

```javascript
if (item.id === 'autoClicker1' && item.imageSrc && item.count <= 200) {
    addBuddy(item.imageSrc, item.count);
}
```
