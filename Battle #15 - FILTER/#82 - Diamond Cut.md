# 82 - Diamond Cut

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/82.png)

## My Solution

```
<div></div>
<style>
  body{background:#F3AC3C;display:grid;place-items:center}
  ::before,::after{
    content:'';
    position:absolute;
    background:#F3AC3C;
  }
  div {
	width:30;
    height:30;
    background:#1A4341;
    transform:rotate(45deg);
    border:35px solid #F3AC3C;
    outline:30px solid #998235;
    position:relative;
    left:-2px
  }
  div::before{
    width:30;
    height:35;
    bottom:62;
  }
  div::after{
    width:35;
    height:30;
    right:62;
  }
</style>
```
