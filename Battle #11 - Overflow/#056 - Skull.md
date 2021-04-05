# 56 - Skull

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/56.png)

## My Solution

```
<div></div>
<div chin></div>
<div teeth></div>
<span></span>
<style>
  body{background:#191919}
  div {
    position:absolute;
    top:85px;
    left:50%;
    transform:translateX(-50%);
    width: 120px;
    height: 100px;
    border-radius:70px 70px 12px 12px;
    background: #4F77FF;
    transform-origin:right bottom;
  }
  [chin]{
    width:80px;
    height:30px;
    top:185px;
    border-radius:0 0 20px 20px
  }
  [teeth]{
    width:10px;
    height:10px;
    background:#191919;
    top:205px;
    left:46.3%;
    color:#191919;
    border-radius:20px 20px 0px 0px;
    box-shadow:15px 0, 30px 0
  }
  span{
    position:absolute;
	width:40px;
    height:40px;
    border-radius:50%;
    background:#191919;
    left:155px;
    top:137.5px;
    color:#191919;
    box-shadow:50px 0, 25px 28px 0 -10px;
  }
</style>
```
