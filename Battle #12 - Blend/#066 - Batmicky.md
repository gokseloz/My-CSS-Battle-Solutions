# 66 - Batmicky

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/66.png)

## My Solution

```
<div></div>
<span></span>
<span></span>
<style>
  body{background:#191919}
  div{
    width:240px;
    height:80px;
    position:absolute;
    background:#F2AD43;
    top:100px;
    left:80px;
  }
  div:before{
    content:"";
    position:absolute;
    width:80px;
    height:30px;
    background:radial-gradient(circle at 37.5% 33%, #F2AD43 0 9%, transparent 0%),radial-gradient(circle at 62.5% 33%, #F2AD43 0 9%, #191919 0%);
    left:80px;
    border-radius:0 0 10px 10px;
  }
  div:after{
    content:"";
    position:absolute;
    top:10px;
    width:20px;
    height:30px;
    background:#F2AD43;
    left:110px;
    border-radius:5px
  }
  span{
    position:absolute;
    width:100px;
    height:100px;
    border-radius:50%;
    background:#191919;
    top:100px;
    left:25px;
    box-shadow:250px 0 #191919
  }
  span:nth-of-type(2){
	width:200px;
    height:200px;
    top:160px;
    left:40px;
    box-shadow:120px 0 #191919
  }
</style>
```
