# Target 14 - Web Maker Logo

2021/03/22

![Target](https://cssbattle.dev/targets/14.png)

## 100% - 415 / 115

```css
<p style="border-top:130px solid #FD4602;margin-left:-90px">
<p style="border-top:130px solid #FF6D00;margin-left:-130px">
<p style="border-bottom:130px solid #FF6D00;margin-left:130px">
<p style="border-bottom:130px solid #FD4602;margin-left:90px">
<style>body{background:#F2F2B6;display:flex;justify-content:center;align-items:center}p{position:absolute;border-left:75px solid #0000;border-right:75px solid #0000}
```

## Expanded

```css
<p style="border-top:130px solid #FD4602;margin-left:-90px">
<p style="border-top:130px solid #FF6D00;margin-left:-130px">
<p style="border-bottom:130px solid #FF6D00;margin-left:130px">
<p style="border-bottom:130px solid #FD4602;margin-left:90px">

<style>
body{
    background:#F2F2B6;
    display:flex;
    justify-content:center;
    align-items:center
}
p{
    position:absolute;
    border-left:75px solid #0000;
    border-right:75px solid #0000
}
```

## Original Answers

```css
<p>
<p>
<p>
<p>


<style>
body{
    background:#F2F2B6;
    display:flex;
    justify-content:center;
    align-items:center
}
p{
    position:absolute;
    border-left: 75px solid #0000;
    border-right: 75px solid #0000;
}  
  
  
p:nth-child(1){
    border-top: 130px solid #FD4602;
    margin-left:-90px;
}  
p:nth-child(2){
    border-top: 130px solid #FF6D00;
    margin-left:-130px
} 
  
p:nth-child(3){
    border-bottom: 130px solid #FF6D00;
    margin-left:130px;
}
p:nth-child(4){
    border-bottom: 130px solid #FD4602;
    margin-left:90px;
}
```
