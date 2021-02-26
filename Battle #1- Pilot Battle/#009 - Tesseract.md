# 9 - Tesseract

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/9.png)

## My Solution

```
<div class="rect"></div>
<div class="circle"></div>
<style>
  body{
    background-color:#222730; 
    display:flex;
    align-items:center;
    justify-content:center;
    margin:0;
    background:linear-gradient(#222730 75px, #4CAAB3 75px 225px, #222730 225px)
  }
  .rect{
    width:150px;
    height:150px;
    background-color:#4CAAB3;
    transform:rotate(45deg);
    box-shadow:0 0 0 50px #222730;
  }
  .circle{
    position:absolute;
    width:50px;
    height:50px;
    background-color:#393E46;
    border-radius:50%
  }
</style>
```
