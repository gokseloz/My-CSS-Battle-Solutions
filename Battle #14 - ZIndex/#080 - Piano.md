# 80 - Piano

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/80.png)

## My Solution

```
<div></div>
<style>
  body{background:#998235;display:flex;justify-content:center;align-items:center}
  :before,:after{
    content:"";
    position:absolute;
  }
  div{
    width:180px;
    height:100px;
    background:#191919;
    border-radius:10px;
    position:relative;
  }
  div:before{
    width:20px;
    height:70%;
    background:#FFFFFF;
    bottom:5px;
    left:5px;
    border-radius:5px;
    color:#ffffff;
    box-shadow:25px 0, 50px 0, 75px 0, 100px 0, 125px 0, 150px 0;
  }
  div:after{
    width:15px;
    height:50%;
    background:#191919;
    top:10px;
    left:20px;
    color:#191919;
    box-shadow:25px 0, 75px 0, 100px 0, 125px 0;
  }
</style>
```
