# Design-your-own-Grid-based-Framework

## HTML & CSS - Project 6

### Microverse

### Developer

**John Elvis Durán Montoya** [@jelduran](https://github.com/jelduran)

### Description

Building a grid-based framework (similar to bootstrap) that includes some basic functionality necessary to build a website. To do this we made use of the following HTML and CSS features:

1. Responsive.
2. Breakpoints for small, medium and big screens.
3. Grid system with gutters and font default values.

### How to use?

This simple framework has a small set of css classes to perform its task wich are described below:

**mesh** 
This is the container class for all other elements in framework, its width is 100% of the viewport.

**mesh-boxed** 
Is a version of 'mesh' class with a maximum width of 1100 px.

**tier** 
This class defines horizontal levels into the mesh.

**box-n** 
This class defines the most inner elements into the mesh, where 'n' is an integer number from 1 to 12 which is the width of box according to its parent width. For example `<div class="box-6">` is a div which is a [(parent width/12)*6] width.

**fillbox-n** 
This is a experimental feature of the framework to set the width of box elements inside of a 'tier' class element, where 'n' is an integer number from 1 to 12 which is the width of inner boxes according to its own width. For example `<div class="tier fillbox-3">` set children elements' width as if they were 'box-3' elements. This only works for 'div', 'header', 'section', 'article', 'aside' and 'footer' html elements into the 'tier' class element.

**center-box** 
This class is for centering a block element inside its parent.

## Project source can be downloaded from: <https://github.com/jelduran/Design-your-own-Grid-based-Framework>
  
## License & Copyright

John Elvis Durán, Student of Microverse.