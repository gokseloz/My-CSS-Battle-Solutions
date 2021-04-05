# 18 - Matrix

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/18.png)

## My Solution

```
<div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div>
<style>
  body{margin:0;background-color:#5C434C;display:flex;flex-wrap:wrap;}
  div{
    width:80px;
    height:80px;
    margin:10px;
	background-color:#F09462;
    border-radius:80px 0 0 0;
  }
  div:nth-of-type(2n){
        background-color:#F5D6B4;
  }
   div:nth-of-type(5){
       background-color:#F5D6B4;
  }
  div:nth-of-type(6){
        background-color:#F09462;
  }
  div:nth-of-type(7){
       background-color:#F5D6B4;
  }
   div:nth-of-type(8){
        background-color:#F09462;
  }
</style>
```
