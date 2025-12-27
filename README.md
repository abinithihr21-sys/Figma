# Ex08 Event Registration Web Application
## Date:

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:
```
page1

index.html


<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="val" src="img/val-1.png" />
      <img class="whatsapp-image" src="img/whatsapp-image-2025-12-27-at-9-13-39-AM-1.png" />
      <img class="SEC-logo" src="img/SEC-logo-1-1.png" />
      <div class="rectangle"></div>
      <div class="div"></div>
      <div class="text-wrapper">LOGIN</div>
      <div class="text-wrapper-2">username</div>
      <div class="text-wrapper-3">Password</div>
    </div>
  </body>
</html>

globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}

button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.iphone-pro-max {
  background-color: #ffffff;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .val {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 956px;
  aspect-ratio: 0.56;
}

.iphone-pro-max .whatsapp-image {
  position: absolute;
  top: 0;
  left: 0;
  width: 439px;
  height: 88px;
  aspect-ratio: 4.97;
  object-fit: cover;
}

.iphone-pro-max .SEC-logo {
  position: absolute;
  top: 235px;
  left: 106px;
  width: 227px;
  height: 219px;
  aspect-ratio: 1.04;
  object-fit: cover;
}

.iphone-pro-max .rectangle {
  top: 631px;
  position: absolute;
  left: 15px;
  width: 409px;
  height: 67px;
  background-color: #d9d9d9;
}

.iphone-pro-max .div {
  top: 725px;
  position: absolute;
  left: 15px;
  width: 409px;
  height: 67px;
  background-color: #d9d9d9;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 543px;
  left: 24px;
  width: 194px;
  font-family: "Indie Flower-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 631px;
  left: 58px;
  width: 207px;
  font-family: "Indie Flower-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 722px;
  left: 63px;
  font-family: "Indie Flower-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

page-2

index.html

<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="img" src="img/img-1.png" />
      <div class="text-wrapper">Fun games</div>
      <img class="whatsapp-image" src="img/whatsapp-image-2025-12-27-at-9-13-39-AM-2.png" />
      <div class="ellipse"></div>
      <div class="div"></div>
      <div class="ellipse-2"></div>
      <div class="ellipse-3"></div>
      <div class="ellipse-4"></div>
      <div class="text-wrapper-2">friendship tower</div>
      <div class="text-wrapper-3">pocky</div>
      <div class="text-wrapper-4">limbo contest</div>
      <div class="text-wrapper-5">buzz bomb balloon</div>
      <div class="text-wrapper-6">word building</div>
    </div>
  </body>
</html>

globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.iphone-pro-max {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .img {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 956px;
  aspect-ratio: 0.56;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 108px;
  left: 27px;
  font-family: "Indie Flower-Regular", Helvetica;
  font-weight: 400;
  color: #611c5e;
  font-size: 80px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .whatsapp-image {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 88px;
  aspect-ratio: 4.97;
  object-fit: cover;
}

.iphone-pro-max .ellipse {
  top: 245px;
  left: 3px;
  position: absolute;
  width: 433px;
  height: 99px;
  background-color: #dc9191;
  border-radius: 216.5px / 49.5px;
}

.iphone-pro-max .div {
  top: 365px;
  left: 3px;
  position: absolute;
  width: 433px;
  height: 99px;
  background-color: #dc9191;
  border-radius: 216.5px / 49.5px;
}

.iphone-pro-max .ellipse-2 {
  top: 485px;
  left: 0;
  position: absolute;
  width: 433px;
  height: 99px;
  background-color: #dc9191;
  border-radius: 216.5px / 49.5px;
}

.iphone-pro-max .ellipse-3 {
  top: 725px;
  left: 3px;
  position: absolute;
  width: 433px;
  height: 99px;
  background-color: #dc9191;
  border-radius: 216.5px / 49.5px;
}

.iphone-pro-max .ellipse-4 {
  top: 605px;
  left: 3px;
  position: absolute;
  width: 433px;
  height: 99px;
  background-color: #dc9191;
  border-radius: 216.5px / 49.5px;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 263px;
  left: 58px;
  width: 433px;
  font-family: "Indie Flower-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 360px;
  left: 139px;
  font-family: "Indie Flower-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 500px;
  left: 87px;
  font-family: "Indie Flower-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-5 {
  position: absolute;
  top: 620px;
  left: 34px;
  font-family: "Indie Flower-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-6 {
  position: absolute;
  top: 731px;
  left: 71px;
  font-family: "Indie Flower-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 55px;
  letter-spacing: 0;
  line-height: normal;
}

page-3

index.html
 

<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="img" src="img/img2-1.png" />
      <div class="text-wrapper">THANK YOU!</div>
      <img class="sec-logo" src="img/sec-logo-01as-1-2.png" />
      <img class="fig" src="img/fig-1.png" />
    </div>
  </body>
</html>

globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

styles.css

.iphone-pro-max {
  background-color: #ffffff;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .img {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 956px;
  aspect-ratio: 0.56;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 807px;
  left: 70px;
  font-family: "Inika-Regular", Helvetica;
  font-weight: 400;
  color: #cb484a;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .sec-logo {
  position: absolute;
  top: 12px;
  left: 0;
  width: 440px;
  height: 89px;
  aspect-ratio: 4.97;
  object-fit: cover;
}

.iphone-pro-max .fig {
  position: absolute;
  top: 170px;
  left: 20px;
  width: 400px;
  height: 252px;
  aspect-ratio: 1.59;
}

page-4

index.html

<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="tku" src="img/tku-1.png" />
      <div class="EVENT-REGISTRATION">EVENT REGISTRATION<br />FORM</div>
      <div class="rectangle"></div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <img class="img" src="img/rectangle-9.svg" />
      <div class="rectangle-6"></div>
      <div class="text-wrapper">NAME</div>
      <div class="text-wrapper-2">Email ID</div>
      <div class="text-wrapper-3">Dept</div>
      <div class="register-no">Register no.</div>
      <div class="text-wrapper-4">GENDER</div>
      <div class="text-wrapper-5">moblie no</div>
      <div class="text-wrapper-6">SUBMIT</div>
      <img class="sec-logo" src="img/sec-logo-01as-1-1.png" />
    </div>
  </body>
</html>

globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.iphone-pro-max {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .tku {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 956px;
  aspect-ratio: 0.56;
  object-fit: cover;
}

.iphone-pro-max .EVENT-REGISTRATION {
  position: absolute;
  top: 108px;
  left: 11px;
  width: 761px;
  font-family: "Jacques Francois Shadow-Regular", Helvetica;
  font-weight: 400;
  color: #131212;
  font-size: 30px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 208px;
  left: 49px;
  width: 343px;
  height: 71px;
  background-color: #d9d9d9;
}

.iphone-pro-max .div {
  position: absolute;
  top: 208px;
  left: 49px;
  width: 343px;
  height: 71px;
  background-color: #e69898;
}

.iphone-pro-max .rectangle-2 {
  position: absolute;
  top: 808px;
  left: 80px;
  width: 280px;
  height: 53px;
  background-color: #d9d9d9;
}

.iphone-pro-max .rectangle-3 {
  position: absolute;
  top: 708px;
  left: 48px;
  width: 343px;
  height: 71px;
  background-color: #e69898;
}

.iphone-pro-max .rectangle-4 {
  position: absolute;
  top: 608px;
  left: 49px;
  width: 343px;
  height: 71px;
  background-color: #e69898;
}

.iphone-pro-max .rectangle-5 {
  position: absolute;
  top: 508px;
  left: 49px;
  width: 343px;
  height: 71px;
  background-color: #e69898;
}

.iphone-pro-max .img {
  position: absolute;
  top: 408px;
  left: 49px;
  width: 343px;
  height: 71px;
}

.iphone-pro-max .rectangle-6 {
  position: absolute;
  top: 308px;
  left: 48px;
  width: 343px;
  height: 71px;
  background-color: #e69898;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 217px;
  left: 80px;
  width: 164px;
  font-family: "Jaro-Regular", Helvetica;
  font-weight: 400;
  color: #1e1e1e;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 719px;
  left: 80px;
  width: 164px;
  font-family: "Jaro-Regular", Helvetica;
  font-weight: 400;
  color: #1e1e1e;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 514px;
  left: 80px;
  width: 164px;
  font-family: "Jaro-Regular", Helvetica;
  font-weight: 400;
  color: #1e1e1e;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .register-no {
  position: absolute;
  top: 414px;
  left: 80px;
  width: 196px;
  font-family: "Jaro-Regular", Helvetica;
  font-weight: 400;
  color: #1e1e1e;
  font-size: 38px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 319px;
  left: 80px;
  width: 164px;
  font-family: "Jaro-Regular", Helvetica;
  font-weight: 400;
  color: #1e1e1e;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-5 {
  position: absolute;
  top: 618px;
  left: 81px;
  font-family: "Jaro-Regular", Helvetica;
  font-weight: 400;
  color: #161414;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-6 {
  position: absolute;
  top: 808px;
  left: 152px;
  font-family: "Jaro-Regular", Helvetica;
  font-weight: 400;
  color: #e80e61;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .sec-logo {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 95px;
  aspect-ratio: 4.97;
  object-fit: cover;
}



```


## OUTPUT:
![alt text](<Screenshot 2025-12-27 114605.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
