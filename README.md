# Drowsiness-Detection
A drowsy detection and alarming system using ML technology.
My drowsiness detector hinged on two important computer vision techniques:

1.Facial landmark detection
2.Eye aspect ratio

Facial landmark prediction is the process of localizing key facial structures on a face, including the eyes, eyebrows, nose, mouth, and jawline.
For drowsiness detection, we only needed the eye regions.
Once we have our eye regions, we can apply the eye aspect ratio to determine if the eyes are closed. If the eyes have been closed for a sufficiently long enough period of time,
we can assume the user is at risk of falling asleep and sound an alarm to grab their attention.
                                             
