# Keyboard Website Exercise

## General

Most of the work that needs to be done is inside index.html, with some in stylesheet.css. Something that needs to be changed or added is indicated by '[]'. 

## Part 1

At the bottom of the index.html there are eight <audio> tags below a comment saying what letter they are for. Inside, you should see src='[]'. Delete the brackets, and replace them with the path to the audio file. For instance, if you have an audio file called 'trumpet.mp4' inside the 'sounds' folder, you will put this inside the quotation marks:

'sounds/trumpet.mp4'

The entire line for the letter a would look like this:

<audio data-key="65" src="sounds/trumpet.mp4"></audio>

Remember to include the data type at the end. In the example above that would be .mp4

## Part 2

Go through index.html and fill out the content of the page (indicated with square brackets).
[PAGE TITLE] will be what shows in the tab in your browser
[PAGE NAME] will be the heading at the top of the page
[Category X] will be the heading at the top of each container
[Sound title] will be a description of the sound

## Part 3

Let's add a background. Download an image you want as the background of your site. Copy and paste it into the same folder as this. Then add the name of the image to this line in stylesheet.css: background: url('./[]') bottom center;

If you're image is called: background.jpg
Then the line should look like this:

background: url('./background.jpg') bottom center;

If you would rather have a colour than a background, you can replace the text after 'background:' with what ever colour you want. For instance, if you wanted the background to be yellow, it would look like this:

background: yellow;

(It's important for the semi-colon to stay at the end)

A list of all the colour names you can use can be found here:

https://www.w3.org/wiki/CSS/Properties/color/keywords

## Part 4 (Optional)

Try to change the look of the website. Go through the stylesheet.css and look at the colours used. Try changing the numbers inside and see what changes on the site. So, for instance, in .setup:

color: rgb(255, 255, 255);

Could become:

color: rgb(127, 2, 31);

(NOTE: each number can be from 0 to 255)

Check out this site to see what colours you can create:

https://htmlcolorcodes.com/color-picker/