# Complete Blender Creator - Section 10 - VFX

This is the [Complete Blender Creator course]( http://gdev.tv/cbcgithub) - one of the bestselling and highest rated Blender courses on Udemy! Continually updated in response to student suggestions, you will benefit from the fact we have already taught over 360,336 students game development and design, many shipping commercial games as a result.

You're welcome to download, fork or do whatever else legal with all the files! The real value is in our huge, high-quality online tutorials that accompany this repo. You can check out the course here: [Complete Blender Creator]( http://gdev.tv/cbcgithub)

## In This Section

### Introduction to VFX & CGI ###



### Video Effects (VFX) ###

+ All about combining our Computer Generated Imagery (CGI) with real world environments.
+ This can be models, particle effects etc.
+ We will start with a still image and place a model into it.
+ After we have mastered that we will conquer video footage!

**Choosing Your Subject**

+ You can follow along with me, choose your own path or both!
+ Keep it simple, this goes for both your model AND the “real” space it is going to occupy.

### Good Source Material ###

+ Picture/photo, video or even another render
+ We’ll grab a photo and check out it’s settings.
+ This is important with both stills and videos.
+ With you own video keep a note of the settings as they’re often lost

### Introduction to Compositing ###

+ Bringing different renders together into one final render.
+ Compositing is done in the Node Editor.
+ View your composite changes live.
+ Learn how to scale a background image independently of the final render resolution.

### Matching Camera Settings ###

+ We will setup the camera using the settings gathered from the picture.
+ Reiterate the importance of accurate camera data.
+ Use the Text Editor to store data for reference.
+ Start setting up a scene to match the photo.

### Mathematics And Images ###

+ Can be difficult to comprehend at first.
+ Initially focus on monochrome (Grayscale).
+ Reminder that Colour is generated through 3 channels, Red, Green and Blue, with values from 0-1 (Sliders show 0-255).
+ Each Pixel will have its own values.
+ Use one value for all Pixels

**Basic Mathematics**

+ Adding, subtracting, dividing and multiplying are just as you would expect them to be.
+ Values that are less than 0 or greater than 1 are passed through unless clamped.
+ Colour>Mix and Convertor>Math nodes function almost the same, however there are different options.

### Overlaying Images ###

+ Background Image - Visible
+ Our Object - Visible
+ Our Objects Shadow- Visible
+ Ground - Used for capturing the shadow -Hidden
+ How we can isolate the object by itself.
+ How we can isolate the shadow by itself.

### Extracting Image Data ###

+ We could take the background image and map it to an object that is visible in our render.
+ We have all the 3D data to make a comparison scene.
+ Create another Render Layer for comparison without the object and therefore no shadow.
+ Need to consider the order of these layers.

### Blender Camera Tracking: Footage ###



### Blender Camera Tracking: Markers ###

+ Markers track parts of the footage.
+ Uses similar controls to the 3D Editor
+ You’ll need a minimum of 8 in the scene to effectively track a camera, more the better.
+ Well have a look at Pattern Size and Search size, discovering what they do.
+ Recommend placing markers manually.

### Solving Camera Motion ###

+ You need the right camera details!
+ Check the accuracy of our markers
+ Average camera solve error of \<1 is ideal, but not always necessary. We have to test and assess.
+ May have to refine your markers more.

### CGI / VFX Final Scene ###

+ Import assets you wish to use in your scene.
+ Adjust your camera's view, if it is slightly out.
+ Get the ground ready for shadows.

### Transparent Backgrounds ###

+ Learn how to set your Background as transparent.
+ The options are different in both Blender Render and Cycles.
+ Relatively straightforward - however the options are hidden away!

### VFX and CGI Wrap Up ###
