# Fitness_Freak_Object_Detection_using_Deep_Learning_and_OpenCV

# Sample Demo
![Farmers Market Finder Demo](/demo.gif)

This project can detect any of the food items among popular fruits(orange, apple, banana), vegetables (carrot, broccoli), fast food(pizza, sandwich) and sweets(cake, donut).
With further development this can be upscaled to detect thousands of different kinds of food.
Also this displays the result about user's diet sugession in order to gain or loose weight.

# Execution
Food Identification and Suggestion : $ python food_identification.py --image pizza.jpg --config yolov3.cfg --weights yolov3.weights --classes yolov3.txt

Object Detection: $ python object_detection.py --image pizza.jpg --config yolov3.cfg --weights yolov3.weights --classes yolov3.txt
