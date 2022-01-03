# 91 - Reflection

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/91.png)

## My Solution

```
<div class="topCircle"></div>
<div class="bottomCircle"></div>
<style>
  body{background:linear-gradient(to bottom, #D25B70 0 50%, #6CB3A9 50%)}
  div{
    width:200px;
    height:100px;
    position:absolute;
    left:50%;
    top:50%;
  }
  .topCircle{
    border-radius:100px 100px 0 0;
    transform:translate(-50%,-100%);
    background:#F6DF96;
  }
  .bottomCircle{
    border-radius:0 0 100px 100px;
    transform:translate(-50%,0%);
    background:repeating-linear-gradient(#6CB3A9, #6CB3A9 15px, #F6DF96 15px, #F6DF96 25px) 
  }
</style>
```
