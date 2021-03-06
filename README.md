# Photoshop-NICAR

In this session, we'll learn:

1. How to automate tasks using **Actions**
2. How to create **Droplets** for Actions you use regularly
3. How to make **Animated Gifs** using the Timeline
4. How to use the **Perspective tool**

[Download files here](https://drive.google.com/file/d/0ByZb_bUVlqwjdkgzSnRGRk40Sm8/view?usp=sharing)

##Actions##
Do you find yourself repeating many of the same tasks again and again? You're working too hard. Make an action! In this example, we'll set up an action that saves an image as RGB at 200px wide and 72px/in resolution.

1. Open an image: **File > Open...**
2. Open the Actions pallette: **Window > Actions**
3. From the dropdown, select **New Action...**
*    ![](https://github.com/chriscanipe/Photoshop-NICAR/blob/master/screengrabs/NewAction.png)
4. Give it a name. Let's say "200px wide", and push "Record"
5. Select **Image > Image Size...**
*    ![](https://github.com/chriscanipe/Photoshop-NICAR/blob/master/screengrabs/Image%20Size.png)
6. Set the resolution to 72px and the width to 200px.
7. At the bottom of the Actions window, hit "Stop" to stop recording.
8. Close the image without saving your changes.
9. To run your script, open **File > Automate > Batch...**
*    ![](https://github.com/chriscanipe/Photoshop-NICAR/blob/master/screengrabs/BatchWindow.png)
10. Under "Play" select your Action "200px side"
11. Choose your source folder. This should be a folder containing multiple image files.
12. Under "Destination", choose "Folder". Then, Select a destination folder or create. This is where your new images will be saved.
13. Hit "Okay", sit back and relax. Your photos will be ready momentarily.


##Droplets##
Droplets make Actions even simpler to use by making them executuable with a simple Drag and Drop. 

1. Select **File > Automate > Create Droplet...**
*    ![](https://github.com/chriscanipe/Photoshop-NICAR/blob/master/screengrabs/CreateDroplet.png)
2. The Droplet menu is much like the Batch menu. Select a location for the Droplet icon to appear, and a folder in which you'd like your files to save.
3. Now, instead of going the all the trouble of selecting Batch from the Automate menu, just drag your folder of unedited images on top of the droplet icon. That's it! You're done!
*    ![](https://github.com/chriscanipe/Photoshop-NICAR/blob/master/screengrabs/droplet.png)

##Animated Gifs##
Do you have an interactive graphic you'd like to promote on the front page? Animated Gifs are a great way to draw attention to interactive work.

1. Start with a series of images or screenshots from your interactive.
2. Open one of the images in Photoshop.
3. Drag and drop your other images onto the stage. This will bring them into your file as separate layers.
*    ![](https://github.com/chriscanipe/Photoshop-NICAR/blob/master/screengrabs/GifLayers.png)
4. Select **Window > Timeline** from the toolbar. This will open a new panel in Photoshop.
5. From the Timeline panel, select "Create Frame Animation" from the dropdown, then click the dropdown.
6. This will pull one layer into the timeline window.
7. From the dropdown in the upper right of the Timeline window, select "Make Frames from Layers"
*    ![](https://github.com/chriscanipe/Photoshop-NICAR/blob/master/screengrabs/FramesFromLayers.png)
8. Make sure your frames are in the correct sequence, then set the duration for which you'd like each to display
*    ![](https://github.com/chriscanipe/Photoshop-NICAR/blob/master/screengrabs/SetFrameDurations.png)
9. Select **File > Save for Web**
10. Select Gif as your save format. At the bottom of the window, you'll also be able to set the number of times you'd like the animation to loop. For a homepage promo, it might not be appropriate to loop infinitely. Let's set it to loop 3 times. 
11. Save and you're done. Woot!
([The source files here are from this WSJ interactive:](http://graphics.wsj.com/ukraine-rebel-maps/))

##Perspective Tool##
We also covered the perspective tool through a tutorial I borrowed entirely from Proublica's Lena Groeger, so rather than try to replicate it,I'm jsut going to link to her tutorial here:
[Reorienting documents and images using the Perspective Tool (Exercise #2)](http://lenagroeger.s3.amazonaws.com/cuny-spring14/photoshop.html)
