# 70 - Froggy

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/70.png)

## My Solution

```
<span class="eyes"></span>
<span class="eyes"></span>
<div class="face"></div>
<style>
  body{margin:0;background:#293462}
  .face {
    position:absolute;
    top:110px;
    left:50%;
    transform:translate(-50%);
    width: 150px;
    height: 100px;
    border-radius:50px;
    background: #A64942;
    overflow:hidden;
  }
  .face:before{
    content:"";
    position:absolute;
    left:50%;
    transform:translateX(-50%);
    width:250px;
    height:150px;
    background:radial-gradient(circle at 46% 90%,#293462 2.5%, transparent 0), radial-gradient(circle at 54% 90%,#293462 2.5%,#FE5F55 0);
    border-radius:50%;
    bottom:30px;
  }
  .eyes{
    position:absolute;
    width:50px;
    height:50px;
    border-radius:50%;
    background:radial-gradient(circle at center,#293462 14% ,#FFF1C1 14% 42%,#FE5F55 0%);
    left:140px;
   	top:85px;
    z-index:2;
  }
  .eyes:nth-of-type(2){
    left:210px
  }
</style>
```
