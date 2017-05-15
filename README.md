# 201705-3-Never-lost-Multicamera-Face-detection-and-tracking
201705-3-Never-lost: 
Xucheng Chen (xc2360) and Lingyu Zhang (lz2494)

Our goal is to create a smart platform that is very similar to the AI in TV series: Person of Interest. However, such strong AI with exceptional understanding of human activities and high accuracy in human recognition is far from technology in this area. Although it is still a dream to achieve actual artificial intelligence, we are still able to construct a rather smart platform combining cutting-edge technology like deep learning. With such hope of building great artificial intelligence, we built PRPOF——a person recognition platform that can conduct automated detection and tracking of targeted person. 
We firstly learning features of the specific face of the target person and we detect the specific person we want among the mass of people in multiple video cameras of surveillance system. Then we do inference from face location to the whole body bounding box and start tracking of that person. Since we are tracking the whole body, even if the person only gives us the back view, we can still keep tracking. And we also start face detecting mode once the person disappears, so in this way, we never lose the person we want. Additionally, with the person tracked, we also estimate the person's gender and facial expression to do some analysis.
