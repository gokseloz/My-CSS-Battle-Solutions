# 100  - CSSBattle

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/100.png)

## My Solution

```
<div class="leftWall"></div>
<div class="swordCont">
  	<div class="leftSwordHandle1"></div>
	<div class="leftSwordHandle2"></div>
	<div class="leftSwordHandle3"> </div>
	<div class="leftSwordHandle2Add"></div>
	<div class="rightSwordHandle1"></div>
	<div class="rightSwordHandle2"></div>
	<div class="rightSwordHandle3"> </div>
</div>
<div class="rightWall"></div>

<style>
  body{background:#14313E;display:flex;justify-content:center;align-items:center;}
  *{box-sizing:border-box}
  ::before,
  ::after{
    content:"";
    position:absolute;
  }
  .leftWall {
	width:40px;
	height:150px;
	background:#FFDF00;
    border-radius:20px 0 0 20px;
    position:relative;
  }
  .leftWall::before{
    width:15px;
    height:67%;
    background:#14313E;
    right:0;
    top:50%;
    transform:translateY(-50%);
    border-radius:10px 0 0 10px;
  }
  .leftWall::after{
    width:10px;
    height:27%;
    top:50%;
    transform:translate(-98%,-50%);
    background:#FFDF00;
    border-radius:5px 0 0 5px;
  }
  .rightWall{
    width:40px;
	height:150px;
	background:#FFDF00;
    border-radius:0 20px 20px 0;
    position:relative;
  }
  .rightWall::before{
    width:15px;
    height:67%;
    background:#14313E;
    left:0;
    top:50%;
    transform:translateY(-50%);
    border-radius:0 10px 10px 0;
  }
  .rightWall::after{
    width:10px;
    height:27%;
    top:50%;
    right:0;
    transform:translate(100%,-50%);
    background:#FFDF00;
    border-radius:0 5px 5px 0;
  }

  .swordCont{
    width:194px;
    height:150px;
    position:relative;
  }
  .leftSwordHandle1{
    width:20px;
    height:52px;
    background:#FFDF00;
    position:absolute;
    bottom:5px;
    left:12px;
  	transform:rotate(45deg);
    transform-origin:bottom;
    border-radius:8px;
  }
  .leftSwordHandle2{
    width:30px;
    height:40px;
    background:#FFDF00;
    position:absolute;
    bottom:28.5px;
    left:50.5px;
  	transform:rotate(45deg);

  }
  .leftSwordHandle2Add{
    width:30px;
    height:79px;
    background:#FFDF00;
    position:absolute;
    bottom:87px;
    left:128px;
  	transform:rotate(45deg);
  }
   .leftSwordHandle2Add::before{
    border:16px solid #14313E;
    right:14px;
 	top:-1;
     
    border-bottom-color:transparent;
    border-left-color:transparent;
    border-right-color:transparent;
  }
  .leftSwordHandle2Add::after{
    border:16px solid #14313E;
    left:14px;
 	top:-1;

    border-bottom-color:transparent;
    border-left-color:transparent;
    border-right-color:transparent;
  }
  
  .leftSwordHandle3{
    width:80px;
    height:20px;
    background:#FFDF00;
    position:absolute;
    bottom:30.5px;
    left:17.5px;
  	transform:rotate(45deg);
  }
  .rightSwordHandle1{
     width:20px;
    height:52px;
    background:#FFDF00;
    position:absolute;
    bottom:5px;
	right:12px;
  	transform:rotate(-45deg);
    transform-origin:bottom;
    border-radius:8px;
  }

  .rightSwordHandle2{
    width:29.5px;
    height:170px;
    background:#FFDF00;
    position:absolute;
    bottom:9px;
    right:95.5px;
  	transform:rotate(-45deg);
  }
  .rightSwordHandle2::before{
    border:16px solid #14313E;
    right:14px;
    top:-1;
    border-bottom-color:transparent;
    border-left-color:transparent;
    border-right-color:transparent;
  }
  .rightSwordHandle2::after{
    border:16px solid #14313E;
    left:14px;
    top:-1;
    border-bottom-color:transparent;
    border-left-color:transparent;
    border-right-color:transparent;
  }
  .rightSwordHandle3{
    width:80px;
    height:20px;
    background:#FFDF00;
    position:absolute;
	bottom:34px;
    right:10px;
  	transform:rotate(-45deg);
    transform-origin:bottom;
  }
</style>
 
```
