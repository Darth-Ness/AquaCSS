# AquaCSS
A CSS framework that brings modern design to your website

# How to use

First download the latest release. . Then, move it to where your HTML code is.
AquaCSS has two main files. There is ```aquamain.css``` and ```aquacomp.css``` if you want to include some CSS code that styles your site and then forget it exists use ```aquamain.css``` 
If you want features such as componentes and Tailwind style shorthands then add ```aquacomp.css``` as well

Here as to do that: 

```HTML
<link rel="stylesheet" href="aquamain.css>
```
or
```HTML
<link rel="stylesheet" href="aquacomp.css>
```


# Custom Themes
There are some premade themes already (check the themes folder above) ,however, you can also make a custom theme as well.
Here is a template.
```CSS
:root {
--red:#bf616a;
--orange: #d08770;
--yellow: #ebcb8b;
--green: #a3be8c;
--blue1:#8fbcbb;
--blue2:#88c0d0;
--blue3:#81a1c1;
--blue4:#5e81ac;
--purple: #b48ead;
--default:#2e3440; 
--default2:#3b4252;
--default3:#434c5e; 
--bhover:#4c566a; 
--text:#eceff4;
}
```
Most of these names are self explanatory, but "bhover" is the color of the buttons when you hover over them. "text" is the text color.
You can also add styling for other elements in the same file.
The colors for these variables are the default values. 

# Docs
Docs for AquaCSS can be found [here](https://github.com/Darth-Ness/AquaCSS/wiki)
