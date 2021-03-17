# 13 - Totally Triangle

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/13.png)

## My Solution

```
<div></div>
<div></div>
<span></span>
<style>
  body{margin:0;background:#0B2429;}
 div {
    width: 200px;
    height: 200px;
    background-color: #998235;
	border-radius:100% 0% 100% 100%;
    position:absolute;
  	 top:50%;
   	left:50%;
  	 transform:translate(-50%,-50%) rotate(45deg)
  }
  div:nth-of-type(1){
    transform:translate(-50%,-50%) rotate(-135deg)
  }
  span{
    width: 50px;
    height: 50px;
    background-color: #0B2429;
    border-radius:50%;
    position:absolute;
  	 top:50%;
  	 left:50%;
   	transform:translate(-50%,-50%);
    border:45px solid #F3AC3C;
    box-shadow:0 0 0 20px #0B2429;
  }
</style>
```
