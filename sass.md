1. What is Sass?
    - Syntactically Awesome StyleSheets
    - Css PreProcessor/Extension
    - Let's you features that do not exist in CSS
    - Sass(.scss) files are compiled to regular CSS

# Can have variables:
- Variables are declared using the $ , then later can be reused.

Ex:
```scss
$font-stack: Helvetica, sans-serif;
$primary-color: #333;

body{
    font: 100% $font-stack
    color: $primary-color
}
```

# Nesting;
- Instead of repeating nav ul{}, nav li{}, nav a{}
 
- nav{
    ul{

    }
    li{

    }
    a{

    }
}

@function 

@mixin

@each
//A loop


# making it responsive inside scss:
Create parcel _mobile.scss
// Anything smaller than 700 px
@media(max-width: 700px){

}