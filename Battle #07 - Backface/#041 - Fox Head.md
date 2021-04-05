# 41 - Fox Head

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/41.png)

## My Solution

```
<div></div>
<div></div>
<style>
  body{background:#293462;display:flex;justify-content:center;align-items:center}
  div {
    width:50px;
    height:140px;
    background-color:#FE5F55;
    border-radius:0 40px;
    position:relative;
  }
  div:before,div:after{
    content:"";
    position:absolute;
    background:#293462;
  }
  div:before{
    width:50px;
    height:40px;
    border-radius:0 50px 0 0;
	bottom:0;
  }
  div:after{
    width:30px;
    height:30px;
    left:14.5px;
    bottom:50px;
    border-radius:50%;
  }
  div:nth-of-type(2){
    border-radius:40px 0;
  }
  div:nth-of-type(2):before{
    border-radius:50px 0 0 0;
  }
  div:nth-of-type(2):after{
    left:5px;
  }
</style>
```
