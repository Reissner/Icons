
<!-- markdownlint-disable no-trailing-spaces -->
<!-- markdownlint-disable no-inline-html -->
# Icons

Offers icons for GUIs in a way that a missing icon file 
is detected at compile time rather than in runtime. 

Since this shall be open source, we restrict ourselves to the GIF format. 
Besides the GIF pictures, 
categorized by their location in a folder structure, 
there is a parallel structure of java classes in their packages. 
All these java classes extend the class 

```[sh]
eu.simuline.util.images.GifResource. 
```

In the long run, this project provides only those icons 
which are likely to be needed in any GUI, 
like those in the menus file, edit, help and so on. 

For an example of usage see 
[`testhelpers`](http://www.simuline.eu/TestHelpers/). 

Many icons are designed by Dean S. Jones, 
but I could not reach him to ask for allowance. 
Dean, if you read this, please contact me. 
