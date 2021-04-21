# 71 - Elephant

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/71.png)

## My Solution

```
<span ear></span>
<span ear></span>
<div head></div>
<p mustache></p>
<a trunk></a>
<style>
  body{margin:0;background:#998235}
  
  div,span,p,a,:after,:before{position:absolute}
  
  :after,:before{content:""}
  
  [head]{
    width:180px;
    height:180px;
    background:#1A4341;
    border-radius:50%;
    left:110px;
    top:60px;
  }
  div:before,div:after{
    left:40px;
    top:90px;
    width:40px;
    height:20px;
    border-radius:0 0 25px 25px;
    background:radial-gradient(circle at 50% 0, #0B2429 35%,#998235 0%);
  }
  div:after{
    left:100px;
  }
  [ear]{
    width:80px;
    heighT:180px;
    border-radius:50%;
    background:#1A4341;
    top:60px;
    left:50px;
    overflow:hidden;
  }
  [ear]:nth-of-type(2){
    transform:rotate(180deg);
    left:270px;
  }
  span:before{
    width:80px;
    heighT:180px;
    top:50%;
    transform:translateY(-50%);
    border-radius:50%;
    background:#0B2429;
    left:15.5px
  }
  [mustache]{
    width:80px;
    height:80px;
    border:20px solid #fff;
    border-radius:50%;
    border-bottom-color:transparent;
    border-left-color:transparent;
    transform:rotate(-45deg);
    left:140px;
    top:174px
  }
  [trunk]{
    width:40px;
    height:200px;
    background:#0B2429;
    border-radius:50px;
	left:180px;
    top:180px;
  }
</style>
```
