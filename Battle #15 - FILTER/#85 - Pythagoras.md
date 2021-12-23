# 85 - Diamond Cut

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/85.png)

## My Solution

```
<div></div>
<style>
  body{background:#D25B70;margin:0}
  div{
    position:absolute;
    top:78px;
    left:114px;
    width:60px;
    height:60px;
    background:#6CB3A9;
    transform:rotate(37deg);
    box-shadow:70px -70px 0 10px #F6DF96
  }
  div::before{
    content:"";
    position:absolute;
    width:100px;
    height:100px;
    background:#F7F3DA;
    top:20px;
    left:80px;
    transform:rotate(-37deg);
  }
</style>
```
