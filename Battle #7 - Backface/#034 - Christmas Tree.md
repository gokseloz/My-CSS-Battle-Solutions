# 34 - Christmas Tree

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/34.png)

## My Solution

```
<div></div>
<div></div>
<div></div>
<style>
  body{background:#007065}
  div {
    position:absolute;
    left:75px;
    top:50px;
    border-style:solid;
    border-width:0 125px 100px 125px;
    border-color:0 transparent #FFEECF transparent;
  }
  div:nth-of-type(2){
    top:100px;
    border-bottom-color:#F5C181;
    z-index:-1
  }
   div:nth-of-type(3){
    top:150px;
    border-bottom-color:#00A79D;
    z-index:-2;
  }
</style>

```
