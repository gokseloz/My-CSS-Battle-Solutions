# 88 - Tight Corner

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/88.png)

## My Solution

```
<div class="bar"></div><div class="curvMaker"></div>
<style>
  body{background:#F7F3DA;margin:0;}
  ::before,::after{
    content:"";
    position:absolute;
  }
  .bar{
    position:absolute;
    top:110px;
    width:100%;
    height:80px;
    background-color:#D25B70;
    position:relative;
    background:linear-gradient(to bottom, transparent 0% 25%, #D25B70 25% 75%, transparent 75% 100%)
  }
  .bar::before{
    left:0;
    width:50%;
    height:100%;
    background:#D25B70;
    border-radius:0 10px 0 0;
  }
  .bar::after{
    right:0;
    width:50%;
    height:100%;
    background:#D25B70;
    border-radius:0 0 0 10px;
  }
  .curvMaker{
    width:50%;
    height:50%;
    background:#F7F3DA;
    position:absolute;
    top:0;
    right:0;
    border-radius:0 20px 0 20px;
    box-shadow:-200px 150px #F7F3DA;
  }
</style>
```
