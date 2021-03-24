# 36 - Interleaved

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/36.png)

## My Solution

```
<div></div>
<div></div>
<style>
  body{background:#1A4341}
  div {
    width:50px;
    height:200px;
    background:#F3AC3C;
    position:absolute;
    bottom:0;
    left:25px;
    border-radius:50px 50px 0 0;
    color:#F3AC3C;
    box-shadow:150px 0, 300px 0;
  }
  div:nth-of-type(2){
    top:0;
    border-radius:0 0 50px 50px;
    left:100px;
    color:998235;
    background:#998235;
  }
</style>

```
