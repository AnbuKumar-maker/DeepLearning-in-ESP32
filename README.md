# DeepLearning-in-ESP32
Object detection and identification is one of the most important and challenging branches of computer vision, which has been widely applied in peoples’ life, such as monitoring security, autonomous driving, and so on, with the purpose of locating instances of semantic objects of a certain class. With the rapid development of deep learning networks for detection tasks, the performance of object detectors has been greatly improved. By using Machine Learning and ResNet, we can easily identify the names of the objects which we needed. For this, firstly the training data is fed to the machine and labeled it correctly based on the nomenclature. By using the Camera Module, the test data is detected and verified with the train data using the ResNet algorithm. By repeated testing of the objects, the data set is updated or deleted based on the errors made by the machine in identification. On the repeated iteration of identifying the objects correctly ie., Accuracy reaching ≥ 95%, the dataset, and the application is used in Real World for automation. For this, I use Keras, an open-source neural-network library written in Python and by using the IoT module, the identified data is transferred to the Display device wirelessly. In Real-Time, this project is used for the identification of objects with more than 95% accuracy and transmit the data from anywhere and anytime using the cloud, and completely automate the process and reduces the manpower.  ESP32 :  Engineered for mobile devices, wearable electronics and IoT applications, ESP32 achieves ultra-low power consumption with a combination of several types of proprietary software. ESP32 also includes state-of-the-art features, such as fine-grained clock gating, various power modes and dynamic power scaling.
