# 69 - PushOwl

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/69.png)

## My Solution

```
<div></div>
<div></div>
<style>
  body{background:#191919};
  :before,:after{
    content:"";
    position:absolute;
  }
  div {
    width:114px;
    height:114px;
    border-radius:0 50% 50% 50%;
    position:absolute;
    left:79px;
    top:67px;
    border:10px solid #191919;
    background:radial-gradient(circle at center, #191919 0 56%, #E08027 0)
  }
  div:nth-of-type(2){
   border-radius:50% 0 50% 50%;
   left:187px;
   z-index:3;
  }
  div:before{
    width:12px;
    height:12px;
    border:9px solid #E08027;
    border-radius:50%;
    top:42.5%;
    left:50%;
    border-bottom-color:transparent;
    border-right-color:transparent;
    transform:translateX(-50%) rotate(45deg);
  }
  body:before{
    width:50px;
    height:50px;
    background:#E08027;
    transform:rotate(-45deg);
    top:162px;
    left:175px;
    z-index:2
  }
</style>
```
