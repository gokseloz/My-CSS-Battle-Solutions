# 52 - Break the Chain

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/52.png)

## My Solution

```
<span></span>
<div></div>
<div></div>
<style>
  body{background:#6592CF;}
  div{
    width:10px;
    height:50px;
	background:#243D83;
    position:absolute;
    left:45px;
    top:140px;
    color:#243D83;
    box-shadow:45px 0, 90px 0, 165px 0, 210px 0, 255px 0, 300px 0;
  }
  div:nth-of-type(2){
    width:20px;
    height:20px;
    border-radius:50%;
    top:130px;
    left:40px;
  }
  span{
    width:40px;
    height:40px;
    position:absolute;
    background:#EEB850;
    border-radius:50%;
    left:30px;
    top:120px;
    color:#EEB850;
    box-shadow:45px -10px 0 10px, 90px 0;
  }
</style>
```
