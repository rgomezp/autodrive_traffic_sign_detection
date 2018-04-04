# Autodrive Traffic Sign Detection
### Rodrigo Gomez-Palacio

My program uses OpenCV to detect traffic signs in a frame feed for the Autodrive Competition with General Motors. The algorithm works by first filtering the image/video based on color (red). Next, the algorithm detects shapes within the filtered image. Finally, detected possible signs are fed into a neural net (neural2d) that classifies them. 

## Main
Main.cpp can be found in `traffic_sign_detection/src/apps/`

#### Jan 24 - 2018
False positive rate has been reduced to near zero for all intents and purposes. While not 100% perfect, this minimum viable product can detect stop signs with a high accuracy.

![Alt text](screencapture.png?raw=true "Title")
=======
# autodrive_traffic_sign_detection
Autodrive_Traffic_Sign_Detection
