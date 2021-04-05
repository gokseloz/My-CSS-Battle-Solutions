# 51 - Wear a Mask

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/51.png)

## My Solution

```
<div><span></span></div>
<style>
  body{margin:0;background:#293462;display:flex;justify-content:center;align-items:center;}
  div{
    width:150px;
    height:100px;
    background:radial-gradient(circle at 73.2% 60%, #FE5F55 0 16%, #FFF1C1 0%);
    border-radius:0 0 50px 50px;
    position:relative;
  }
  div:before,div:after{
    content:"";
    position:absolute;
    left:-60px;
    width:50px;
    height:40px;
    border-radius:40px 0 0 40px;
    border:10px solid #FFF1C1;
    background:transparent;
  }
  div:after{
    left:unset;
    right:-60px;
    border-radius:0 40px 40px 0;
  }
  span{
    position:absolute;
    top:20px;
    left:20px;
    width:40px;
    height:10px;
    border-radius:20px;
    box-shadow:0 20px 0 #FE5F55;
    background:#FE5F55;
  }
</style>
```
