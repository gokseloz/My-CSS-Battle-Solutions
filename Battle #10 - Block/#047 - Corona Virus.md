# 47 - Corona Virus

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/47.png)

## My Solution

```
<span></span>
<span></span>
<span></span>
<div></div>
<style>
  body{margin:0;background-color:#1A4341;background:#1A4341}
  div {
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%);
   	width:100px;
    height:100px;
    border-radius:50%;
    background-color:#F3AC3C;
    background:radial-gradient(circle at 35% 35%, #998235 0 16.3%, transparent 0%), radial-gradient(circle at 75% 25%, #998235 0 4.7%, transparent 0%), radial-gradient(circle at 50% 75%, #998235 0 11%, #F3AC3C 0%);
  }
  span{
    position:absolute;
    top:46.5%;
    left:50%;
    width:10px;
    height:180px;
    background:#F3AC3C;
    border-radius:10px;
    transform:translate(-50%,-50%);
	transform-origin:50% 55.5%;
  }
  span:nth-of-type(2){
        transform:translate(-50%,-50%) rotate(60deg);
  }
  span:nth-of-type(3){
        transform:translate(-50%,-50%) rotate(120deg);
  }
</style>
```
