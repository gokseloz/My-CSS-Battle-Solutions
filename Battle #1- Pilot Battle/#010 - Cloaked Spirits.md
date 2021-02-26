# 1ß - Cloaked Spirits

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/10.png)

## My Solution

```
<div></div>
<div></div>
<div></div>
<style>
  body{
    background-color:#62306D;
    display:flex;
    justify-content:center;
    align-items:flex-end;
    margin:0;
  }
  div{
    width:100px;
    height:100px;
    background-color:#F7EC7D;
    position:relative;
  }
  div:nth-child(2){
    height:200px
  }
  div:after{
    content:"";
    position:absolute;
    width:60px;
    height:60px;
    border-radius:50%;
    top:0;
    left:50%;
    transform:translate(-50%,-50%);
 	background-color:#E38F66;
    box-shadow:0 0 0 20px #AA445F;
  }
  div:nth-child(2):after{
    background-color:#AA445F;
    box-shadow:0 0 0 20px #E38F66;
  }
</style>
```
