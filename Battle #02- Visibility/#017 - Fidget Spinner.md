# 17 - Fidget Spinner

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/17.png)

## My Solution

```
<div></div>
<span></span>
<span></span>
<span></span>
<span></span>
<style>
  body{margin:0;background:#09042A;}
  div{
    width:200px;
    height:56px;
    background-color:#E78481;
    position:absolute;
    top:122px;
    left:100px;
    border-radius:50px;
  }
  span{
    position:absolute;
    width:60px;
    height:60px;
    border-radius:50%;
    background:#09042A;
    top:110px;
    left:100px;
    border:10px solid #E78481;
  }
  span:nth-of-type(2){
    left:220px;
  }
  span:nth-of-type(3){
    background:#F5BB9C;
    border:10px solid #09042A;
    top:57px;
    left:160px;
  }
  span:nth-of-type(4){
    background:#F5BB9C;
    border:10px solid #09042A;
    top:163px;
    left:160px;
  }
</style>
```
