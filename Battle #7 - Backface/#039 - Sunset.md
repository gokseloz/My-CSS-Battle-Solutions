# 39 - Sunset

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/39.png)

## My Solution

```
<div></div>
<span></span>
<span></span>
<style>
  body{background:#293462;margin:0}
  div {
    width:200px;
    height:200px;
    background:#FFF1C1;
  }
  span{
    width:200px;
    height:100px;
    position:absolute;
    bottom:0;
    background:linear-gradient(to right, #FE5F55 75%, #A64942 0%)
  }
  span:nth-of-type(2){
    top:50px;
    left:150px;
    transform:rotate(90deg);
  }
</style>

```
