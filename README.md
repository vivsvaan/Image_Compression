# Image Compression
Web app for Image Compression using DCT Algorithm

### Input
- path for the image
- int F - it determines how big are the blocks into which the image is split; the higher this value, the faster the algorithm but the lossier is the compression.
- int D - it must have a value between 0 and 2F - 1 and it determines how many frequencies will be cut out. The lower this value, the more aggressive the compression. It doesn't affect time performances.

### Output
- Rebuilds the image after performing the steps.
### Algorithm
- Split the image into FxF pixel blocks
- for each block
-     applies the
