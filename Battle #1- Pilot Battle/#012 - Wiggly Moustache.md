# 12 - Wiggly Moustache

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/12.png)

## My Solution

```
<div>
  <span></span>
   <span></span>
</div>
<style>
  body{
    background:#F5D6B4;
    display:flex;
    justify-content:center;
    align-items:center;
  }
  div{
    width: 60px;
    height: 30px;
    border-radius:100px 100px 0 0;
    border:20px solid #D86F45;
    border-bottom:none;
    margin-top:-50px;
    position:relative;
  }
  span{
    position:absolute;
    width: 60px;
    height: 30px;
    top:30px;
    border-radius:0 0 100px 100px;
    border:20px solid #D86F45;
    border-top:none;
  }
  span:after{
    content:"";
    position:absolute;
    background:#D86F45;
    width:20px;
    height:20px;
    top:-10px;
    border-radius:50%;
  }
  span:nth-child(1){
   left:-100px
  }
  span:nth-child(1):after{
  left:-20px;
  }
  span:nth-child(2){
   right:-100px
  }
  span:nth-child(2):after{
    right:-20px;
  }
</style>
```
