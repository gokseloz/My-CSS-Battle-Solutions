# 65 - Max Volume

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/65.png)

## My Solution

```
<div></div>
<span></span>
<span></span>
<span></span>
<style>
  body{background:#191919;}
  div{
    position:absolute;
    top:50px;
    left:100px;
    border-top:100px solid transparent;
    border-bottom:100px solid transparent;
    border-right:100px solid #5DBCF9;
  }
  div:before{
    content:"";
    position:absolute;
    width:100px;
    height:50px;
    background:#5DBCF9;
    border-radius:10px;
    top:-25px;
    left:-25px;
  }
  span{
    width:180px;
    height:180px;
    position:absolute;
    left:125px;
    top:50px;
    border-radius:50%;;
    border:10px solid #5DBCF9;
    border-left-color:transparent;
    border-bottom-color:transparent;
    transform:rotate(45deg);
  }
  span:nth-of-type(2){
  	width:130px;
    height:130px;
    top:75px;
    left:150px;
  }
  span:nth-of-type(3){
  	width:80px;
    height:80px;
    top:100px;
    left:175px;
  }
</style>
```
