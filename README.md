# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

Step 1: Create a static file directory and mention the changes in settings.

Step 2: Make a new folder templates inside your app and create a html and map them using views and url.

Step 3: Write down the code for book cover using HTML and CSS.

Step 4: Add images and other contents using CSS record a screenshot of it.

## Code:
```
cover.html:

<!DOCTYPE html>
<html lang="en">
    <head>
        <title> Wings of Fire</title>
        <style>
        h1{
           color:white;
        }
         .bookpage{
             width: 400px;
             height: 650px;
             background-color: black;
             background-position: center;
             margin-left: auto;
             margin-right: auto ;
             padding: 20px;
             background-image: url('/static/images/pic2.jpg');
             background-size: cover;
             background-repeat: no-repeat;

         }
         .toptext{
             color:white;
             padding-left: 10px;
             font-size: 14px;
             font-family: Arial, Helvetica, sans-serif;

         }
         .tophr{
             color:#e36f2f;
              width: 180px;
         }
         hr{
             color:#e36f2f;

         }
         .booktitle{
             font-family: Arial, Helvetica, sans-serif;
             padding: 10px 10px 0px 10px;
             display: flex;
            align-items: center;
            justify-content: center;
  margin-right: 10px;
  margin-left: 10px;
  font-size: 20px;
         }
         .author{
             color:white;
             font-family: Arial, Helvetica, sans-serif;
             display: inline;
             font-size: 24px;
             position:relative;
             line-height: 20px;


         }
         .sub-text {
             color:white;
             font-family: Arial, Helvetica, sans-serif;
             display: flex;
             line-height: 5px;

  margin-right: 10px;
  margin-left: 10px;

  font-size: 14px;
  }

.footer {
  color:orange;
  padding-top: 180px;
}
.image {
    color:white;
             font-family: Arial, Helvetica, sans-serif;
 font-size: 22px;
  margin-right: 20px;
}
.bottomhr {
    color:#e36f2f;
              width: 400px;

}
img {
    width: 90px;
    height: 100px;
    margin-right: 20px;
    vertical-align: bottom;
}
.edition {
    color:#e36f2f;
             font-family: Arial, Helvetica, sans-serif;
 font-size: 22px;
 line-height:bottom;

}


        </style>
        </head>
            <body>
                <div class="bookpage">

                    <div class="toptext">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;EXPERT INSIGHT</div>
                    <div class="tophr"><hr></div>
               <div class="booktitle"><h1>Wings of Fire</h1></div>
               <h3 class="sub-text">The autobiography of Dr. APJ Abdul Kalam</h3>
                    <h3 class="sub-text">written by Dr. APJ Abdul Kalam</h3>
                    <div class="footer">
                        <h2 class="edition">&nbsp;&nbsp;First
Edition&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <img src="/static/images/img.jpg" alt="Author"></h2>

                        <div class="bottomhr"><hr></div>
                    <div class="author"><h3>&nbsp;&nbsp;Dr. APJ Abdul Kalam &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</h3></div>

                </div>
                </div>

            </body>


</html>
```

## Output:

CLIENT OUTPUT:


![web output 6 1](https://github.com/kancharlaNarmadha/cover-page-design/assets/119559316/447ea214-f8f2-4f1f-82e7-23bdba9b0842)


SERVER OUTPUT:

![web output 6 2](https://github.com/kancharlaNarmadha/cover-page-design/assets/119559316/4c553a3d-9f5b-4c57-a74e-3f4c37cf7f0e)



## Result:
Thus a website to display the cover page design of a book was successfully created.
