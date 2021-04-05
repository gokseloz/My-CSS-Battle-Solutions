# 50 - Use Hand Sanitizer

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/50.png)

## My Solution

```
<div class="tank"></div>
<span class="cover"></span>
<span class="pump"></span>
<span class="press"></span>
<span class="exit"></span>
<style>
  body{margin:0;background:#1A4341;display:flex;justify-content:center;align-items:center;
}
  :before,:after{
    content:"";
    position:absolute;
  }
  body:before,body:after{
    width:20px;
    height:20px;
    background:#998235;
    top:100px;
    right:100;
    border-radius:50%;
  }
   body:after{
    top:130px;
    right:100;
  }
  .tank{
    margin-top:60px;
    width:100px;
    height:140px;
	background:#F3AC3C;
    border-radius:20px;
    position:relative;
    overflow:hidden;
  }
  .tank:before,.tank:after{
    width:50px;
    bottom:-30px;
    heighT:140px;
    border-radius:50px;
    background:#998235;
    box-shadow:50px 0 #998235;
  }
  .tank:after{
    width:50px;
    heighT:50px;
    background:#F3AC3C;
    right:0;
    top:30px;
  }
  .cover{
    position:absolute;
    width:50px;
    height:20px;
    background:#F3AC3C;
    top:90px;
    border-radius:10px 10px 0 0;
  }
  .pump{
    position:absolute;
    width:20px;
    height:30px;
    background:#F3AC3C;
    top:60px;
  }
  .press{
    position:absolute;
    width:150px;
    height:20px;
    background:#F3AC3C;
    top:50px;
    left:150px;
    border-radius:10px;
  }
  .exit{
    position:absolute;
    width:20px;
    height:40px;
    background:#F3AC3C;
    top:50px;
    left:280px;
    border-radius:10px;
  }
</style>
```
