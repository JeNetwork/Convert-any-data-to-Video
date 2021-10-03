# Convert any data to Video and convert back
We can convert any data to Video and keep it on  Video hosting like YouTube, Vimeo, ... Important !!! We can convert back from Video to data original.

Convert data to video flow (Encode data to video):
1. Load data to bytes
2. Convert bytes to Base64 string
3. Draw Base64 string to Images (1920x1080 or 4K)
4. Convert all Images to Video with option: 1 frame = 1 image, 30fps = 30 images per second
5. Upload to Video hosting or keep local

Convert video to data flow (Decode video to data):
1. Extract all frame in Video to Images, every frame as image, may be use ffmpeg to extract frame
2. Open image and read all Base64 string, may be use OpenCV Tesseract to read text (OCR)
3. Convert all Base64 string to data original

Please tell me any your idea about this one in Discussions tab.
