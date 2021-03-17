# Classification-of-Anomalies-in-Gastrointestinal-Tract-through-Endoscopic-Imagery-Using-CNN

![image](https://user-images.githubusercontent.com/62339931/111059431-7c0e6100-84bb-11eb-8c32-e6afc97aff93.png)

In this challenge, you will learn how machine learning can be applied to medical imaging.
You will use the human gastrointestinal (GI) tract endoscopic imagery in order to detect different anomaly types.

During this task you will explore KVASIR dataset. 

You should train a classification model on the given medical dataset to classify anomalies in Gastrointestinal Tract using endoscopic imagery. 
We recommend  using a Deep Convolutional Neural Network with transfer learning.


![image](https://user-images.githubusercontent.com/62339931/111059446-9b0cf300-84bb-11eb-8d75-8d4a92b444df.png)

The dataset consists of 8,000 annotated GI tract images in 8 different classes (different annomalies) where 1000 images belong to each class.

It contains anatomical landmarks; z-lines, pylorus and cecum, pathological finding; esophagitis, polyps, and ulcerative colitis and polyp removal signs ; dyed-lifted-polyps, dyed-resection-margins.

You can download the image dataset from
https://datasets.simula.no/kvasir/#download or 
https://datasets.simula.no/kvasir/data/kvasir-dataset.zip


![image](https://user-images.githubusercontent.com/62339931/111059452-a3fdc480-84bb-11eb-9bac-5a860435dbbe.png)

* Keras: Keras is a popular deep learning framework. Read and follow this tutorial, Installing Keras with the TensorFlow backend.

* NumPy & Scikit-learn: If you followed the Keras install instructions linked directly above, these packages for numerical processing and machine learning will be installed.

* Matplotlib: The most popular plotting tool for Python. Once you have your Keras environment ready and active, you can install via pip install matplotlib .


Before the use this source code you have to go through following steps.

STEP 1-Installing Python3, Pip  and set environment variables.
(For more details - https://phoenixnap.com/kb/how-to-install-python-3-windows)

STEP 2 - Installing Keras with the TensorFlow backend and a few python dependencies. 
You can open a Command Prompt and run following Command.

	* Installing NumPy & Scikit-learn .
		pip install numpy 
		pip install scikit-learn	

	* Installing Keras with the TensorFlow backend. 
		pip install --upgrade tensorflow
		pip install keras 

	* Installing Matplotlib for plotting.
		pip install matplotlib

	* Installing split-folders.
		pip install split-folders

	* Installing seaborn to visualize model accuracy.
		pip install seaborn
	
	
STEP 3 - Getting source code.

Use Zip folder to get source code.
Create new folder and Unzipping that Zip folder in that new folder. 

or 

Cloning git project to get source code. 
Create a new folder and open a Command Prompt from this direction and run following command.

git clone https://github.com/LahiruKumaraHewagama/Classification-of-Anomalies-in-Gastrointestinal-Tract-through-Endoscopic-Imagery-Using-CNN.git
 
STEP 4 - Downloading Dataset  [ kvasir-dataset-v2.zip (size 2.3 GB) ]  .
Use this link https://datasets.simula.no/kvasir/#download for downloading data sets. 

After downloading , copy this dataset folder to pervious folder .
 

STEP 5- Then Open a new Command Prompt from pervious folder and Open Jupyter notebook using following command. Then automatically will be open jupyter  notebook from browser window and click CNN MODEL(Team - NullPointers).ipynb file to open source file.

	jupyter notebook
![jupyter notebook](https://user-images.githubusercontent.com/62339931/111424224-7745e900-8717-11eb-9e35-946739f11c29.JPG
 

STEP 6 - Change Dataset path for your location as following .
 
 ![change direc](https://user-images.githubusercontent.com/62339931/111424074-3fd73c80-8717-11eb-943b-ddbdb488cc1a.png)

input_dir=os.path.join(r'<Your location>\kvasir-dataset-v2')
output_dir = os.path.join(r'<Your location>\kvasir-dataset-v2_splitted')

train_dir = os.path.join(r'<Your location>\kvasir-dataset-v2_splitted\train')
test_dir = os.path.join(r'<Your location>\kvasir-dataset-v2_splitted\val')
 





STEP 7 - Run each by each using "Run" button .
 
 ![run](https://user-images.githubusercontent.com/62339931/111424227-77de7f80-8717-11eb-86f2-0c0965910571.png)


STEP 8 - After all steps you can check prediction of model using testing dataset.
For this you can change index of image in testing dataset and can see predict Anomalies and correct Anomalies.
 
