# Blur-Detection

Blur detection, as the name suggests, is the process of detecting whether an image is blurry or not.

Possible applications of blur detection include:

Automatic image quality grading
Helping professional photographers sort through 100s to 1000s of photos during a photo shoot by automatically discarding the blurry/low quality ones
Applying OCR to real-time video streams, but only applying the expensive OCR computation to non-blurry frames
The key takeaway here is that it’s always easier to write computer vision code for images captured under ideal conditions.

Instead of trying to handle edge cases where image quality is extremely poor, simply detect and discard the poor quality images (such as ones with significant blur).
