# WaweCss

WaweCss is a new CSS Framework designed to provide a set of pre-defined styles and components for building modern and responsive websites and web applications.

## Usage

To use WaweCss in your HTML document, follow these steps:

1. Download the "wawe.css" file from the WaweCss website or repository. Or use with JsDelivr CDN Network.

````html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/2qke/WaweCss@main/wawe.css">
``````

2. Place the "wawe.css" file in the same directory as your HTML file if you downloaded it from the repo.

3. Make a sample button design with WaweCss using the sample code below.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/2qke/WaweCss@main/wawe.css">
    <title>WaweCss Example!</title>
</head>
<body class="bgr-white">
    <div class="flex flex-row">
        <button class="button-aqua radius-10 m-left-9">Button Example Aqua</button>
        <button class="button-orange radius-6 m-left-9">Button Example Orange</button>
        <button class="button-red radius-8 m-left-9">Button Example Red</button>
        <button class="bgr-gray radius-8 cp m-left-9">Button bgr-gray</button>
        <button class="cp default-button bgr-dark text-white radius-7 m-left-9">Default Button</button>
      </div>
</body>
</html>
```
# Result Aqua Button (Added as an example img)
<img src="https://cdn.discordapp.com/attachments/1133431801487040563/1137705560192598036/button-example-aqua.png">

# What will we add next?
> text-size, more text-color, more bg-color and some missing styles

### Navigation
<a href="#flex">#Flex</a><br>
<a href="#margin">#Margin</a><br>
<a href="#border">#Border</a><br>
<a href="#background-color">#Background-Color</a><br>
<a href="#text-color">#Text-Color</a><br>
<a href="#text-features">#Text Features</a><br>
<a href="#effect">#Effect</a><br>
<a href="#justify">#Justify</a><br>
<a href="#responsive">#Responsive</a><br>
<a href="#other">#Other Class</a><br>


# ClassList
Our main goal is for you to use it as multi-support. You can use it in some parts you don't like in libraries such as Bootstrap or TailwindCSS that you usually use. You can also use us as an option. We do not have such a large structure yet, but our goal is to modernize!

## Flex
`flex — display: flex;` | Classic display-flex structure<br>
`flex-col — flex: direction: column;` | Classic display-flex and flex-column structure<br>
`flex-row — flex: direction: row;` | Classic display-flex and flex-row structure<br>

## Margin
`mx-auto` | It ensures that the object is at a certain distance from the right and left.<br>
`m-left` — margin-left | Margin Left class has from 2 to 20 (use m-left-5 vb.)<br>
`m-right` — margin-right | Margin Right class has from 2 to 20 (use m-right-5 vb.)<br>

## Border
`border` — border-radius | Border Radius class has from 2 to 30 (use border-5 vb.)<br>

## Background Color
`bgr-dark — background-color: rgb(31, 33, 39);` | Background color dark<br>
`bgr-gray — background-color: rgb(101, 101, 109);` | Background color gray<br>
`bgr-white — background-color: rgb(231, 231, 231);` | Background color white<br>

## Text Color
`text-dark — color: rgb(41, 42, 44);` | Text color dark<br>
`text-gray — color: rgb(185, 185, 185);` | Text color gray<br>
`text-white — color: rgb(224, 224, 224);` | Text color white<br>

## Text Features
`text-center` | Centers the text.<br>
`item-center` | Used to center items on the vertical (horizontal) axis. <br>
`text-no-decoration` | It removes the lines under the links you are using. <br>
`list-no-decoration` | Removes objects such as dots, numbers or letters in the li classes you create. <br>
`hide-item` | Hides the object. <br>

## Effect
`white-effect` | Adds a white transition effect. (0.3s)<br>
`red-effect` | Adds a red transition effect. (0.3s)<br>
`orange-effect` | Adds a orange transition effect. (0.3s)<br>
`yellow-effect` | Adds a yellow transition effect. (0.3s)<br>

## Justify
`jcenter` | This style attribute is used to center the elements in the flex container horizontally (on the x-axis).<br>
`jend` | This style property aligns items inside the flex container horizontally (on the x-axis) to the right.<br>
`jright` | Aligns the contents of the flex container horizontally to the right.<br>
`jleft` | Aligns the contents of the flex container containing the class horizontally to the left.<br>
`jbetween` | This style property aligns elements in the flex container horizontally (on the x-axis) by spacing them apart.<br>

## Responsive
`responsive-button` — Makes the buttons mobile friendly.<br>

## Other
`cp — cursor: pointer;` | Classic cursor-pointer<br>

> Created by <a target="_blank" href="https://github.com/2qke">2qke</a><br>
> My web site: <a target="_blank" href="https://ebusoft.com.tr">ebusoft.com.tr</a>