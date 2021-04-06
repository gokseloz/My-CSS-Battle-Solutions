# 60 - Evil Triangles

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/60.png)

## My Solution

```
<span></span>
<div></div><div></div>
<div></div><div></div><div></div>
<div></div><div></div>
<style>
  body{background:#191919}
  span{
    position:absolute;
    left:100px;
    top:125px;
	width:200px;
    height:100px;
    background:#4F77FF;
  }
  div {
    position:absolute;
	top:75px;
    left:100px;
    border-width:50px;
    border-style:solid;
    border-color:#4F77FF transparent transparent transparent;
  }
  div:nth-of-type(2){
    left:200px
  }
  div:nth-of-type(3),div:nth-of-type(4),div:nth-of-type(5),div:nth-of-type(6),div:nth-of-type(7){
    left:100px;
    top:125px;
    border-color:#191919 transparent transparent transparent;
  }
   div:nth-of-type(4){
    left:200px;
  }
   div:nth-of-type(5){
    left:150px;
    transform:rotate(180deg)
  }
   div:nth-of-type(6){
    left:50px;
    transform:rotate(180deg)
  }
    div:nth-of-type(7){
    left:250px;
    transform:rotate(180deg)
  }
</style>
```
