# bootstrap-5-tutorial

## What is Bootstrap?
- Bootstrap is a free front-end framework for faster and easier web development
- Bootstrap includes HTML and CSS based design templates for typography, forms, buttons, tables, navigation, modals, image carousels and many other, as well as optional JavaScript plugins
- Bootstrap also gives you the ability to easily create responsive designs

## Where to Get Bootstrap 5?
There are two ways to start using Bootstrap 5 on your own web site.
1. Include Bootstrap 5 from a CDN
2. Download Bootstrap 5 from getbootstrap.com

### 1.Bootstrap 5 CDN:
jsDelivr provides CDN support for Bootstrap's CSS and JavaScript:
``` html
<!-- Latest compiled and minified CSS -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet">

<!-- Latest compiled JavaScript -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js"></script>
```

### 2.Downloading Bootstrap 5:
For downloading bootstrap 5, go to https://getbootstrap.com/, and follow the instructions there.

## Basic Bootstrap 5 Page:
``` html
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Bootstrap Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>

<div class="container">
  <h1>My First Bootstrap Page</h1>
  <p>This part is inside a .container class.</p>
  <p>The .container class provides a responsive fixed width container.</p>
</div>

</body>
</html>
```

## Features of Bootstrap:
### 1. Bootstrap Containers:
+ Containers are used to pad the content inside of them, and there are two container classes available
1. The .container class provides a responsive fixed width container
``` html
        <div class="container">
          <h1>My First Bootstrap Page</h1>
          <p>This is some text.</p>
        </div>
```
2. The .container-fluid class provides a full width container, spanning the entire width of the viewport
``` html
        <div class="container-fluid">
          <h1>My First Bootstrap Page</h1>
          <p>This is some text.</p>
        </div>
```

+ By default, containers have left and right padding, with no top or bottom padding, margins,borders and colors.
``` html
    <div class="container p-5 my-5 bg-primary text-white">
      <h1>My First Bootstrap Page</h1>
      <p>This container has a blue background color and a white text, and some extra padding and margins.</p>
    </div> 
```

<img src="https://user-images.githubusercontent.com/70798723/210711942-90ce9d14-01c2-4531-9def-5d762ca409c3.png" width="800" height="200">


### Bootstrap Grid System:
Bootstrap's grid system is built with flexbox and allows up to 12 columns across the page.
#### Grid Classes:
+ col- (screen width less than 576px)
+ col-sm- (>=576px)
+ col-md- (>=768px)
+ col-lg- (>=992px)
+ col-xl- (>=1200px)
+ col-xxl-(>=1400px)
#### Basic Structure of a Bootstrap 5 Grid:
``` html
<div class="row">
    <div class="col p-3 bg-dark text-white">1</div>
    <div class="col p-3 bg-secondary text-white">2</div>
    <div class="col p-3 bg-dark text-white">3</div>
  </div>
```
![image](https://user-images.githubusercontent.com/70798723/210713742-12314e4f-3fa2-491d-8b96-3afe247bbb3b.png)



+ Bootstrap Typography:
+ Bootstrap Tables
+ Bootstrap Lists
+ Bootstrap List Groups
+ Bootstrap Forms
+ Bootstrap Custom Forms
+ Bootstrap Input Groups
+ Bootstrap Buttons
+ Bootstrap Button Groups
+ Bootstrap Images
+ Bootstrap Cards
+ Bootstrap Media Objects
+ Bootstrap Icons
+ Bootstrap Navs
+ Bootstrap Navbar
+ Bootstrap Accordion
+ Bootstrap Breadcrumbs
+ Bootstrap Pagination
+ Bootstrap Badges
+ Bootstrap Progress Bars
+ Bootstrap Spinners
+ Bootstrap Jumbotron
+ Bootstrap Helper Classes
