# 76 - Beeee

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/76.png)

## My Solution

```
<span></span>
<span></span>
<div></div>
<style>
  body{margin:0;background:#998235}
  span{
    width:75px;
    height:75px;
    background:#FFFFFF;
    position:absolute;
    border-radius:50% 50% 0 50%;
    left:125px;
    top:75px;
  }
  span:nth-of-type(2){
    left:200px;
    transform:rotate(90deg);
  }
  div{
    width:150px;
    height:75px;
    background:#EFF33C;
    border-radius:75px;
    position:absolute;
    left:125px;
    top:150px;
    overflow:hidden;
  }
  :before,:after{
    content:"";
    position:absolute;
    background:#191919;

  }
  div:before{
    width:25px;
    height:100%;
    color:#191919;
    box-shadow:35px 0, 70px 0;
  }
  div:after{
    width:15px;
    height:15px;
    border-radius:50%;
    right:20px;
    top:20px;
  }
</style>
```
