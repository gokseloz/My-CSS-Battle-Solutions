# 93 - Great Wall

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/93.png)

## My Solution

```
<div></div>
<style>
  body{background:#4F77FF;display:grid;place-items:center}
  ::before,::after{
    content:"";
    position:absolute;
  }
  div{
    width:200px;
    height:200px;
    border-radius:50%;
    background:radial-gradient(circle at 30% 30%, #F9E492 0 20px, #191919 0);
    position:relative;
    overflow:hidden;
  }
  div::before{
    width:50%;
   	height:16px;
    background:#F9E492;
    left:0;
    bottom:62;
    color:#F9E492;
    box-shadow:0 26px, 0 52px, 120px -13px, 120px 13px, 120px 39px
  }
  div::after{
    width:20px;
    height:16px;
    background:#D6B73F;
    bottom:68.5;
    left:100.0;
    transform:skewY(-33.2deg);
    color:#D6B73F;
    box-shadow:0 26px, 0 52px;
  }
</style>
```
