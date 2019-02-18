# Jquery-alert

1.Create an `index.html` file using text editor of your choice. 

2.In `index.html` file, create html document, if you are using sublime type html and tab or if you using visual studio code type html:5 and tab to complete document, or type everything like this.
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="styles.css">
    <title>Document</title>
</head>
<body>
   
</body>
</html>
```
3.Create a div, `<div></div>`( a place to hold other html tags,)

4.After div tag create another tag ; `<button></button>`.

In between the button opening and closing tag write anything you want like click me, button etc
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="styles.css">
    <title>Document</title>
</head>
<body>
   <div> 
    <button> click me </button>
   </div>
</body>
</html>
 
 ```
5.Download Jquery using ```npm install jquey``` from the downloaded jquery folder take jquery.min.js file and paste it in your project,import it in the index.html like this;

``` <script src="jquery.min.js"></script> ``` just before closing body tag.

OR use jquery CDN;

```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>

```

6.In the `style.css` file put any styles you want for your web page.

```

body{
   margin: 0; 
   
}
.alert{
    margin-top:30px;
    text-align: center;
    align-content: center;
    justify-items: center;
}
button{
    padding: 10px 30px;
    background-color:red;
    color:#fff;
    border-style: none;

}

```
