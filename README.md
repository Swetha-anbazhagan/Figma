# Ex09 Event Registration Web Application
# Date:06/05/25
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:

```
Home.html

div class="container--0-">
  <img
    src=""logo.png"
    />
  <div class="text-0-1-1">TECH FESTO</div>
  <svg
    width="185"
    height="46"
    viewBox="0 0 185 46"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="185" height="46" fill="#D63FB5"></rect>
  </svg>
  <div class="text-0-1-3">LOGIN</div>
  <svg
    width="204"
    height="44"
    viewBox="0 0 204 44"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="204" height="44" fill="#D63FB5"></rect>
  </svg>
  <div class="text-0-1-5">REGISTER<br /></div>
  <div class="container-0-1-6"></div>
  <img
  src="home.png"
   />
</div>

Event.html

<div class="container--0-">
  <img
  src="back.png"
   width="281"
    height="65"
    viewBox="0 0 281 65"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="281" height="65" fill="#D63FB5"></rect>
  </svg>
  <div class="text-0-1-2">EVENTS</div>
  <svg
    width="336"
    height="540"
    viewBox="0 0 336 540"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="336" height="540" fill="#D63FB5"></rect>
  </svg>
  <div class="text-0-1-5">
    <br />Hack-o-Heist <br /><br />DesignDerby <br /><br />CyberKnights
    <br /><br />GameOn <br /><br />AppThon <br /><br />DevDetective<br />
  </div>
</div>

Form.html

<div class="container--0-">
  <img

  src="back1.png"/>
   /><svg
    width="336"
    height="36"
    viewBox="0 0 336 36"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="336" height="36" fill="white"></rect></svg
  ><svg
    width="330"
    height="58"
    viewBox="0 0 330 58"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="330" height="58" fill="#D63FB5"></rect>
  </svg>
  <div class="text-0-1-3">EVENT REGISTERATION FORM<br /></div>
  <svg
    width="336"
    height="27"
    viewBox="0 0 336 27"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="336" height="27" fill="white"></rect>
  </svg>
  <div class="text-0-1-5">FULL NAME</div>
  <svg
    width="336"
    height="31"
    viewBox="0 0 336 31"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="336" height="31" fill="#D9D9D9"></rect>
  </svg>
  <div class="text-0-1-7">GENDER<br /></div>
  <svg
    width="336"
    height="29"
    viewBox="0 0 336 29"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="336" height="29" fill="#D9D9D9"></rect>
  </svg>
  <div class="text-0-1-9">REGISTER NO<br /></div>
  <svg
    width="336"
    height="29"
    viewBox="0 0 336 29"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="336" height="29" fill="#D9D9D9"></rect>
  </svg>
  <div class="text-0-1-11">EVENT NAME</div>
  <svg
    width="336"
    height="28"
    viewBox="0 0 336 28"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="336" height="28" fill="#D9D9D9"></rect>
  </svg>
  <div class="text-0-1-13">DEPARTMENT<br /></div>
  <svg
    width="336"
    height="31"
    viewBox="0 0 336 31"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="336" height="31" fill="#D9D9D9"></rect>
  </svg>
  <div class="text-0-1-15">PHONE NO</div>
  <div class="text-0-1-16">EMAIL ID<br /></div>
  <svg
    width="251"
    height="53"
    viewBox="0 0 251 53"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="251" height="53" fill="#D63FB5"></rect>
  </svg>
  <div class="text-0-1-18">REGISTER</div>
</div>

End.html

div class="container--0-">
  <img
    src="back2.png"/>
    />
  <div class="text-0-1-1">
    Thank you for registering<br /><br /><br /><br />We’ll update you through
    email.<br />
  </div>
</div>

CSS code

Home.html

.container--0- {
  position: absolute;
  left: -21px;
  top: 96px;
  width: 379px;
  height: 908px;
  background-color: #ffffff;
  justify-content: start;
  align-items: start;
}
.text-0-1-1 {
  width: 302px;
  height: 98px;
  color: #d63fb5;
  font-size: 48px;
  font-family: Readex Pro, "Bold";
  font-weight: 700;
  text-align: center;
  vertical-align: top;
}
.text-0-1-3 {
  width: 143px;
  height: 46px;
  color: #ffffff;
  font-size: 32px;
  font-family: Readex Pro, "Bold";
  font-weight: 700;
  text-align: center;
  vertical-align: top;
}
.text-0-1-5 {
  width: 227px;
  height: 57px;
  color: #ffffff;
  font-size: 32px;
  font-family: Readex Pro, "Bold";
  font-weight: 700;
  text-align: center;
  vertical-align: top;
}
.container-0-1-6 {
  position: absolute;
  left: 325px;
  top: 856px;
  width: 50px;
  height: 1px;
  justify-content: start;
  align-items: start;
}

Event.html
.container--0- {
  position: absolute;
  left: 406px;
  top: 104px;
  width: 382px;
  height: 922px;
  background-color: #ffffff;
  justify-content: start;
  align-items: start;
}
.text-0-1-2 {
  width: 206px;
  height: 47px;
  color: #ffffff;
  font-size: 32px;
  font-family: Readex Pro, "Bold";
  font-weight: 700;
  text-align: center;
  vertical-align: top;
}
.text-0-1-5 {
  width: 260px;
  height: 501px;
  color: #ffffff;
  font-size: 32px;
  font-family: Readex Pro, "Bold";
  font-weight: 700;
  text-align: left;
  vertical-align: top;
}

Form.html

.container--0- {
  position: absolute;
  left: 835px;
  top: 87px;
  width: 391px;
  height: 939px;
  background-color: #ffffff;
  justify-content: start;
  align-items: start;
}
.text-0-1-3 {
  width: 284px;
  height: 66px;
  color: #ffffff;
  font-size: 22px;
  font-family: Readex Pro, "Bold";
  font-weight: 700;
  text-align: center;
  vertical-align: top;
}
.text-0-1-5 {
  width: 242px;
  height: 54px;
  color: #d63fb5;
  font-size: 22px;
  font-family: Readex Pro, "Bold";
  font-weight: 700;
  text-align: center;
  vertical-align: top;
}
.text-0-1-7 {
  width: 148px;
  height: 46px;
  color: #d63fb5;
  font-size: 22px;
  font-family: Readex Pro, "Bold";
  font-weight: 700;
  text-align: center;
  vertical-align: top;
}
.text-0-1-9 {
  width: 222px;
  height: 50px;
  color: #d63fb5;
  font-size: 22px;
  font-family: Readex Pro, "Bold";
  font-weight: 700;
  text-align: center;
  vertical-align: top;
}
.text-0-1-11 {
  width: 247px;
  height: 63px;
  color: #d63fb5;
  font-size: 22px;
  font-family: Readex Pro, "Bold";
  font-weight: 700;
  text-align: center;
  vertical-align: top;
}
.text-0-1-13 {
  width: 164px;
  height: 29px;
  color: #d63fb5;
  font-size: 22px;
  font-family: Readex Pro, "Bold";
  font-weight: 700;
  text-align: center;
  vertical-align: top;
}
.text-0-1-15 {
  width: 170px;
  height: 55px;
  color: #d63fb5;
  font-size: 22px;
  font-family: Readex Pro, "Bold";
  font-weight: 700;
  text-align: center;
  vertical-align: top;
}
.text-0-1-16 {
  width: 169px;
  height: 36px;
  color: #d63fb5;
  font-size: 22px;
  font-family: Readex Pro, "Bold";
  font-weight: 700;
  text-align: center;
  vertical-align: top;
}
.text-0-1-18 {
  width: 300px;
  height: 88px;
  color: #ffffff;
  font-size: 29px;
  font-family: Readex Pro, "Bold";
  font-weight: 700;
  text-align: center;
  vertical-align: top;
}

End.html
.container--0- {
  position: absolute;
  left: 1252px;
  top: 104px;
  width: 380px;
  height: 922px;
  background-color: #ffffff;
  justify-content: start;
  align-items: start;
}
.text-0-1-1 {
  width: 404px;
  height: 449px;
  color: #ffffff;
  font-size: 32px;
  font-family: Readex Pro, "Bold";
  font-weight: 700;
  text-align: center;
  vertical-align: top;
}

```

# OUTPUT:
![alt text](<Event Registration .png>)


# RESULT:

The program to design, develop and deploy a web application for event registration is completed successfully.
