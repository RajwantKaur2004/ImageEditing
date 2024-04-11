#ImageEditing
My application is to edit the images. The features in my photo editing app, which include text addition, background removal, image retouching, filters, and effects. It will assist users in improving, modifying, and customising their images. My goal in creating this app is to make it easy to use and enjoyable for people to alter their photos. Popular features of these apps include the ability to edit every aspect of an image in detail, the ability to make collages, add stickers, and edit photos using presets and access to the smartphone's camera and photo gallery.

Technologies
Kotlin as a Programming language
Firebase
Wireframe: Figma
Database: .txt using Notepad
Features: 
Drawing on image with option to change its Brush's Color, Size, Opacity, Erasing and basic shapes.
Apply Filter Effect on image using MediaEffect
Adding/Editing Text with option to change its Color with Custom Fonts.
Adding Emoji with Custom Emoji Fonts.
Adding Images/Stickers
Pinch to Scale and Rotate views.
Undo and Redo for Brush and Views.
Deleting Views
Saving Photo after editing.
To start with this, I simply add the dependencies from mavenCentral() in the gradle file.
First i added First PhotoEditorView in our xml layout. Then, set the image by getting source from PhotoEditorView which will return a ImageView so that we can load image.
We can apply inbuild filter to the source images using
mPhotoEditor.setFilterEffect PhotoFilter.BRIGHTNESS and text with inputText and colorCode like this
mPhotoEditor.addText inputText, colorCode. Then i have also added undo and redo buttons.

I have added Camera access and some navigations to the app to make it more appealing.
The app has a new Icon now.
So overall this app is easy to use and simple.
