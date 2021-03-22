# 26 - Smiley

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/26.png)

## My Solution

```
<div></div>
<div></div>
<div></div>
<style>
  body{margin:0;background:#6592CF;}
  div{
    width:80px;
    height:80px;
    border-radius:50%;
    border:20px solid #060F55;
    border-left-color:transparent;
    border-bottom-color:transparent;
    transform:rotate(-45deg);
    position:absolute;
    top:40px;
    left:40px;
  }
  div:nth-of-type(2){
    left:240px;
  }
  div:nth-of-type(3){
    top:140px;
    left:140px;
    transform:rotate(135deg)
  }
</style>
```
