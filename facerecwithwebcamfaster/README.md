This implementation is faster but it's a little more complicated, but it includes some basic performance tweaks to make things run a lot faster:
  1. Process each video frame at 1/4 resolution (though still display it at full resolution)
  2. Only detect faces in every other frame of video.

To make it work:
  1. install the required libraries (face_recognition, opencv, and some more boring basic ones like pillow etc.).
  2. make sure that the file(s) are in the same directory.
  3. change/add names of the people from variables and change/add them to array of names.
