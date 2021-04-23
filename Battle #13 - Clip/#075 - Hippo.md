# 75 - Hippo

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/75.png)

## My Solution

```
<p></p>
<p></p>
<div></div>
<span></span>
<style>
  body{margin:0;background:#191919}
  *,:before,:after{
    position:absolute;
  }
  :before,:after{
    content:"";
  }
  p{
    width:10px;
    height:20px;
    background:#000000;
    border:5px solid #FE5F55;
    border-radius:50%;
    left:150px;
    top:54px;
    transform:rotate(-45deg)
  }
  p:nth-of-type(2){
    left:230px;
    transform:rotate(45deg)
  }
  div{
    width:130px;
    heighT:130px;
    background:#FE5F55;
    left:135px;
    top:75px;
    border-radius:60px 60px 0 0;
  }
  div:before,div:after{
    width:10px;
    height:10px;
    border-radius:50%;
    background:#000000;
    top:50px;
    left:25px;
  }
  div:after{
 	left:95px;
  }
  span{
    width:150px;
    height:100px;
    background:#A64942;
    border-radius:75px 75px 60px 60px;
    top:145px;
    left:125px;
  }
  span:before,span:after{
    width:30px;
    height:20px;
    background:#000000;
    left:20px;
    top:25px;
    border-radius:50%;
    transform:rotate(-45deg)
  }
  span:after{
    left:100px;
    transform:rotate(45deg)
  }
</style>
```
