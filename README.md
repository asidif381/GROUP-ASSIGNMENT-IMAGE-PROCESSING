Explanation of Thresholding Result (Arabic Text Image)
The input image contains Arabic text from a kitab, where the characters are dark and the background is relatively bright. 
After converting the image to grayscale, Otsu’s thresholding technique was applied to 
automatically determine the optimal threshold value based on pixel intensity distribution.
The resulting segmentation mask successfully separates the text (foreground) from the paper background (background). 
This method is effective for document images because of the high contrast between text and background.
The inverted binary image further enhances text visibility, 
making it more suitable for subsequent processing such as text analysis or optical character recognition (OCR).

Explanation of Thresholding Result (Hand-Drawn Sketch)
The hand-drawn sketch consists of irregular line thickness and varying pencil intensity. 
After converting the image to grayscale, Otsu’s thresholding was applied to distinguish the drawn lines from the background.
The segmentation result shows that thresholding is able to capture the main sketch structure; 
however, some lighter strokes may not be fully preserved due to low contrast. 
This demonstrates the limitation of global thresholding when applied to non-uniform hand-drawn images.

Explanation of Thresholding Result (Hand-Drawn Color Drawing)
The color hand-drawn image contains multiple color intensities and shading variations. 
When converted to grayscale, different colors may map to similar gray-level values, reducing contrast between the drawing and the background.
As a result, Otsu’s thresholding produces partial segmentation, where some colored regions are merged with the background.
This highlights that thresholding based solely on grayscale intensity is less effective for color images, 
and color-based or adaptive thresholding techniques may be more suitable.
