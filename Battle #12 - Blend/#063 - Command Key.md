# 63 - Command Key

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/63.png)

## My Solution

```
<div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
</div>
<style>
  body{background:#191919;}
  div {
    width: 50px;
    height: 50px;
    border:10px solid #5DBCF9;
    position:absolute;
    top:49.8%;
    left:50.2%;
    transform:translate(-50%,-50%);
	  position:relative;
  }
  div>div{
	position:absolute;
    left:-35px;
    top:-35px;
    border-radius:50px 50px 0px 50px;
  }
  div>div:nth-of-type(2){
    transform:rotate(90deg);
    left:50px;
    top:-70px;
  }
  div>div:nth-of-type(3){
    transform:rotate(180deg);
    left:50px;
    top:50px;
  }
   div>div:nth-of-type(4){
    transform:rotate(270deg);
    left:-70px;
    top:50px;
  }
</style>
```
