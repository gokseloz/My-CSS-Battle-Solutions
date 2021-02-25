# 8 - Forking Crazy

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/8.png)

## My Solution

```
<div class = "main">
  <div class="bar holder"></div>
  <div class="bar bar1"></div>
  <div class="bar bar2"></div>
  <div class="bar bar3"></div>
  <div class="bar bar4"></div>
  <div class="bar innerBar innerBar1"></div>
  <div class="bar innerBar innerBar2"></div>
  <div class="bar innerBar innerBar3"></div>
</div>
<style>
  body{
    background-color:#6592CF;    
  }
  .main{
    width:140px;
    height:95px;
    background:#060F55;
    margin:155px 0 0 122;
    border-radius:0 0 140px 140px;
    position:relative;
  }
  .bar{
    position:absolute;
    width:20px;
    height:120px;
    background:#060F55;
    left:50%;
    transform:translateX(-50%);
    border-radius:10px;
  }
  .holder{
    bottom:-85px;
  }
  .bar1{
    top:-105px;
	left:10;
  }
  .bar2{
    top:-111%;
	left:50;
  }
  .bar3{
    top:-111%;
	left:90;
  }
  .bar4{
    top:-111%;
	left:130;
  }
  .innerBar{
    background:#6592CF;
    top:-115px;
  }
  .innerBar1{
	left:30;
  }
  .innerBar2{
	left:70;
  }
  .innerBar3{
	left:110;
  }
</style>
```
