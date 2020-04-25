# Emoji_Recognition
This code helps you to recognize and classify different emojis. As of now, we are only supporting hand emojis.

#Description
Emojis are ideograms and smileys used in electronic messages and web pages. Emoji exist in various genres, including facial expressions, common objects, places and types of weather, and animals. They are much like emoticons, but emoji are actual pictures instead of typographics.

#Functionalities
Filters to detect hand.
CNN for training the model.

#Python Implementation
Network Used- Convolutional Neural Network

#Procedure
1.First, you have to create a gesture database. For that, run CreateGest.py. Enter the gesture name and you will get 2 frames displayed. 2. Look at the contour frame and adjust your hand to make sure that you capture the features of your hand. Press 'c' for capturing the images. It will take 1200 images of one gesture. Try moving your hand a little within the frame to make sure that your model doesn't overfit at the time of training.
3.Repeat this for all the features you want.
4. Run CreateCSV.py for converting the images to a CSV file
5. If you want to train the model, run 'TrainEmojinator.py'
6. Finally, run Emojinator.py for testing your model via webcam.

Reference from: https://github.com/akshaybahadur21/Emojinator
