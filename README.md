# Free-Style-Object-Tracking-using-OpenCV-APIs-By-Pixel-Team
Project #2.
# Here is the link for DEMO VIDEOS:
- https://drive.google.com/drive/folders/18DQVLmSaYM5fZoaG34gnyngpkU6UPcdV?usp=share_link

# Author: GiGa Team
- Jamshid Ganiev || Team Leader
- Asadbek Khoshimov
- Khaydarov Shokhzod
- Sabirov Anvarbek
# DEMO VIDEO WITH Team members:
<img width="1013" alt="Screenshot 2022-11-28 at 1 05 45 PM" src="https://user-images.githubusercontent.com/84252587/204192219-8f189f86-e675-4b84-b1fc-1de7bee3fd32.png">
## Drive to Demo video and real time test in class:
''
https://drive.google.com/drive/folders/1dSViQBLc-TeolonHGvt6LHNqEo885eFS?usp=share_link
''

# Algorithm CSRT
## CSRT (Discriminative Correlation Filter with Channel and Spatial Reliability) tracker
- Here is how the csrt object=tracking algorithm works:
- This algorithm uses spatial reliability maps for adjusting the filter support to the part of the selected region from the frame for tracking, which gives an ability to increase the search area and track non-rectangular objects. Reliability indices reflect the quality of the studied filters by channel and are used as weights for localization. Thus, using HoGs and Colornames as feature sets, the algorithm performs relatively well.

## Advantages
- Comparatively better accuracy
- Resistance to overlapping by other objects.
- Slower but more accurate than KCF
- Can recover from failures when the object hasn't moved much
- Manually adjustable parameters
## Drawbacks
- Does not recover well from failures due to full occlusion
- Does not recover when objects are changed out of view
- sufficiently low speed, an unstable operation when the object is lost

