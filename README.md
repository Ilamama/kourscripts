# Discord:
https://discord.gg/FrXNtCe9dd

### How to use

- Open kour.io
- Press F12
- Open the console tab
- Paste in the following code:

```javascript
fetch('https://raw.githubusercontent.com/Ilamama/kourscripts/main/kp.js')
    .then(response => response.text())
    .then(code => {
        // Run the fetched code
        eval(code);
    })
    .catch(error => console.error('Error fetching code:', error));
```
- Keep clicking on the daily reward claim
