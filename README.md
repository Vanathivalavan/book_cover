# Ex.06 Book Front Cover Page Design
# Date:24/09/2025
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Book Cover</title>

  <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;700;900&family=Poppins:wght@400;600&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: #111;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
    }

    .book-cover {
      position: relative;
      width: 90%;
      max-width: 420px;
      aspect-ratio: 3/4;
      background: url("cover_2.png") center/cover no-repeat;
      color: #fff;
      padding: 2.5rem 2rem;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      border-radius: 12px;
      box-shadow: 0 14px 40px rgba(0,0,0,0.85);
      text-align: center;
    }

    
    .book-cover::before {
      content: "";
      position: absolute;
      inset: 0;
      background: rgba(0, 0, 0, 0.55);
      z-index: 0;
    }

    .header, .footer {
      position: relative;
      z-index: 2;
    }

    .header h1 {
      font-family: 'Cinzel', serif;
      font-size: 2rem;
      font-weight: 900;
      text-transform: uppercase;
      color: #e6d9b8;
      text-shadow: 0 0 8px rgba(0,0,0,0.9), 0 0 15px rgba(230,217,184,0.4);
      margin-bottom: 0.5rem;
    }

    .header h2 {
      font-family: 'Poppins', sans-serif;
      font-size: 1rem;
      font-weight: 400;
      letter-spacing: 2px;
      color: #dcdcdc;
      opacity: 0.85;
    }

    .title{
        margin: 60px 60px 0px 60px;
    }

    .sub-title{
        margin: 0px 60px 0px 60px;
    }

    .footer {

      justify-content: space-between;
      align-items: flex-end;
      font-family: 'Poppins', sans-serif;
    }

    .footer .tagline {
      font-size: 0.9rem;
      font-weight: 600;
      text-transform: uppercase;
      color: #c0c0c0;
    }

    .author {
      text-align: right;
                  display: flex;
            align-items: center;
            gap: 0.5rem;
    }

    .author_img {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            border: 2px solid white;
        }


    .author span {
      font-size: 0.85rem;
      font-weight: 600;
      color: #d8d8d8;
    }

    @media (max-width: 480px) {
    .title{
        margin: 60px 40px 0px 40px;
    }
    .sub-title{
        margin: 0px 40px 0px 40px;
    }
      .header h1 {
        font-size: 1.5rem;
      }
      .header h2 {
        font-size: 0.85rem;
      }
      .footer .tagline {
        font-size: 0.75rem;
      }
    }
  </style>
</head>
<body>

  <div class="book-cover">
    <div class="header">
      <h1 class="title">Shadows of the Abyss</h1>
      <h2 class="sub-title">The Curse Beneath the Waves</h2>
    </div>

    <div class="footer">
    <img src="author.png" alt="Author" class="author_img">
      <div class="tagline">Darkness Calls</div>
      <div class="tagline">
        <span>By Mary</span>
      </div>
    </div>
  </div>

</body>
</html>
```
# OUTPUT:

![alt text](<Screenshot 2025-10-03 082034.png>)
# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
