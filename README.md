# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Clone the GitHub repository and create a Django admin interface.

### Step 2:
Write HTML and CSS code for designing book cover page  and execute them.

## Code:
```
<!DOCTYPE html>
<html lang="en">
    </head>
           <meta name="viewport"
           content="width=device-width,initial-scale=1.0">
           <style>
    .bookpage{
        width: 400px;
        height: 600px;
        color:rgb(250, 20, 20);
        margin-left: auto;
        margin-right: auto;
        padding: 20px;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        background-image: url(/static/images/ex6.jpg);
        background-size: cover;
    }
        

    .insight{
        color: rgb(22, 21, 21);

    }

    
    .hrstyle{
        width:100px;
    }
    .author{
    
        display: inline;
        position: relative;
        color: rgb(14, 12, 12);
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
        color: rgb(14, 14, 230);
        font-size: medium;
        font-family: Verdana;
        position:relative;
        top:85px;

    }
    .subtitle{
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
            SEC INSIGHT
        </div>
        <div class="hrstyle">
            <hr style="color: rgb(20, 16, 16);">
        </div>
        <div class="booktitle">
            <h1>Fundamentals of Web Application Development</h1></div>
        <div class="subtitle">
            HTML and CSS Combined with Django Architecture
        </div>
        <div class="mypic">
            <img src="/static/images/my photo .jpg" width="130" height="145" alt="">
        </div>
        <div class="id">
            <hr style="color: orange;">
        </div>
        <div class="author">
           <p><b>sathish</b></p>
        </div>
        <div class="pub">
            SEC
        </div>
        <div class="ed">
            <b>Seventh Edition</b>
        </div>
    </div>
</body>
```

## Output:
![Screenshot_20230123_111321](https://user-images.githubusercontent.com/119404415/213979673-3e9ce23e-4842-4c6a-b374-010c13d04a26.png)


## HTML Validator:
![valid](https://user-images.githubusercontent.com/119404415/213979698-e895efd8-7ea1-4133-925b-f5bc53f553bd.png)


## Result:
The program for designing book cover page using HTML and CSS is created successfully.
