# Fun with CSS

In this project, you will experiment and implement fun layout with HTML and CSS ONLY!  

Yes, no JavaScript!  

Enjoy!  

## Tasks

### 0. Sprite languages

By using this HTML:

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 0- Sprite</title>

        <link href="0-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <ul>
            <li>HTML<span class="icon i-html"></span></li>
            <li>CSS<span class="icon i-css"></span></li>
            <li>JavaScript<span class="icon i-js"></span></li>
        </ul>
    </body>
</html>
```

And this image file: [`0-sprite.png`](img/94aa60f76c412f40a87b.png)  
Create `0-styles.css` and generate this layout:

![image 0-styles.css](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/2/94aa60f76c412f40a87b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20210823%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20210823T195207Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=29af33c63e870681a6a00aa105bde8cd11ed451af6b5de4ddbfcfd59e4382326)  

You are not allowed to change the image and the HTML - sprite is cool!


----
### 1. Move the (under)line

By using this HTML:

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 1- Underline</title>

        <link href="1-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <h2>
            Hello <a href="https://www.holbertonschool.com">Holberton!</a>
        </h2>
    </body>
</html>
```

Create `1-styles.css` and generate this layout where the underline is hidden by default and appeared slowly…:

![image 1-styles.css](img/b791cfdbd11c0eefa5f7.gif)

You are not allowed to change the HTML

----
### 2. Toggle

By using this HTML:

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 2- toggle</title>

        <link href="2-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <div class="toggle">
            <input type="checkbox" name="toggle" class="toggle-cb" id="toggle-0" checked>
            <label class="toggle-label" for="toggle-0">
                <div class="toggle-inner"></div>
                <div class="toggle-switch"></div>
            </label>
        </div>
    </body>
</html>
```

Create `2-styles.css` and generate this layout where the `<input>` is has this custom toggle layout:

**Checked:**

![image](https://user-images.githubusercontent.com/54107524/130515159-99e87341-602a-4563-b9f7-31af9e580066.png)


**Unchecked:**

![image](https://user-images.githubusercontent.com/54107524/130515196-c0d13ca6-5153-471a-8df3-e21a9933bd66.png)

You are not allowed to change the HTML

----
### 3. Menu

By using this HTML:

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 2- toggle</title>

        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
        <link href="3-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>

        <nav class="menu">
            <input type="checkbox" href="#" class="menu-open" name="menu-open" id="menu-open"/>
            <label class="menu-open-button" for="menu-open">
                <span class="menu-line menu-line-1"></span>
                <span class="menu-line menu-line-2"></span>
                <span class="menu-line menu-line-3"></span>
            </label>

            <a href="#" class="menu-item"> <i class="fa fa-area-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-bar-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-line-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-pie-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-table"></i> </a>
        </nav>

    </body>
</html>
```

Create `3-styles.css` and generate this layout/animation:

![image 3-styles.css](img/252a25667dc7c65fe0e9.gif)

You are not allowed to change the HTML
