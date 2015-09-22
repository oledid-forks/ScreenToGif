﻿    ___  ___  ___  ___  ___.---------------.
  .'\__\'\__\'\__\'\__\'\__,`   .  ____ ___ \
  |\/ __\/ __\/ __\/ __\/ _:\   |`.  \  \___ \
   \\'\__\'\__\'\__\'\__\'\_`.__|""`. \  \___ \
    \\/ __\/ __\/ __\/ __\/ __:                \
     \\'\__\'\__\'\__\ \__\'\_;-----------------`
      \\/   \/   \/   \/   \/ :   ScreenToGif   |
       \|______________________;________________|

Nicke Manarin, 21/09/2015

TO-DO:

• The Editor window.
• Board Recorder.
• You shouldnt play the preview while executing something.

• Pressed Keys overlay.
• Follow the cursor while recording without need to reajust the window position (free recording).
• Option to reduce number of colors.  http://www.codeproject.com/Articles/34792/Quick-how-to-Reduce-number-of-colors-programmatica
• Zoom effect.
• Morph algorithm.  http://www.codeforge.com/article/216937
• (Stalled) Image upload (ImgUr)  http://api.imgur.com/, Example 
• More startup args.
• Fast Rewind transition.
• TitleFrame delay should be a param.
• Any action shouldn't remove the image and alter everything.
• After resizing bellow 100px, use the NoText style on the Record/Stop buttons.

BUGS:

• Undo/Redo/Reset is a little bit buggy.
• Takes a while to render the inserted frames.
• Trying to record while moving using the Alt + Space option to -Y (above top screen) does not work.
• Video import is buggy.
• Opening the Recorder with the Snap options active and unchecking 
  Snapshot mode still displays the "Snap" button. Actually, changing the Snapshot mode doesn't change the button.
• First frame of webcam recording is just black.
• DoubleNumericUpDown not showing new binding value.
• Deleting multiple frames using the Delete key, will delete the wrong frames. (If selected from the end to the start).
• After deleting, scroll the list to the selected frame.
• Undo-Redo-Reset or maybe other actions should hide the ActionGrid.
• If selecting multiples frame from the end to the start, it will scroll to the end one.
• Deleting a big project will hang.

• Fix paddings with: Record, Stop.
• Move frame feature, after moving select moved frame.

 Done:
 • High DPI fixes.
 • Watermark, Border, FreeDrawing.