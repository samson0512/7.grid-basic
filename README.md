# 7.grid-basic
## PROGRAM :
```
<!DOCTYPE html>
<html>
  <head>
    <title>grid area</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
      <div class="content">
      <div class="item1">header</div>
      <div class="item2">sidebar</div>
      <div class="item3">main-content</div>
      <div class="item4">footer</div>
      </div>
  </body>
</html>
body{
  padding:0;
  margin:0;
  font-family:Arial;
}
.content{
  box-sizing:border-box;
  display:grid;
  grid-template-rows:1fr 3fr 1fr;
  grid-template-columns:2fr 2fr;
  gap:4px;
 
}
.item1{
  grid-area:1/1/2/3;
  background-color:#23f342;
  text-align:center;
  height:5vh;
}
.item2{
  grid-area: 2/1/3/2;
  background-color:#f0f0f0;
  
}
.item3{
  grid-area:2/2/3/3 ;
}
.item4{
  grid-area:3/1/4/3;
  background-color:#23f342;
  text-align:center;
}

```
## output:
![WhatsApp Image 2024-07-14 at 22 29 46_c96c6f85](https://github.com/user-attachments/assets/e8cc6d6c-586b-41d1-a35e-db9d3d675075)
