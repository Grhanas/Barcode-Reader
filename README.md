# Barcode-Reader
This code uses image processing techniques and pyzbar library to decode single barcodes in an image. 

This barcode reader code reads all 1D and 2D barcodes supported by the pyzbar library. This code is created for grayscale camera((basler)pylon camera) so if you are using RGB camera you need to add grayscale in image processing function. The special thing is pyzbar library is reading barcodes in 90 degrees(90-180-270-0). So this code fix this problem, you can read in barcodes in any degree.
