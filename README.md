# Ex.06 Book Front Cover Page Design
# Date:28-10-2024
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


    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Book Cover Design</title>
        <style>
            body {
                margin: 0;
                padding: 0;
                font-family: Arial, sans-serif;
                display: flex;
                justify-content: center;
                align-items: center;
                height: 100vh;
                background-color: #f0f0f0;
            }
            .book-cover {
                width: 450px; /* Approx 6 inches */
                height: 675px; /* Approx 9 inches */
                background-image: url('CODE_IMG.jpg'); /* Add your background image URL here */
                background-size: cover;
                background-position: center;
                position: relative;
                box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            }
            .overlay {
                position: absolute;
                top: 0;
                left: 0;
                width: 100%;
                height: 100%;
                background-color: rgba(0, 0, 0, 0.6); /* Dark overlay */
            }
            .content {
                position: absolute;
                top: 15%;
                left: 10%;
                right: 10%;
                color: white;
                text-align: center;
            }
            .title {
                font-size: 2.5em;
                font-weight: bold;
                line-height: 1.2em;
            }
            .subtitle {
                font-size: 1.0em;
                margin-top: 10px;
            }
            .author {
                position: absolute;
                bottom: 15%;
                left: 50%;
                transform: translateX(-50%);
                display: flex;
                flex-direction: column;
                align-items: center;
            }
            .author img {
                width: 80px;
                height: 80px;
                
                border-radius: 50%;
                margin-bottom: 10px;
            }
            .author-name {
                font-size: 1.2em;
            }
            .footer {
                position: absolute;
                bottom: 5%;
                width: 97.5%;
                text-align: center;
                padding: 5px;
                background-color: rgba(0, 0, 0, 0.8);
                color: white;
                font-size: 0.9em;
            }
        </style>
    </head>
    <body>

        <div class="book-cover">
            <div class="overlay"></div>

            <div class="content">
                <div class="title">
                    Responsive Web Design <br> with HTML5 and CSS
                </div>
                <br></br>
                <br></br>
                <br></br>

                <div class="subtitle">
                    Develop future-proof responsive websites using the latest HTML5 and CSS techniques
                </div>
            </div>

            <div class="author">
                <img src="author.jpg" alt="Author Image"> <!-- Add author's image URL here -->
                <div class="author-name">John Doe</div>
            </div>

            <div class="footer">
                © 2024, Expert Insight Publications
            </div>
        </div>

    </body>
    </html>


# OUTPUT:

![alt text](<Screenshot 2024-11-21 184046.png>)


# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
