# 64 - Door Knob

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/64.png)

## My Solution

```
<div></div>
<style>
  body{background:radial-gradient(circle at center, #E08027 20%,transparent 0),radial-gradient(circle at center, #824B20 32%, #191919 0)}
  div{
    width:80px;
    height:80px;
    border:20px solid #FFF58F;
    border-radius:50%;
    border-top-color:transparent;
    border-left-color:transparent;
    transform:rotate(45deg);
    position:absolute;
    left:140px;
    top:90px;
  }
  div:before,div:after{
    content:"";
    position:absolute;
    width:20px;
    height:20px;
    border-radius:50%;
    background:#FFF58F;
    left:-5.2;
    top:65;
  }
  div:after{
    left:66;
    top:-5.2px
  }
</style>
```
