# Batch resize and optimize Images

Two line of code, to be used for batch resizing images on MacOSX

What you need:
1. MacOSX build-in `sips` command [read full documentation](https://developer.apple.com/legacy/library/documentation/Darwin/Reference/ManPages/man1/sips.1.html)
2. ImageOptim App [Download here](https://imageoptim.com)

How to use it:
1. Open Terminal
2. Navigate to the folder with your Images
3. Make sure you have a backup of your files, this process is not reservable 
<<<<<<< HEAD
4. This command is going to scale all images (jpegs) inside the folder to a width of 1280 pixel and keep the aspect ratio
```$ sips --resampleWidth 1280 *.jpg```
5. This command will run the ImageOptim App in the background and optimize all images (jpeg) inside the folder
```/Applications/ImageOptim.app/Contents/MacOS/ImageOptim *.jpg```

=======
4. `$ sips --resampleWidth 1280 *.jpg`

This command is going to scale all images (jpegs) inside the folder to a width of 1280 pixel and keep the aspect ratio
5. `/Applications/ImageOptim.app/Contents/MacOS/ImageOptim *.jpg`

This command will run the ImageOptim App in the background and optimize all images (jpeg) inside the folder
>>>>>>> origin/master
