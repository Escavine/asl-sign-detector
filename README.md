# asl-sign-detector
This is for the software development for my A-level Computer Science project, it utilises a pre-trained neural network known as SSD-Mobile Net which takes in the manually collected and labelled images for training and testing via transfer learning. It also allows for testing in real-time and represents 8 different ASL symbols accurately.

The repository that was used, I had made changes to it within the Jupyter Notebook to train for different ASL symbols (transfer learning) and to allow for the extraction of the model to enable the development of the web-app.

Alongsides this, I've also saved the model into JSON format and a frozen graph model in .config file to get the relevant checkpoints for web-app integration.


## Credits
- https://github.com/nicknochnack/RealTimeObjectDetection - Nick Renotte
