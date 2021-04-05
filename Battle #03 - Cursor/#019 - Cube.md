# 19 - Cube

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/19.png)

## My Solution

```
<div></div>
<span></span>
<span></span>
<style>
  body{margin:0;background:#0B2429;}
  div {
    width: 100px;
    height: 100px;
    background: #F3AC3C;
    transform:rotate(45deg);
    position:absolute;
    top:135px;
    left:150px;
  }
  span{
    width: 70px;
    height: 70px;
    background:#1A4341;
    transform:skew(0deg,45deg);
    position:absolute;
    left:200px;
    top:80px
  }
  span:nth-of-type(2){
    width: 70px;
    height: 70px;
    background:#998235;
    transform:skew(0deg,-45deg);
    left:130px;
    top:80px
  }
</style>
```
