# webdev_ii_assignment_2

The codes for this page:

CSS

/* Reset some default styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
}

/* Style for flex containers */
.flex-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 50px; /* Adjusted to space boxes 50 pixels apart */
}

/* Style for each flex box */
.flex-box {
    width: calc(50% - 20px);
    background-color: white;
    border: 1px solid black;
    border-radius: 20px;
    padding: 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    margin-bottom: 20px;
    margin-left: 20px;
    margin-right: 20px;
}

/* Style for the square images */
.flex-box img {
    width: 100px;
    height: 100px;
    border-radius: 50%;
}

/* Style for the title */
.title {
    font-weight: bold;
    margin: 10px 0;
}

/* Style for the horizontal line */
.line {
    width: 100%; /* Adjusted to cover the entire length of the paragraph */
    height: 1px;
    background-color: black;
    margin: 10px 0;
}

/* Style for the paragraph */
.paragraph {
    margin: 10px 0;
}

/* Style for the button */
button {
    padding: 10px 20px;
    background-color: #8400ff;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

button:hover {
    background-color: #b3009e;
}


/--------------------------------------------------------------------------------------/



HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles/styles.css">
</head>
<body>
    <div class="flex-container">
        <div class="flex-box">
            <img src="images/image1.png" alt="Smiling Face with Smiling Eyes">
            <div class="title">Smiling Face with Smiling Eyes</div>
            <div class="line"></div>
            <div class="paragraph">A yellow face with smiling eyes and a broad, closed smile turning up to rosy cheeks. Often expresses genuine happiness and warm, positive feelings</div>
            <button type="button">Read More about this emoji</button>
        </div>

        <div class="flex-box">
            <img src="images/image2.png" alt="Clinking Beer Mugs">
            <div class="title">Clinking Beer Mugs</div>
            <div class="line"></div>
            <div class="paragraph">Two frosty mugs of beer with frothy heads being clinked together, as done at a celebratory or convivial toast ("Cheers!"). Several platforms include stylized lines to mark the clinking.</div>
            <button type="button">Read More about this emoji</button>
        </div>
    </div>

    <div class="flex-container">
        <div class="flex-box">
            <img src="images/image3.png" alt="Face with Tears of Joy">
            <div class="title">Face with Tears of Joy</div>
            <div class="line"></div>
            <div class="paragraph">A yellow face with a big grin, uplifted eyebrows, and smiling eyes, each shedding a tear from laughing so hard. Widely used to show something is funny or pleasing. Named the Oxford Dictionaries 2015 Word of the Year, and the most used emoji on all platforms from 2011-2021.</div>
            <button type="button">Read More about this emoji</button>
        </div>

        <div class="flex-box">
            <img src="images/image4.png" alt="Seedling">
            <div class="title">Seedling</div>
            <div class="line"></div>
            <div class="paragraph">A seedling, or a young plant, as a newly sprouted tree. Depicted as a tiny, light-green plant with a short stem and two leaves. often shown freshly sprung from a small mound of brown earth.</div>
            <button type="button">Read More about this emoji</button>
        </div>
    </div>
</body>
</html>



/--------------------------------------------------------------------------------------/

