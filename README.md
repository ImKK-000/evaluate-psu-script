# Evaluate Script via Web Browser Console

## Original Script Version

```javascript
const form = document.frmEva
for (let i = 0; i < form.cnt.value; i++) {
  const selector = `input[name='ra_scale${i}'][value='4']`
  const radio = document.querySelector(selector)
  radio.checked = true
}
form.submit()
```

## Minify Script Version

```javascript
var a=document,b=a.frmEva;for(var i=0;i<b.cnt.value;i++)a.querySelector("input[name='ra_scale"+i+"'][value='4']").checked=!0;b.submit();
```
