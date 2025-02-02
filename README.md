# AM2022.1_GestureClasifier
- A Machine Learning Project, from the first semester of 2022, tutored by Prof. Dr. Fabrício Braz, at UnB. 
- Model identifies hand gestures in an image
- Model trained using HaGRID, with a smaller database, as it is originally extensive
- The images from the database were cut using bounding box, given that by doing it, a better accuracy can be achieved

## Identifiable gestures
- 🤙 call
- 👎 dislike
- ✊ fist
- 🖐️ four (ignore one finger here)
- 👍 like
- 🤭 mute
- 👌 ok
- 👆 one
- ✋ palm
- ✌️ peace
- ✌️ peace_inverted
- 🤘 rock
- ✋ stop
- 🤚 stop_inverted
- 🖐️ three (ignore two fingers  here)
- 🖐️ three2 (ignore two fingers  here)
- ✌️ two_up (pretend the two raised fingers are close)
- ✌️ two_up_inverted (pretend the two raised fingers are close)

## Step by step
- Extract the file "cropped"
- Start the blocks
- Modify the path where the files will be uploaded from
- Load batch and confusion matrix
- Insert an image with any of the above hand gestures to be classified
- The classification is generated

## Screenshots
![image](https://github.com/brenoalexandre0/AM-2022.1---Gesture-Classifier/assets/80782792/9e8b3f8b-2ad8-4e32-927c-ff9b02b2feed)

## Installation
**Language:** Jupyther Notebook  
**Framework:** tqdm, numpy, os, json, PIL, fast.ai, fastbook, resnet18, resnet152, pandas

## Original model
https://github.com/hukenovs/hagrid
