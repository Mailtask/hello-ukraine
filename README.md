##Hello Ukraine

A simple html and JavaScript project.  

index.html:  

```html
<!DOCTYPE html><!--set up document type -->
<html> <!-- html tag open tag-->
    <!-- head tag contents common web-page settings -->
    <head> <!-- head open tag -->
         <!-- meta tag provides web-page common settings -->
         <meta charset="UTF-8"> <!-- charset="UTF-8" is a meta tag
                                     attribute that allows all language
                                     letters support-->
        <!-- link is a tag that allows to connect to Cascade Style Sheet files and
             set web-page favicon: bookmark image, which can be seen before of
             bookmark name (title) -->
        <link rel="icon" href="images/favicon.ico" type="image/x-icon">
         <!-- title tag allows to set bookmark name -->
        <title>Hello Ukraine </title> <!-- This web-page bookmark name
                                           is set to "Hello Ukraine" -->
    </head> <!-- head close tag-->
    <!-- body tag contents main part of web-page settings-->
    <body> <!-- body open tag-->
           <div id="hello"></div> <!--id="hello" identifier data attribute:
                                    allows access to web-page element with
                                    related value ( "hello" in this case)  -->
          <!-- div tag is a block tag: may consist another different tags inside-->
    <!--script tag allows to connect to JavaScript  from web-page document -->
    <script src="scripts/script.js"></script><!--scr tag sets source of
                                                 JavaScrip file
                                                 ("scripts/script.js"
                                                 in this case)-->

    </body> <!-- body close tag->
</html> <!-- html tag close tag-->
```

script.js:

```javascript
/*
 * document - web-page (<file name>.html) document
 * getElementById ('<id name>'- function that provide access to
 *                              the first element in web-page document
 *                              with related id value
 * innerHTML - web-page element property, which allows to set its text,
 *             including to set new elements.
 *             For example '<h1>Hello,Ukraine!</h1>' value of innerHTML
 *             will create new tag h1 inside its own element.
 * */
document.getElementById('hello').innerHTML='<h1>Hello,Ukraine!</h1>';
```