# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1: Set Up the HTML Document
Start with the HTML5 doctype declaration:

<!DOCTYPE html>
Open the HTML document with the <html> tag and set the language attribute to "en":


<html lang="en">
Add the <head> section to include metadata and styles:


<head>
   <!-- Add meta tags and style block here -->
</head>
Inside the <head> section, include the viewport meta tag for responsiveness:


<meta name="viewport" content="width=device-width, initial-scale=1.0">
Add the <style> block within the <head> section to contain the CSS styles.

Open the <body> section to include the content of the document:


<body>
   <!-- Add the content here -->
</body>

### Step 2: Style the Book Page
Create a div tag with the class "bookpage" to serve as the container for the book cover page:


<div class="bookpage">
   <!-- Add content inside the bookpage div -->
</div>
Inside the "bookpage" div, add various <div> elements with classes such as "insight," "hrstyle," "booktitle," "subtitle," "mypic," "id," "author," "pub," and "ed" to structure the content.

### Step 3: Apply CSS Styles
In the <style> block, add CSS rules to style the elements within the "bookpage" container.

Set styles for the container's width, height, color, margin, padding, font, and background image.

Define styles for other elements such as text color, font family, sizes, and positioning.

Use the background-image property to set the background image for the container.

Link external images (if any), such as the author's picture.

### Step 4: Save and Run
Save the HTML file with an appropriate name (e.g., "book_cover_page.html").

Open the HTML file in a web browser to view the styled book cover page.

### Step 5: Adjustments and Customization
If needed, make adjustments to the styles, content, or layout in the HTML and CSS code to achieve the desired appearance.

Experiment with different values for colors, sizes, and positioning to customize the book cover page.

By following these steps, you should be able to create and customize a book cover page using the provided HTML and CSS code.

### Step 6:
End program.

## Code:
```
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            color:yellow;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arail Narrow', Arial, sans-serif;
            background-image:"https://www.google.com/url?sa=i&url=https%3A%2F%2Falphacommunity.in%2Fexplore%2Fexpert-speak%2Fcapturing-the-rhythms-of-classical-india%2F&psig=AOvVaw0RTtw42q8tFfie08rgSEYp&ust=1701673603118000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCKDM5aPa8oIDFQAAAAAdAAAAABAK";
            background-color: red;
            background-size:cover;
            background-position: center;
        }
            

        .insight{
            color: blanchedalmond;

        }

        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: Honeydew;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color: cyan;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            color: greenyellow;
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                CSC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color:bisque;">
            </div>
            <div class="booktitle">
                <h1>Honors diplomo computer application</h1></div>
            <div class="subtitle">
                C language, C++, Python, Ms-office and HTML and CSS combined in HDCA
            </div>
            <div class="mypic">
                <img src="easwar.img.jpg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: hotpink;">
            </div>
            <div class="author">
               <p><b>EASWAR R</b></p>
            </div>
            <div class="pub">
                AIDS
            </div>
            <div class="ed">
                <b>Seventh Edition</b>
            </div>
        </div>
    </body>
</html>

```
## Output:
![image](https://github.com/EaswarR2005/cover-page-design/assets/146931525/b24efcf9-e849-4057-9bd0-ea64be5bd2c7)

## Result:
Then, the program is successfully executed.
