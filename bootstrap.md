 **Q-1 What are the advantages of Bootstrap?**
**Ans:**
     Open Source Community of Resources. There is a vast community of open-source developers who contribute regularly to Bootstrap. One of the most significant advantages of Bootstrap is its ease of use.

* Consistent Designs        
* Access to Support
* Fast Development        
* Responsive Business Actions with a Grid System
* Customizable Expansion
* Loaded JavaScript Components
* Easy to Integrate
* Community and Ecosystem
* Cross-browser Compatibility

<hr>

**Q-2 What is a Bootstrap Container, and how does it work?**
**Ans:**
Bootstrap Containers are the most basic layout element in Bootstrap. Bootstrap Containers are very essential and basic building blocks of bootstrap that wrap a page’s content. It’s responsible for setting and aligning content within it according to viewport or given device. Containers are defined within the container class (.container). 

 * <h5>Basically, there are three types of container classes available in bootstrap:</h5>

<h6> 1.Default-Container(container)</h6>
<h6> 2.Responsive-Container(along with sm, md, lg, xl, xxl)</h6>
<h6> 3.Fluid-Container(container-fluid)</h6>
 
<hr>

**Q-3 What are the default Bootstrap text settings?**
 **Ans:**
 Bootstrap's global default font-size is `14px`, with a line-height of `1.428`.

This is applied to the `<body>` element and all paragraphs `(<p>)`.

In addition, all `<p>` elements have a bottom margin that equals half their computed line-height `(10px by default)`.

<h4>Font Family:</h4>


* Default: A clean, modern font like Roboto or Helvetica Neue.
* Fallback: If the default font isn't available, it'll use a similar font like Arial.

<h4>Font Size:</h4>

* Base: The standard size for regular text.
* Headings: H1 is the largest, H6 is the smallest.

<h4>Font Weight:</h4>

* Normal: Regular text.
* Bold: Thicker, emphasized text.

<h4> Line Height:</h4>

* Default: The spacing between lines of text.
* Headings: Have slightly more spacing to make them easier to read.
<hr>

**Q-4 What do you know about the Bootstrap Grid System?**
**Ans:**
The Bootstrap 3 grid system has four tiers of classes: `xs (phones), sm (tablets), md (desktops), and lg (larger desktops)`. You can use nearly any combination of these classes to create more dynamic and flexible layouts.

* **The Bootstrap grid system has four classes:**
* xs (for phones - screens less than 768px wide)
* sm (for tablets - screens equal to or greater than 768px wide)
* md (for small laptops - screens equal to or greater than 992px wide)
* lg (for laptops and desktops - screens equal to or greater than 1200px wide)

**Q-5 What is the difference between Bootstrap 4 and Bootstrap 5.**
**Ans:**

 No.| Bootstrap 4 | Bootstrap 5
 ---| ------------| ------------
  1 | Does not support the Offcanvas component |Adds support for the Offcanvas component, allowing for better navigation options
  2|  Lacks the ability to modify utilities | Allows developers to create and customize their own utility classes using Sass, enhancing customization options.
  3|Limited color options |  Expands the color palette with additional colors and shades, enhancing design flexibility.
  4|  Utilizes a 5-tier grid system (xs, sm, md, lg, xl).| Expands to a 6-tier grid system by adding an xxl tier for better responsiveness on larger displays

**Q-6 What is a Button Group, and what is the class for a basic Button Group?**
**Ans:**
“Button Groups” in Bootstrap is a class of name “btn-group” which is used to create a series of buttons in groups (without spaces) vertically or horizontally.

* **Adding Styles on Buttons:** 
Bootstrap allows you to add styles to your buttons using the following classes:

* .btn-default
* .btn-primary
* .btn-success
* .btn-info
* .btn-warning
* .btn-danger
* .btn-link


* **Example:**
```html
  <html>
    <head>
      <title>web page</title>
      <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
     rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" 
     crossorigin="anonymous">
     <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

    </head>
  <body>
    <div class="btn-group">
        <button type="button" class="btn btn-danger">Click</button>
        <button type="button" class="btn btn-warning">Click</button>
        <button type="button" class="btn btn-success">Click</button>
    </div>
</body>
</html>
```
<hr> 

**Q-7 How can you use Bootstrap to make thumbnails?**
**Ans:**
Bootstrap helps web developers to create thumbnails that are used to show linked images in grids with the pre-defined classes which help to reduce codes length. Thumbnails are created to provide a quick preview of images with small images.Bootstrap has an easy way to do this with thumbnails.
* **Example**
```html
<html>
<head>
<style> 
        .thumb-container { 
            width: 300px; 
            height: 180px; 
            overflow: hidden; 
            padding: 5px; 
            border: 1px solid #e1e1e1; 
            border-radius: 8px; 
            margin: 20px; 
        } 
       .thumb-image { 
            width: 100%; 
            height: 100%; 
            object-fit: cover; 
            border-radius: 5px; 
        } 
      .thumb-image:hover { 
            scale: 1.02; 
            cursor: pointer; 
        } 
      .thumb-container:hover { 
            box-shadow: 0 0 2px 1px rgba(0, 140, 186, 0.5); 
        } 
    </style> 
</head> 
  
<body> 
    <div class="thumb-container"> 
        <img class="thumb-image" src= 
"https://media.geeksforgeeks.org/wp-content/uploads/20230427130955/CSS-Tutorial.webp"
            alt="Thumbnail Image"> 
    </div> 
</body> 
  
</html>
```
<hr>

**Q-8 In Bootstrap 4, what is flexbox?**

**Ans:**
* The Flexible Box Layout Module, makes it easier to design flexible responsive layout structure without using float or positioning.

* <h6> Use .flex-row to display the flex items horizontally (side by side). This is default.

* **Example:** 
```html
<html>
<head>
  <title></title>
 <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
     rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" 
     crossorigin="anonymous">
     <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
</head>

<body>
<div class="d-flex flex-row bg-secondary">
  <div class="p-2 bg-info">Flex item 1</div>
  <div class="p-2 bg-warning">Flex item 2</div>
  <div class="p-2 bg-primary">Flex item 3</div>
</div>
</body>
</html>
```
* <h6> Use .flex-column to display the flex items vertically (on top of each other), or .flex-column-reverse to reverse the vertical direction

* **Example:**
```html
<html>
<head>
  <title></title>

 <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
     rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" 
     crossorigin="anonymous">
     <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
</head>

<body>
<div class="d-flex flex-column">
  <div class="p-2 bg-info">Flex item 1</div>
  <div class="p-2 bg-warning">Flex item 2</div>
  <div class="p-2 bg-primary">Flex item 3</div>
</div>
</body>
</html>
```
<hr>

**Q-9 How can one create an alert in Bootstrap?**
**Ans:**
Bootstrap provides an easy way to create predefined alert messages:

Alerts are created with the .alert class, followed by one of the four contextual classes `.alert-success, .alert-info, .alert-warning or .alert-danger.`
* **Example:**
```html
<html>
<head>
<title>webpage</title>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
     rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" 
     crossorigin="anonymous">
</head>
<body>
<div class="alert alert-success">
  <strong>Success!</strong> Indicates a successful or positive action.
</div>

<div class="alert alert-info">
  <strong>Info!</strong> Indicates a neutral informative change or action.
</div>

<div class="alert alert-warning">
  <strong>Warning!</strong> Indicates a warning that might need attention.
</div>

<div class="alert alert-danger">
  <strong>Danger!</strong> Indicates a dangerous or potentially negative action.
</div>
</body>
</html>
```
<hr>

* **Q-10 What is a bootstrap card and how would you create one?**
**Ans:**
A card is a flexible and extensible content container. It includes options for headers and footers, a wide variety of content, contextual background colors, and powerful display options. If you’re familiar with Bootstrap 3, cards replace our old panels, wells, and thumbnails. Similar functionality to those components is available as modifier classes for cards.

<h2>card :) </h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" 
crossorigin="anonymous">
<link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
</head>

<body>
    <div class="card d-flex align-canter mx-auto top-50 border-2  border-secondary" style="width: 18rem;">
        <img src="https://t3.ftcdn.net/jpg/07/17/33/40/360_F_717334058_zZu41aMmrR0CvBxI3WLbWRjrqFyLAdW1.jpg " class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title"> Cat </h5>
          <p class="card-text">3 hours ago</p>
          <button type="button" class="btn btn-primary position-relative w-25 rounded-3">
            like<span class="position-absolute top-0 start-100 translate-middle badge rounded-pill text-bg-secondary">+99 <span class="visually-hidden">unread messages</span></span>
          </button>
          </div>
      </div>
</body>
</html>
```