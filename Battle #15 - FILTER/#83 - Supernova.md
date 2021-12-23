# 83 - Diamond Cut

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/83.png)

## My Solution

```
<div></div>
<style>
   body{background:#243D83;display:grid;place-items:center}
  ::before,::after{
    content:"";
    position:absolute;
    background:#6592CF;
  }
  div{
    width:60px;
    height:60px;
    background:#EEB850;
    transform:rotateZ(45deg);
    position:relative;
    border-radius:50%;
  }
  div::before{
    width:100px;
    height:50px;
    border-radius:50px 50px 0 0;
    top:-80px;
    left:50%;
    transform:translateX(-50%);
    -webkit-box-reflect:below 120px;
  }
    div::after{
    width:50px;
    height:100px;
    border-radius:50px 0 0 50px;
  	left:-80px;
    top:50%;
    transform:translateY(-50%);
    -webkit-box-reflect:right 120px;
  }
</style>
```
