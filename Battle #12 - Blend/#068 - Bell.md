# 68 - Bell

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/68.png)

## My Solution

```
<div></div>
<style>
  body{background:#191919;display:flex;justify-content:center;align-items:center;}
  div{
    width:120px;
    height:120px;
    background:#E08027;
    border-radius:60px 60px 10px 10px;
    position:relative;
  }
  div:before,div:after{
    content:"";
    position:absolute;
    width:50px;
    height:50px;
    background:#F2AD43;
    border-radius:50%;
    left:34.8;
    top:-24px;
    z-index:-1
  }
  div:after{
    background:#824B20;
    top:auto;
    bottom:-24.5px;
  }
</style>
```
