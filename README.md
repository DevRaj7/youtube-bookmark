# youtube-bookmark
This repository contains the source code for a web extension for youtube video player . We can bookmark a particular time stamp and can view it in the future

I have used Manifest V3 and I have used YouTube DOM structure to insert a button on the plalyer, and chrome web storage for storing timestamps of each URL

Here is how to use extension


#1 Enable it in Chrome Extensions.

![Screenshot (48)](https://user-images.githubusercontent.com/80745353/179186209-346956cb-3763-46b6-ae85-8748cb8bfd3e.png)

#2 Open an YouTube Video

#3 Click on the + icon to bookmark a timestamp

![Screenshot (49)](https://user-images.githubusercontent.com/80745353/179186331-e826a39d-5c67-45ab-b96c-ffbe429601e0.png)

# Go to the extension and play particular timestamp

![Screenshot (50)](https://user-images.githubusercontent.com/80745353/179186412-61d5576a-9df5-44ae-b6f0-e3bb6f4930bf.png)





























#issue
an eventListener occurs whenever the URL id is changed, and a bookmark button is added,
but if the page is reloaded , URL remains the same , and bookmark button disappears, to address this issue,multifunction calls are used which is not an optimized approach !! 
