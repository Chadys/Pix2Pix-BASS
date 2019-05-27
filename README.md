### A Pix2Pix implementation for the Blind Audio Source Separation problem, on vocal separation, using musdb18
This is a direct implementation of Pix2Pix for BASS, in a colab notebook, on raw audio format.

It uses Tensorflow 2.0 (but it will be installed automatically in the notebook VM), with 1D de/conv instead of 2D, ReduceLROnPlateau and EarlyStopping.

The notebook should be pretty self explanatory.

The only thing you need to do to execute is to chose a GPU environment and to have the musdb18.zip in your folder `My Drive` in your google drive (the file is to big to import it from local, but feel free to change the command and use another host to load it from).

Uncomment the four rsync syscall if you want to save your result on your mounted drive.

If you want the score of your run, you need to uncomment one of the evaluation method (either in the estimate creation function or in the EVALUATION ONLY block).

Outputs aren't great but this is a preliminary test.

A result sample can be found in the `samples` folder.