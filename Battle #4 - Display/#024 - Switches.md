# 24 - Switches

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/24.png)

## My Solution

```
<div><span></span></div>
<div><span></span></div>
<style>
  body{margin:0;background:#62306D;}
  div{
    width:100px;
    height:150px;
    border-radius:50px;
    background:#AA445F;
    position:absolute;
    left:80px;
    top:50px;
  }
  span{
    position:absolute;
    width:100px;
    height:100px;
    background:#F7EC7D;
    border-radius:50%;
    bottom:0;
  }
  div:nth-of-type(2){
    left:220px;
    top:100px;
    background:#E38F66;
  }
  div:nth-of-type(2) > span{
    top:0;
  }
</style>
```
