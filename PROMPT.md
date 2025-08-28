This is my one shot prompt to create this application.

````

This is a single page HTML/JavaScript application that runs in the browser with the filename index.html. Keep the design simple and functional, do not use icons or emojis. Just simple CSS layout and colors that are professional, attractive and intuitive. Ensure the design is responsive to desktop, tablet and mobile sized screens.

Add an input box that is full width "Image URL" with a button to its right "Get Image"

dd 1 more input box "Maximum Pixels per Side" with the default value 1280 and it only accepts numbers.

Add 1 more input box "Padding Pixels" with the default value 20, it will only accept numbers. 

Add 1 more input box "JPEG Quality" with the default value 88, it will only accept numbers. 

Then show a square full width of the window CANVAS with a dotted line border.

The user will provide an image URL into an input box and click "Get Image" to fetch, OR drag an image into the canvas box OR paste from the clipboard.  

Show the image in the CANVAS. Ensure that transparent PNG, AVIF and WEBP images always show a white background.

As soon as the image is loaded into the application and shown on the canvas, begin the process:

1) Square the image by adding additional white pixels to the shorter sides so that all sides are the same number of pixels. 
2) Then add more white pixels on every side as a padding/border. The number of pixels comes from the "Padding Pixels" value.
3) If the resulting sides of the squared image after all of the previous processing is now greater than "Maximum Pixels per Side" value then resize the image to be no larger than "Maximum Pixels per Side". (Fox example the default value of 1280 will never produce an image larger then 1280x1280. If after all of the processing, the image is square and less then 1280 we do not do anythign to enlarge the image) WE ONLY EVER REDUCE THE FINAL IMAGE IF ITS LARGER THEN "Maximum Pixels per Side" 

Under the canvas add a full width download button to download the final result and save to the local computer as a jpg file with the quality pulled from the "JPEG Quality" input.



````
