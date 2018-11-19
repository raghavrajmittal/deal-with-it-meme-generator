# Creating the Deal-with-it Meme using OpenCV

- Facial Detection using OpenCV
- Extract facial landmarks (specifically eye regions) using Dlib
- Create a GIF using ImageMagick

Essentially, the application detects faces and the eye regions, computes the angles between the eyes, and rotates the image of the sunglasses accordingly. Then it creates multiple frames starting with the sunglasses on top and slowly falling down to the eye region. The 'DEAL WITH IT' text is displayed in the last frame, and the resulting gif is stored as output (.gif file).

**Running the program** <br/>
    $ python create_gif.py --config config.json --image images/raghav.jpg --output out.gif


Credit: Adrian Rosebrock
https://www.pyimagesearch.com/2018/11/05/creating-gifs-with-opencv/
