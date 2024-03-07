Features
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
mPhotoEditor.addText inputText, colorCode. Then i have also added undo and redo buttons
