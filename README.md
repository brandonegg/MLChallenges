# MLChallenges
The goal of this repository is to improve my familiarity with various AI/ML frameworks and technologies. I'll be occassionally updating this with new challenges and slowly working through my solutions. You can use any programming language and framework of choice for any of the following challenges, I will be using Python for most examples since it is the most widely used in this field.

# Challenges
Challenges below will be `tagged` with various categories of ML/AI concepts. Some frequent tags are found below:
- `image recognition`
- `facial recognition`
- `speech-to-text`
- `text-to-speech`

## 1. Object Labeling
**Labels:** `image recognition` and `text-to-speech`

Create a object labeling system which utilizes a PC webcam to detect objects a person is holding and announce what said object is. This requires several incremental steps in order to complete this successfully. These steps can also be interpreted as the challenge requirements in order to consider it complete.

1. Successfully detect where a human is in the frame and focus on one individual if multiple are present.
2. Locate the general area of the person's hand and crop the image so only the object they are holding is in focus.
3. Pass this image to an object detection algorithm and find the closest match (highest likelihood) object.
4. Read out the object to the user via PC speaker audio using a text-to-speech algorithm in the format `"You are a holding a {OBJECT}"`

**Bonus Points:**
1. Display the camera feed with a square marking where the algoirthm is detecting the object the user is holding (this will help greatly in debugging)
