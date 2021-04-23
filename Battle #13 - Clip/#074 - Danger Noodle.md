# 74 - Danger Noodle

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/74.png)

## My Solution

```
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<style>
  body{margin:0;background:#191919;}
  
  :after,:before{
    position:absolute;
    content:"";
  }
  
  body:before{
    width:50px;
    height:30px;
    background:#E08027;
    border-radius:20px 30px 30px 20px;
    left:265px;
    top:135px;
  }
  
  body:after{
    width:10px;
    height:10px;
    background:#191919;
 	  border-radius:50%;
    left:295px;
    top:137px;
    box-shadow:0 16px #191919
  }
  
  div{
    position:absolute;
    width:30px;
    height:70px;
    border:5px solid #E08027;
    border-bottom:none;
    border-radius:50px 50px 0 0;
  }
  div:before{
    width:60px;
    height:80px;
    border:5px solid #E08027;
    border-bottom:none;
    border-radius:50px 50px 0 0;
    left:-20px;
    top:-20px;
  }
  
  div:nth-of-type(1){
    left:30px;
    top:55px;
  }
  
  div:nth-of-type(2){
    transform:rotate(180deg);
    left:80px;
    top:110px;
    height:130px;
  }
  div:nth-of-type(2):before{
    height:130px;
  }
  
  div:nth-of-type(3){
    height:120px;
    left:130px;
    top:55px;
  }
  div:nth-of-type(3):before{
    height:130px;
  }
  
  div:nth-of-type(4){
    transform:rotate(180deg);
    left:180px;
    top:170px;
    height:70px
  }
  div:nth-of-type(4):before{
    height:80px;
  }
  
  div:nth-of-type(5){
    height:50px;
    top:155px;
    left:230px;
    border-right-color:transparent;
    border-radius:20px 0 0 0
  }
  div:nth-of-type(5):before{
    heighT:65px;
    border-right-color:transparent;
    border-radius:35px 0 0 0
  }
  
  div:nth-of-type(6){
    height:50px;
    top:90px;
    left:-20px;
    border-right-color:transparent;
    border-radius:20px 0 0 0;
    transform:rotate(180deg)
  }
  div:nth-of-type(6):before{
    heighT:65px;
    border-right-color:transparent;
    border-radius:35px 0 0 0
  }
</style>
```
