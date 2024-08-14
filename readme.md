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
 
>
##  CSS File

###  Code:

-  **Importing Google family font**
>
```css
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;600;700&display=swap');
```
>This line imports the Poppins font from Google Fonts. The **@import** rule is used to include external stylesheets. In this case, the stylesheet is hosted on Google Fonts and the font being imported is Poppins with different weights (300, 400, 500, 600). The **url() function** is used to specify the location of the external stylesheet. 
***

-  **Global styles using the _asterisc_ * selector**
>
```css
*{
}
```
> This selector targets all elements on the page and sets their margin, padding, and box-sizing properties.
***

-  **The _Body_ selector**
>
```css
body{
}
```
> Using the **body** element we created a full-screen background with a gradient that transitions from dark blue to dark blue-purple, and centring its content both horizontally and vertically using the flexbox layout.
***

-  **Code _section_ title 4**
>
```css
Put your code here exactly as it is.
```
> Use this text block to describe **relevant facts**, features or functions of your CSS code section that you consider will be useful in understanding **_how the style was applied_** and its relationship with the HTML code. You **highlight** some parts of this text to **improve its readability**.
***

-  **Code _section_ title 5**
>
```css
Put your code here exactly as it is.
```
> Use this text block to describe **relevant facts**, features or functions of your CSS code section that you consider will be useful in understanding **_how the style was applied_** and its relationship with the HTML code. You **highlight** some parts of this text to **improve its readability**.
***
 
-  **Code _section_ title 6(grouped)**
>
```css
Put your code here.
```
> Use this text block 1 to describe _relevant facts_.
>
```css
Put your code here.
```
> Use this text block 2 to describe _relevant facts_.
>
```css
Put your code here.
```
> Use this text block 3 to describe _relevant facts_.
>
```css
Put your code here.
```
> Use this text block 4 to describe _relevant facts_.
***

-  **Code _section_ title 7**
>
```css
Put your code here exactly as it is.
```
> Use this text block to describe **relevant facts**, features or functions of your CSS code section that you consider will be useful in understanding **_how the style was applied_** and its relationship with the HTML code. You **highlight** some parts of this text to **improve its readability**.
***

 
>
##  JS File

###  Code:

-  **Code _section_ title 6(grouped)**
>
```js
Put your code here.
```
> Use this text block 1 to describe _relevant facts_.
>
```js
Put your code here.
```
> Use this text block 2 to describe _relevant facts_.
>
```js
Put your code here.
```
> Use this text block 3 to describe _relevant facts_.
>


![reading...](https://media.giphy.com/media/Tf3mp01bfrrUc/giphy.gif?cid=ecf05e47wajghtrc5targr7mju7coe0avdyurnehrr1krgdt&ep=v1_gifs_search&rid=giphy.gif&ct=g  "...How could I ever do so unless someone guide me?")

***