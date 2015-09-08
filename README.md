# video_signature

Schedule
  Sept 8, 2015 --- Project Started by Genki Kuroda <genkikuroda@gmail.com>

Purpose:

Multimedia including video files on internet often are duplicated and video already spread out will be out of control.
Therefore, we need to identify the duplicate videos with different file format. 
At this moment, there are no simple method is available to identify the same contents of MP4 and AVI, or any other format. 
Thus, having a signature of video is quite useful to identify the "similarity" of any video.  Statistical approach will be done with hidden Malkov model, and machine learning techniques.

Property we can eliminate by this signature.

  Resolution (800 x 400, 1280....) * We don't care 4k or anything else.
  Video File Format (MP4,AVI,WMV,) * it's not important as long as we can see some screens.

Limitation:

  Audio will not be supported.
  Changing aspect ratio is not supported.
  
Approach:

(1) 3 dimentional approach for x,y,time.

(2) Divide and Conquer by 1/4

(3) tree generation algorithm is 4^n where n goes 0 to infinity.

(4) algorithm can be improve by learning.
