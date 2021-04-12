# 61 - ImprovMX

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/61.png)

## My Solution

```
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<style>
  body{margin:0;background:#191919;display:flex;justify-content:center;}
  body:after,body:before{
    content:"";
    position:absolute;
    width:200px;
    height:10px;
    top:204px;
    left:100px;
    background:#5DBCF9;
    box-shadow:0 -10px 0 #191919
  }
  body:before{
    width:110px;
    height:10px;
    top:224px;
    left:145px;
  }
  div{
    position:absolute;
    width:30px;
    height:20px;
    border:10px solid #5DBCF9;
    top:66px;
  }
  div:nth-of-type(2){
    width:80px;
    height:50px;
    border:10px solid #5DBCF9;
    top:96px;
    border-bottom:none;
  }
  div:nth-of-type(3){
    width:80px;
    height:40px;
    border:10px solid #5DBCF9;
    top:145px;
    left:128px;
    border-bottom:none;
    border-right:none;
    transform:rotate(-30deg)
  }
    div:nth-of-type(4){
    width:80px;
    height:40px;
    border:10px solid #5DBCF9;
    top:145px;
    left:181px;
    border-bottom:none;
    border-left:none;
    transform:rotate(30deg)
  }
  div:nth-of-type(5){
    width:10px;
    height:60px;
    top:135px;
    left:195px;
    border:none;
    background:#5DBCF9;
  }
</style>
```
