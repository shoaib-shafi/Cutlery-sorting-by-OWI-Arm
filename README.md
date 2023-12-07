# Cutlery-sorting-by-OWI-Arm
We trained a model to detect cutlery (spoon, knife and fork) using the ITR_classification code and custom dataset prepared available at https://drive.google.com/drive/folders/1bHtX5kG2KwCK9zC9D-65TDonZhptYK6F?usp=drive_link.

We used two cameras one to detect and another to provide feedback for movement of OWI robot in workspace.
The steps of operation include following:

i) Detect the position of cutlery on ground.

ii) Move the robot to the position of cutlery.

iii) Detecting the type of cutlery whether it is a spoon, fork or knife.

iv) Pick up the detected cutlery using the modified electromagnet end effector.

v) Placing the cutlery to a desired location based on it's detection using color thresholding.

