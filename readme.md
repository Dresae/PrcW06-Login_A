# Modern Animated Login Form

Lets create a complete Login form design with Login, Sign up animations and basic JS events. We'll be using CSS Flexbox and CSS transition for some animation effects.

## Branches dev1, dev2, dev3 and Joint
These Branches contain the same changes and look as follow:
>
![screenshot](pics/screenshot1.png)

## Branch Testing
Some errors related to the toggle section and responsiveness of the utility were fixed in this branch:
>
![screenshot](pics/screenshot2.png)

## Branches QA and Main
There will be always an opportunity to improve the final outcome by applying different styles as happened in these two merged branches making its appearance more engaging:
>
![screenshot](pics/screenshot3.png)

  

#  Code analysis

##  HTML File

###  Summary:
The login form structured in this practice is composed mainly of three  containers classes; one of them is a simple **sign in form** with some required fields for the user to get into the web resource, the second one is a **form** too, but **for registration**, which follows a similar structure  with just one more field for the name input. The third grouped element or container is a **big toggle** that was placed on top of the other two containers that **give the sense of being an animated slider**.

###  Code:
We start by defining a main div tag with the class _**container**_ under which all the elements will be placed.

As mentioned in the summary we continue by defining the classes **_form-container sign-up_**, **_form-container sign-in_** and the **_toggle-container_**  one.

- **_form-container sign-up_**
> Inside this container from top to down we placed first a title using the 	**_h1_** tag, a group  of social media icons encapsulated in the **_social-icons_** div class, a text for registration using the **_span_** tag, three **_input_** fields and lastly a **_button_** tag for the sign up action.
> 
- **_form-container sign-in_**
>This container follows a similar structure of the previous one, but in this case we **_removed an input_** field and added a hyperlink using the **_href_** tag aimed to redirect the user toward other page that reestablish the password.
>
- **_toggle-container_**
> To recreate the animated effect we placed a big toggle in front of the forms with the class **_toggle_** which is divided itself in two parts, the **_toggle-panel toggle-left_** and the **_toggle-panel toggle-right_** classes, both of them following the same structure; a title using the **_h1_** tag, a brief text using the **_p_** tag and a **_button_** with same class **_hidden_** that will allows us to make some effects possible through the style code and the script.
 

##  CSS File

###  Code:

-  **Importing Google family font**
>
```css
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;600;700&display=swap');
```
>This line imports the Poppins font from Google Fonts. The **@import** rule is used to include external stylesheets. In this case, the stylesheet is hosted on Google Fonts and the font being imported is Poppins with different weights (300, 400, 500, 600). The **url() function** is used to specify the location of the external stylesheet. 
***
***
-  **Global styles using the _asterisc_ * selector**
>
```css
*{
}
```
> This selector targets all elements on the page and sets their margin, padding, and box-sizing properties.
***
***
-  **The _Body_ selector**
```css
body{
}
```
> Using the **body** element we created a full-screen background with a gradient that transitions from dark blue to dark blue-purple, and centring its content both horizontally and vertically using the flexbox layout.
***
 ***
-  **Styling elements inside the main container**
```css
.container{
}
```
> This code styles the main container element with a white background, rounded corners, a drop shadow, and a fixed width and minimum height. The element will also clip any overflowing content and will not exceed the width of its parent element.
***
```css
.container h1{
}
```
> By using the **_h1_** tag, all the titles inside the main container class will get this style applied.
***
```css
.container p{
}
```
> Similarly by using the **_p_** tag, all the paragraph elements inside the main container class will get this style applied.
***
```css
.container span{
}
```
> This tag selector targets any HTML  _**span**_ elements that are descendants of the elements with the class _**container**_. This is useful you want to apply a different font style to a specific section of text.
***
```css
.container a{
}
```
> This CSS rule styles anchor elements within an element with the class _**container**_ to have a dark gray color, a font size of 13 pixels, no text decoration, and a margin of 15 pixels on top, 0 pixels on the sides, and 10 pixels on the bottom.
***
```css
.container button{
}
```
> This selector styles buttons inside the class _**container**_. It sets the button's background color, text color, font size, padding, border, and other visual properties to create a specific design. The _**cursor: pointer**_ property changes the mouse cursor to a pointing hand when hovering over the button, indicating it's a clickable element.
***
```css
.container button.hidden{
}
```
> Here we target the button element with the _**hidden**_ class, which inside the main _**container**_ class. It sets the button's background color to transparent and its border color to white (#fff), effectively giving the invisible effect to our button.
***
```css
.container form{
}
```
> Here we style the _**form**_ element within the _**main container**_. It sets the form's background color to white (#fff), centers its content both horizontally and vertically using _**flexbox**_, and adds _**padding**_ to the left and right sides taking up the full height of its _**parent container**_.
***
```css
container input{
}
```
> Use this text block 4 to describe _relevant facts_.
***
***
-  **Styling the form**
```css
.form-container{
}
```
> Use this text block 4 to describe _relevant facts_.
***
```css
.form-container form h1{
}
```
> Use this text block 4 to describe _relevant facts_.
***
***
-  **Styling the sign-in and sign-up**
>
```css
.sign-in{
}
```
> Use this text block 4 to describe _relevant facts_.
***
>
```css
.container.active .sign-in{
}
```
> Use this text block 4 to describe _relevant facts_.
***
>
```css
.sign-up{
}
```
> Use this text block 4 to describe _relevant facts_.
***
>
```css
.container.active .sign-up{
}
```
> Use this text block 4 to describe _relevant facts_.
***
>
```css
@keyframes move{
}
```
> Use this text block 4 to describe _relevant facts_.
***
***
-  **Styling the social media icons**
>
```css
.social-icons{
}
```
> Use this text block 1 to describe _relevant facts_.
>
***
>
```css
social-icons a{
}
```
> Use this text block 1 to describe _relevant facts_.
>
***
>
```css
.social-icons .icon{
}
```
> Use this text block 1 to describe _relevant facts_.
>
***
>
```css
.social-icons .icon .fa-brands{
}
```
> Use this text block 1 to describe _relevant facts_.
***
***
-  **Applying CSS effects to our Toggle**
```css
.toggle-panel{
}
```
> Use this text block 4 to describe _relevant facts_.
***
```css
.toggle-left{
}
```
> Use this text block 4 to describe _relevant facts_.
***
```css
.container.active .toggle-left{
}
```
> Use this text block 4 to describe _relevant facts_.
***
```css
toggle-right{
}
```
> Use this text block 4 to describe _relevant facts_.
***
```css
.container.active .toggle-right{
}
```
> Use this text block 4 to describe _relevant facts_.
***
***

##  JS File

###  Code:

- **Declaring constants**
>
```js
const container = document.getElementById('container');
const registerBtn = document.getElementById('register');
const loginBtn = document.getElementById('login');
```
> Use this text block 1 to describe _relevant facts_.
***
***
- **Defining actions on click events**
>
```js
registerBtn.addEventListener('click', () => {
    container.classList.add("active");
});
```
> Use this text block 1 to describe _relevant facts_.
>
```js
loginBtn.addEventListener('click', () => {
    container.classList.remove("active");
});
```
> Use this text block 1 to describe _relevant facts_.
***
***

![reading...](https://media.giphy.com/media/Tf3mp01bfrrUc/giphy.gif?cid=ecf05e47wajghtrc5targr7mju7coe0avdyurnehrr1krgdt&ep=v1_gifs_search&rid=giphy.gif&ct=g  "...How could I ever do so unless someone guide me?")

***