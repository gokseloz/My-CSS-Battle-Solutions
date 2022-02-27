# 97 - Snowman

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/97.png)

## My Solution

```
<div class="container">
  <a class="body"></a>
  <a class="head">
    <div class="eyes left"></div>
    <div class="eyes right"></div>
	</a>
  <p class="scarf"></p>
  <p class="hat">
    <span class="hat-bottom"></span>
  </p>
</div>

<style>
  body{
    background-color:#AC474B;
    display:flex;
    justify-content:center;
    align-items:center;
  }
  ::before,::after{
    content:"";
    position:absolute;
  }
  .container{
    width:100px;
    height:190px;
    position:relative;
  }
  a,p,span,::before{
    position:absolute;
    left:50%;
    transform:translateX(-50%);
  }
  .hat{
    width:40px;
    height:45px;
    background:linear-gradient(to bottom,#0E1F2B 34%,#FFFFFF 34% 56%,#0E1F2B 54%);
    bottom:129px;
  }
  .hat-bottom{
    bottom:0;
    width:150%;
    height:5px;
    background:#0E1F2B;
  }
  .head{
    border-radius:50%;
    width:60px;
    height:60px;
    background:#FFFFFF;
    bottom:90px;
  }
  .eyes{
    position:absolute;
    width:10px;
    height:10px;
    background:#0E1F2B;
    border-radius:50%;
    top:18px;
  }
  .eyes.left{
    left:15px;
  }
  .eyes.right{
    right:15px;
  }
  .scarf{
    width:60px;
    height:10px;
    background:#FFA63F;
    bottom:76px;
    border-radius:0;
    border-radius:10px;    
  }
  .scarf::before{
    width:120%;
    height:4px;
    background:#AC474B;
    bottom:-4px;
    box-shadow:0 -14px #AC474B
  }
  .body{
    width:100px;
    height:100px;
    background:#fff;
    border-radius:50%;
    bottom:0;
  }
</style>
```
