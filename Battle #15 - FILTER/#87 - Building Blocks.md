# 87 - Building Blocks

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/87.png)

## My Solution

```
<div class="left-top"></div><div class="left-bottom"></div>
<div class="right-bottom"></div><div class="right-top"></div>
<style>
  body{background:#F3AC3C;display:grid;place-items:center}
  ::before{
    content:"";
    position:absolute;
  }
  body::before{
    width:70px;
    height:70px;
    background:#F3AC3C;
    border-radius:10px;
    z-index:1
  }
  div{
    width:150px;
    height:50px;
    position:absolute;
    background:#1A4341; 
  }
  .left-top{
    left:65px;
    top:65px;
    border-radius:10px 10px 10px 0px;
  }
  .left-bottom{
    left:65px;
    top:115px;
    width:110px;
    background:linear-gradient(to top, transparent 0 50%, #1A4341 0%)
  }
  .left-bottom::before{
    bottom:0;
    background:#1A4341;
    width:100px;
    height:100%;
    z-index:2;
    border-radius:0 0 10px 10px;
  }
  .right-bottom{
    top:185px;
    left:185px;
    border-radius:10px 0 10px 10px;
  }
  .right-top{
    top:135px;
   	left:225px;
    width:110px;
    background:linear-gradient(to bottom, transparent 0 50%, #1A4341 0%)
  }
  .right-top::before{
    right:0;
    background:#1A4341;
    width:100px;
    height:100%;
    z-index:2;
    border-radius:10px 10px 0 0;
  }
</style>
```
