# 59 - Earth

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/59.png)

## My Solution

```
<div>
<span></span>
 <span></span>
</div>
<style>
  body{background:#191919}
  div {
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%);
    width: 150px;
    height: 150px;
    border-radius:50%;
    background: #4F77FF;
  }
  div:before,div:after{
    content:"";
    position:absolute;
    right:-75;
    top:-30px;
    transform:translate(-50%);
    width:190px;
    height:190px;
    border-radius:50%;
    border:10px solid #191919;
  }
  div:after{
    right:-195;
  }
  span{
    position:absolute;
    top:30px;
    width:100%;
    height:10px;
    background:#191919;
    color:#191919;
    box-shadow:0 40px, 0 80px;
  }
  span:nth-of-type(2){
    background:#191919;
    transform:rotate(90deg);
    box-shadow:none;
    top:70;
  }
</style>
```
