# 11 - Eye of Sauron

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/11.png)

## My Solution

```
<div class="hc l"></div>
<div class="m"></div>
<div class="hc r"></div>
<style>
  body{
    background:#191210;
    display:flex;
    justify-content:center;
    align-items:center;
  }
  .m{
    width:50px;
    height:50px;
    border:25px solid #191210;
    border-radius:50%;
    background: #84271C;
    top:50px;
    box-shadow: 0px 0px 0px 20px #ECA03D;
  }
  .hc{
	width: 60px;
    height: 30px;
    background:transparent;
    border:20px solid #ECA03D;
    top:50px;  
  }
  .l{
	border-radius:0px 0px 75px 75px;
	border-top:none;
    margin-top:50px;
  }
  .r{
	border-radius:75px 75px 0px 0px;
	border-bottom:none;
    margin-top:-50px;
  }
</style>
```
