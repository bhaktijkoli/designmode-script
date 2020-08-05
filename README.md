# designmode-script
```js
document.onkeydown = function(e) {
    if(e.keyCode === 112) {
        if(document.designMode === 'off') {
            document.designMode = 'on'
        } else {
            document.designMode = 'off'
        }
    }
}
```
