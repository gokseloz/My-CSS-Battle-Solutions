# 90 - Eclipse

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/90.png)

## My Solution

```
<div></div>
<style>
  body{background:#F3AC3C;display:grid;place-items:center}
  div{
    width:200px;
    height:200px;
    background:#1A4341;
    border-radius:50%;
    position:relative;
    border:25px solid #F3AC3C;
  }
  div::before,div::after{
    content:"";
    position:absolute;
    width:200%;
    height:200%;
    background:#998235;
    border-radius:50%;
    left:-50%;
  }
  div::before{
    top:-150%;
    z-index:-1
  }
  div::after{
    bottom:-150%;
    z-index:2
  }
</style>
```
