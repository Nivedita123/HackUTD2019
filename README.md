# Vision
Mobile app for visually challenged people


### Inspiration
Smartphones have opened the door to a world of possibilities, far beyond what we could have imagined years ago. They have innovations that allow accessibility and functionality to the people who are visually impaired. With the help of a smartphone they can recognize their surroundings and become more independent.

### What it does
Vision uses the smartphone's camera to continuously capture and recognize the objects and people currently in the view.

### How we built it
We used the SSD MobileNet v2 trained on Microsoft COCO dataset to recognize the objects captured by the smartphone's live camera feed and uses the Azure Face API to give certain details about a person if requested.

### Challenges we ran into
- Avoid detecting objects in the frame which are too far and not relevant
- Couldn't detect stairs and walls with just the mobile's camera.

### Accomplishments that we're proud of
We are proud that we have learned cutting edges technologies like ML, TensorFlow and object detection and were able to deploy these on mobile device. We are also very proud that we have used these technologies to help those who really require help. We are proud that we are able to empower them and make them independent with help of our application.

### What we learned
- The Face API
- TensorFlow
- Integration with android

### What's next for Vision
- Store faces of recognized people, so that user can be notified if the app "sees" a person it already "knows".
- Assist user with traffic signals
- Assist user in navigating indoors more accurately (detecting object distances, stairs and walls)
