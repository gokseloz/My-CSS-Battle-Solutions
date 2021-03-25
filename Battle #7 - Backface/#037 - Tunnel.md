# 37 - Tunnel

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/37.png)

## My Solution

```
<div><div><div></div></div></div>
<style>
  body{background:#6592CF}
  div {
    position:Absolute;
    left:50%;
    top:50%;
    transform:translate(-50%,-50%);
    width:250px;
    height:250px;
    background:#243D83;
  }
  div > div{
    width:150px;
    height:150px;
    background:#6592CF;
	transform:translate(-50%,-50%) rotate(15deg);
  }
  div>div>div{
    width:75px;
    height:75px;
    background:#243D83;
  }
</style>
```
