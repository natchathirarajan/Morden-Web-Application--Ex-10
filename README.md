# Exp-10-Create-a-Gliding-box-using-CSS-Animation
## Aim:
To write HTML & CSS code to create Gliding box using CSS Animation.
## Algorithm:
### Step 1:
Create a html code for the animation.
### Step 2:
Make gliding box for the Web Layout using seprate css file.
### Step 3:
Include Style in the html uing link tag.
### Step 4:
Verify the output by running the Web-Layout in any web browser. 
## Program:
### HTML:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Document</title>
</head>
<body>
    <div class="box"></div>
</body>
</html>
```
### CSS:
```css
.box {
    width: 100px;
    height: 100px;
    background-color: blue;
    position: relative;
    animation-name: glide;
    animation-duration: 2s;
    animation-iteration-count: infinite;
    animation-direction: alternate;
  }
  @keyframes glide {
    0% {
      left: 0;
    }
    100% {
      left: 200px;
    }
  }
```
## Output:
![image](https://github.com/Karthikeyan21001828/MERN_EX10/assets/93427303/8f12abbf-dd49-4369-be3c-2aed954938cc)

![image](https://github.com/Karthikeyan21001828/MERN_EX10/assets/93427303/487a21e7-1d05-41a1-85d2-b772868019c1)

## Result:
Thus the HTML & CSS code to create Gliding box using CSS Animation has been created and output has been verified.
