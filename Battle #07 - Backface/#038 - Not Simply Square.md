# 38 - Not Simply Square

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/38.png)

## My Solution

```
<div></div>
<div><span></span><span></span><span></span></div>
<style>
  body{background:#1A4341;}
  div {
    position:Absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%);
    width:200px;
    height:200px;
    background:#998235;
    border-radius:50%;
  }
  div:nth-of-type(2){
    border-radius:50%/ 250px;
    width:250px;
    height:140px;
    background:#1A4341;
    overflow:hidden;
    display:flex;
    flex-direction:column;
    justify-content:space-evenly
  }
  span{
    width:100%;
    height:20px;
    background:#F3AC3C;
  }
</style>
```
