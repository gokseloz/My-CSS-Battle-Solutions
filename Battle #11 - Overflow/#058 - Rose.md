# 58 - Rose

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/58.png)

## My Solution

```
<div stick>
  <div stick head></div>
</div>
<span halfC></span>
<span f1></span>
<span f2></span>
<span f3></span>
<style>
  body{background:#191919}
  div,span{
    position:absolute;
    left:50%;
    transform:translateX(-50%);
  }
  span{
    background:#4F77FF;
  }
  [stick] {
    top:170px;
    left:50%;
    width: 20px;
    height: 85px;
    border-radius:25px;
    background: #F9E492;
  }
  [head]{
    top:-25;
    width:40px;
    height:40px;
    border-radius:50%;
    background: #F9E492;
  }
  [halfC]{
    top:65px;
    width:100px;
    height:100px;
    background:linear-gradient(transparent 60%, #4F77FF 0%);
    border-radius:50%
  }
  [f1]{
    top:85px;
    width:140px;
    height:30px;
    border-radius:7px 7px 35px 35px
  }
  [f2]{
    top:55px;
    width:100px;
    height:30px;
    border-radius:15px 15px 35px 35px;
	border:10px solid #191919;
  }
  [f3]{
    top:35px;
    border:10px solid #191919;
    width:30px;
    height:30px;
	border-radius:50%;
  }
</style>
```
