# 84 - Diamond Cut

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/84.png)

## My Solution

```
<style>
   body{background:#191919}
  ::before,::after{
    content:"";
    position:absolute;
    border-radius:40px;
  }
  body::before{
    width:50%;
    height:40px;
    background:#A64942;
    transform:translate(-28px,-50%);
    top:50%;
    box-shadow:240px 0 #A64942
  }
    body::after{
    width:40px;
    height:50%;
    background:#FE5F55;
    transform:translate(-50%,-28px);
    left:50%;
    box-shadow:0 190px #FE5F55
  }
</style>
```
