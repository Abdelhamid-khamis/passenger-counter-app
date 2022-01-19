# HTML Cheat Sheet

HTML &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Hyper text markup language

Tags   &nbsp;  &nbsp; &nbsp; &nbsp; &nbsp; ```<a href="https://github.com/"></a>```

Element &nbsp; &nbsp; &nbsp; &nbsp;   a

Attributes &nbsp; &nbsp; &nbsp; &nbsp;href="https://github.com"

Elements can have unique identifiers used by javascript and CSS\
 ```<p id="fruit"> Apple Orange Banana </p>```

Elements can be styled by belonging to a class of Elements\
```<p class="redThings"> This text will be colored red if "redThings" says so```

**Index.html**\
The index.html page is the most common name used for the default page shown on a website if no other page is specified when a visitor requests the site. In other words, index.html is the name used for the homepage of the website

```HTML
<!DOCTYPE HTML>
<html>
    <head>
        <title>Cheat Sheet</title>
        <link rel="stylesheet" type="text/css" href="./index.css">
    </head>

    <body>
        <h1><strong><em>Cheat Sheet</em></strong></h1>
        <h2>A semi complete HTML Cheat sheet</h2>

        <p>In order to practice my muscle memory, I'll try to remember as much as possible, from HTML, Tags, Elements & Attributes.</p>

        <a href="https://github.com/">Github.com</a>
        <a href="#container">Go to the div line</a>

        <script src="https://ajax.googleapis.com/ajax/lib">JS</script>

        <audio></audio>
        <video></video>
        <canvas></canvas>
        <div class="container" id="myID">The div line.</div>
        <span></span>

        <!-- Button element, contains unique id to be called using, CSS or javascript, and contains count() function which will be called when the button is clicked -->
        <button id="count-el" onclick="count();">Count</button>



        <!DOCTYPE>  Defines the document type
        <html> Defines the root of an HTML document </html>
        <title> Defines a title for the document </title>
        <header> Defines a header for a document or section </header>
        <main> Specifies the main content of a document </main>
        <footer> Defines a footer for a document or section </footer>


        <p> Defines a paragraph </p>
        <a> Defines a hyperlink </a>
        <b> Defines bold text </b>
        <br> Defines a single line break </br>
        <button> Defines a clickable button </button>
        <div> Defines a section in a document </div>
        <footer> Defines a footer for a document or section </footer>
        <h1> to <h6> Defines HTML headings </h1> to </h6>
        <img> Defines an image </img>
        
        // Defines ordered/unordered lists & list items
        <ol> Defines an ordered list </ol>
        <ul> Defines an unordered list </ul>
        <li> Defines a list item  </li>

        <script> Defines a client-side script </script>
        <span> Defines a section in a document</span>
        
        // Defines a Table, cells and rows.
        <table> Defines a table </table>
        <td> Defines a cell in a table</td>
        <th> Defines a header cell in a table </th>
        <tr> Defines a row in a table </tr>


    </body>

</html>

```

## Resources

- [Best HTML cheat Sheet](https://htmlcheatsheet.com/)
