# 77 - Notes

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/77.png)

## My Solution

```
<div></div>
<style>
  body{background:#191919;}
  :before,:after{
    content:"";
    position:absolute;
  }
  body:before{
    width:40px;
    height:10px;
    background: #FE5F55;
    right:55px;
    top:110px;
  }
  div {
    position:absolute;
    width: 10px;
    height: 100px;
    background: #FE5F55;
    left:95px;
    top:90px;
    color:#FE5F55;
    box-shadow:70px 0px, 140px 0px #A64942, 210px 0px;
  }
  div:before{
    width:50px;
    height:40px;
    border-radius:100% / 40px;
    background: #FE5F55;
    bottom:-20px;
    left:-40px;
    box-shadow:70px 0px, 140px 0px #A64942, 210px 0px;
  }
  div:after{
    width:40px;
    height:10px;
    background: #FE5F55;
    box-shadow:30px 0px, 140px 0px #A64942, 210px 0px;
  }
</style>
```
