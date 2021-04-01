# 45 - Magical Tree

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/45.png)

## My Solution

```
<div></div>
<span></span>
<style>
  body{margin:0;background:#1A4341;display:flex;justify-content:center;}
  div {
    width: 90px;
    height: 120px;
    background: #1A4341;
   	box-shadow:0 0 0 30px #998235, 0 0 0 60px #1A4341, 0 0 0 90px #F3AC3C;
  }
  span{
    position:absolute;
    width:30px;
    height:300px;
    background:#F3AC3C;
  }
  span:before{
    content:"";
    position:absolute;
    width:270px;
    height:30px;
    background:#998235;
    bottom:30px;
    left:-120px;
    z-index:-1;
  }
</style>
```
