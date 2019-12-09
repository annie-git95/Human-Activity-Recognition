# Human-Activity-Recognition
Human activity recognition (HAR) plays a crucial role in people’s daily life for its competence in learning profound high-level knowledge about human activity. In this project, we apply different types of  Deep Learning techniques to discover which method performs the best in terms of: Generalization, Accuracy, f1-score, precision, recall, Time given minimal  data- preprocessing & transformation.

Data Source used is from Wireless Sensor Data Mining Lab (Fordham University). It has 1,098,203 records from 36 users.
The users carried the Android phone in their front pants leg pocket and were asked to perform activities for specific periods of time. The accelerometer data was collected every 50ms, therefore,  we had 20 samples per second.

x_axis captures horizontal movement of the user’s leg
y_axis captures the upward and down-ward motion
z_axis captures the forward movement of the leg.
The 6 activities classified by our models are:
Walking
Jogging
Sitting
Standing
Downstairs
Upstairs

As you will see in the notebook, CNN-LSTM and ConvLSTMs perform the best for this type of task. 
