# 79 - Tambourine

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/79.png)

## My Solution

```
<span></span>
<div></div>
<span></span>
<p></p><p></p><p></p><p></p><p></p>
<style>
  body{background:#6592CF;}
  div,span,p{
    position:absolute;
    border-radius:50%;
  }
  div{
    left:115px;
    top:75px;
    width:150px;
    height:150px;
    background:transparent;
    border:10px solid #243D83;
  }
  span{
    width:130px;
    height:180px;
    border:10px solid;
    border-color:#243D83 transparent transparent transparent;
    background:#6592CF;
    left:125px;
    top:200px;
  }
  span:nth-of-type(2){
    width:125px;
    left:135px;
    width:130px;
    top:210px;
    background:#6592CF;
	border:none;
  }
  p{
 	width:30px;
    heighT:30px;
    background:#243D83;
    border:10px solid #243D83;
    background:radial-gradient(circle at center, #243D83 0 24%, #6592CF 24%);
    left:175px;
    top:39px;
  }
  p:nth-of-type(2){
    left:105px;
    top:79px;
  }
  p:nth-of-type(3){
    left:245px;
    top:79px;
  }
  p:nth-of-type(4){
    left:105px;
    top:149px;
  }
  p:nth-of-type(5){
    left:245px;
    top:149px;
  }
</style>
```
