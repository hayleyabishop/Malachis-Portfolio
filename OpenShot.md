# OpenShot 

### Contents

 - [Install](#install)
 - [Interface](interface)
    - [Preview Files](#project-files)
    - [Timeline](#timeline)
    - [Video Preview](#video-preview)
 - [Tools](tools)
     - [Transitions](#transitions)
    - [Effects](#effects)
    - [Emojis](#emojis)
    - [Razor Tool](#razor-tool)
    - [Markers](#markers)
 - [Miscellaneous](#Miscellaneous)
    - [Hotkeys](#hotkeys)
    - [Exporting](#exporting)

### Install 

To install OpenShot navigate to https://www.openshot.org/, and click the download button.

![Download button](https://i.imgur.com/VTIkA4H.jpg)

Next, you can continue with the default Windows 64-bit Installer. If you are not on a 64-bit compatible Windows system there are options for other operating systems below the default download.

### Interface 

##### Project Files 

The Project Files section acts as the main storage for all the files in your project. A red box outlines this section of the main interface below.

<img align='left' src='https://i.imgur.com/lv6yS65.png'>

You can use the Project Files section to upload all of the files to be used in the project. Do this by dragging and dropping files directly into the box or by pressing the large green plus at the top of the application. Alternatively, you can right click inside the box and select import files (``` Ctrl-f```) to browse and select files graphically. 

Use the tab at the top of this section to filter files in the project by video, audio, image, or all.

<img align='left' src='https://i.imgur.com/l07I2rh.png'>

Other functionalities in the Project Files section are covered in the [Tools]() section below.

##### Timeline 

You can edit all of the files in your project in the Timeline. A red box outlines the section below.

<img align='left' src='https://i.imgur.com/o9Volem.png'>

You can populate the Timeline by dragging files from the Project Files section and dropping them onto a track in the Timeline. By default, OpenShot will start every project with 5 tracks. You can add more by clicking the green plus under the word Timeline in the top left of the section. You can adjust your view on the tracks by operating the three sliders highlighted in the image below. Note that Tracks work as hierarchical layers. That means that a track with a higher numerical value will overlay tracks with lower numerical values if the content plays at the same time.

<img align='left' src='https://i.imgur.com/P2FaoJM.png'>

The slider at the bottom moves the view horizontally, and the slider to the right moves the view vertically. The slider at the top has a bit more functionality. The transparent blue portion of this slider moves the view horizontally like the slider at the bottom. Moving the blue dots on this slider changes the zoom of the timeline. This allows you to make precise edits or analyze the entire project at once. 

Right clicking a track gives you a few options as well. 

<img align='left' src='https://i.imgur.com/GUDaasT.png'>

Add Track Above adds a track above the track that was right clicked on. Add Track Below adds a track below the track that was right clicked on. Rename Track allows you to name a track whatever you want. Lock Track prevents any further changes to the track that was right clicked on. Remove Track deletes the track from the Timeline.

Other functionalities of the Timeline section are covered in the [Tools]() section below.

##### Video Preview 

This section allows you to preview the contents that are on your timeline. A red box outlines the section below.

<img align='left' src='https://i.imgur.com/u9m7WDY.png'>

The Video Preview section shows the frame that the Timeline ruler is currently located on. You can see the Timeline ruler in the image below.

<img align='left' src='https://i.imgur.com/1I1VBIU.png'>

To play the contents of the Timeline continuously in the Video Player, move the ruler to where you would like to start and press spacebar or the green play button on the Video Preview. You can also move the Video Preview frame by frame by pressing the left and right arrow keys to move to the left and right frame respectively.

### Tools

 ##### Transitions 

You can add transitional effects to files on your Timeline by dragging and dropping them from the Project files section. Start by choosing two files you want to transition between and place them next to each other or overlapping on the same Timeline track. Then navigate to the Transitions tab at the bottom of the Project Files section.  

<img align='left' src='https://i.imgur.com/7fGvcIx.png'>

Here , you can browse the different transition effects offered by OpenShot. Once you choose a transition, drag and drop it onto the files on the Timeline you want to affect. You can adjust the length of the transition by grabbing its edges and moving them to fit your purposes. Note that when overlapping two files in the Timeline, a fade transition will automatically be applied. You can remove it by clicking on the fade transition and pressing the backspace key.

##### Effects 

You can add and adjust visual effects to your project by dragging and dropping effects onto your files in the Timeline. To browse and select effects, navigate to the Effects tab on the Project Files section. 

<img align='left' src='https://i.imgur.com/74Cy2Th.png'>

To apply an effect to a file, drag and drop the effect from the Project Files section onto your file in the Timeline. This will add an indicator to your file that you can right click to adjust. 

<img align='left' src='https://i.imgur.com/XgjGUoY.png'>

Selecting Properties from the right click menu will open a new Properties section on the left of the OpenShot window. 

<img align='left' src='https://i.imgur.com/mfmXwXr.png'>

From this window you can adjust all of the properties of the particular effect you are working with. If you have multiple effects on one file, you can access different effects' properties by using the Selection dropdown at the top of the Properties section outlined above.

##### Emojis

You can add emoji image files to your project by selecting the Emojis tab in the Project Files section and dragging and dropping them onto your Timeline. 

<img align='left' src='https://i.imgur.com/LGHKA3Z.png'>

Once an emoji is added to your Timeline it can be manipulated like any other file on the Timeline. 

##### Razor Tool

The Razor Tool is used to cut files into parts that can be edited or removed separately. It is found in the Timeline section. 

<img align='left' src='https://i.imgur.com/JFSWyAV.png'>

When the Razor Tool is selected you can hover over a file in your Timeline and left click to split the file at that location.

<img align='left' src='https://i.imgur.com/7scEcHu.png'>

In the image above you can see the Razor Tool cursor outlined in red on the left and the split of the file outlined in red on the right.

You can also split file by moving the Timeline ruler to the location on the file you would like to split and right clicking the file. This will bring up a menu that has a Slice option.

<img align='left' src='https://i.imgur.com/JZjfiJg.png'>

Hovering over Slice will bring up a new menu. The options in this menu detail what will be done to the file after is split. Keep Both Sides will act the same as the Razor Tool. Keep Left Side will delete the right side of the file after splitting, and Keep Right Side will delete the left side of the file after splitting. 

##### Markers

The Marker tool is used to specify specific points in a file that have defined properties. They are represented on a file by a small green vertical dash at the bottom of the file.

<img align='left' src='https://i.imgur.com/UJRzsSR.png'>

You can add a marker by setting the Timeline ruler to the location you want and clicking the green Add Marker button outlined in red above. You can also add markers by inserting keyframes in the Properties section of a file. You can switch between markers quickly by clicking the orange Previous Keypoint and Next Keypoint buttons outlined in red above. 

### Miscellaneous

##### Hotkeys

| Function | Hotkey |
| :---      | :---: |
|Add Marker| ```Ctrl+M```|
|Add Track| ```Ctrl+Shift+T```|
|Add To Timeline| ```Ctrl+W```|
|Center on Playhead|```Ctrl+Up``` |
|Choose Profile|```Ctrl+P```|
|Copy|```Ctrl+C```|
|Delete Item|```Delete```|
|Delete Item (Alternative)|```Backspace```|
|Details View|```Ctrl+D```|
|Export Video|```Ctrl+E```|
|Fast Forward|```L```|
|Fullscreen|```F11```|
|Import Files|```Ctrl+F```|
|Insert Keyframe|```Ctrl+Shift+E```|
|Jump To End|```Ctrl+End```|
|Jump To Start|```Ctrl+Home```|
|New Project|```Ctrl+N```|
|Next Frame|```Right```|
|Next Marker|```Ctrl+Right```|
|Open Project|```Ctrl+O```|
|Paste|```Ctrl+V```|
|Play/Pause|```Spacebar```|
|Previous Frame|```Left```|
|Previous Marker|```Ctrl+Left```|
|Quit|```Ctrl+Q```|
|Redo|```Ctrl+Y```|
|Rewind|```J```|
|Save Project|```Ctrl+S```|
|Toggle Razor|```R```|
|Undo|```Ctrl+Z```|
|Zoom In|```=```|
|Zoom Out|```-```|

##### Exporting

To export your completed project, click the red circle at the top of the application.

<img align='left' src='https://i.imgur.com/mFilCE8.png'>

This will open the Export Video window. From here you can select your file name and folder path. You can also choose the profile of the project. This will determine what the project is intended for (i.e. DVD, Blu-Ray, Web). Next you can select the target (filetype), the video profile (resolution/framerate), and the quality. When you are done click Export Video at the bottom of the window.
