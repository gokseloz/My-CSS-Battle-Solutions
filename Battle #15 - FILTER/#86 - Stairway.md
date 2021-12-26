# 86 - Stairway

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/86.png)

## My Solution

```
<div></div>
<style>
  body{background:#191919;display:grid;place-items:center}
  div {
	width:100px;
    height:150px;
    background-color:#4F77FF;
    border-radius:50px 50px 0 0;
    position:relative;
  }
  div::before{
    content:"";
    position:absolute;
    width:80%;
    height:20px;
    background:#191919;
    bottom:0;
    right:0;
    color:#191919;
    box-shadow:20px -24px, 40px -48px, 60px -72px;
  }
</style>
```
