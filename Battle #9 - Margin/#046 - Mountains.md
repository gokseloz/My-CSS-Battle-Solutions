# 46 - Mountains

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/46.png)

## My Solution

```
<div></div>
<style>
  body{margin:0;background:#293462;display:flex;justify-content:center;align-items:center;}
  div {
    width: 200px;
    height: 200px;
    border-radius:50%;
	background:#FFF1C1;
    position:relative;
    overflow:hidden;
  }
  div:before,div:after{
    content:"";
    position:absolute;
    width:200px;
    height:200px;
    background:#FE5F55;
    bottom:-170px;
    left:-70px;
    transform:rotate(45deg)
  }
  div:after{
    bottom:-100px;
    left:41px;
  }
</style>
```
