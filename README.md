# 已经由 Typed.js改写,css部分保留并且注释.  
# Fri-Feb-2023 00:32  






=============================================================
# ERROR Page
 **PenCode Original URL: [ErrorPage](https://codepen.io/leonardo-asher-grace/pen/vYpoGNW)**

 ---
## **Some Basic Options：**
- ## *Change Main Text:*
Go to style.css
```css
.message:after {
    display: block;
    overflow: hidden;
    width: 0;
    white-space: nowrap;
    animation: a1 8.6s steps(x) forwards;
    content: "Text1";
}
.message:after {
    animation: a2 6.4s steps(y) 8.6s forwards;
    content: "Text2";
```
### x:**Means you have the number of all characters in text1.**
### y:**Means you have the number of all characters in text2.**  
### After That, **Maybe you need to change the time in the *animation* based on the number of characters.**
- ## *Next Step:*
Go to style.css
```css
@keyframes a1 {
    to {
        width: xch;
    }
}
@keyframes a2 {
    to {
        width: ych;
    }
}
```
### **Change the value of x, y to the value of x, y in the previous step**
---
- ## *Import Your Background Image:*
Go to style.css
```css
body {
    margin: 0;
    height: 100vh;
    background: radial-gradient(rgba(0, 0, 0, 0.2), #000000), url(Image URL) 50%/cover no-repeat #000;
    background-blend-mode: luminosity;
    color: lime;
    font: 1.5em/ 2 vt323, monospace;
}
```

## **To Do:**
1. - [ ] Add More animation 😍
2. - [ ] Global center 😂
3. - [ ] Add Mobile phone adaptation 🙄
4. - [ ] Rewrite Footer 😫
5. - [ ] Fix known bugs 😢


## **CopyRight:**
> JavaScript File: https://wow.techbrood.com/libs/jquery/jquery-1.11.1.min.js  
> The MIT License (MIT)  
 >Copyright (c) 2022 by Leonardo (https://codepen.io/leonardo-asher-grace/pen/vYpoGNW)
