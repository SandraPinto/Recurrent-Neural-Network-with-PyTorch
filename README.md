# SandraPinto-Recurrent-Neural-Network-with-PyTorch
DATA 602 FINAL RESEARCH PROJECT

SUMMARY

The name of the notebook I chose for my project is Recurrent Neural Network with PyTorch Tutorial from the Digit Recognizer Kaggle Competition using the popular MNIST data, which competition started 8 years ago (LINK TO NOTEBOOOK PROVIDED ON SOURCES SECTION BELOW). The notebook was created by the DATAI TEAM based in Turkey which has achieved the Notebooks grandmaster notation in Kaggle (DATAI TEAM,KAGGLE). My motivation to work with PyTorch instead of Tensorflow was to explore a DL framework that we have not discussed in class and apply it into creating a RNN (used for sequential data for text classifactions problems) to expand my skillset. Also, I was prompted to chose a high ranked notebook from a Kaggle competition.

PyTorch is a popular deep learning framework developed by Facebook mainly used in academia and research with the purpose to replace numpy-like operations with GPU-accelerated operations and Build deep neural networks. PyTorch provides two kinds of data abstractions called tensors and variables.Tensors are similar to numpy arrays and they can also be used on GPUs, which provide increased performance.According to the book Deep Learning with PyTorch the main pros of PyTorch are; ease of use and simplicity, easier-to-debug nature, dynamic computation which allows greater flexibility in building complex architectures(unlike other popular DL frameworks),extensive use of Python concepts to build algorithms in a pure oject-oriented fashion,and strong growing support from various companies such as Salesforce (Subramanian, 2018, page. 16). Along with the pros also come the cons, a third-party is needed for visualization and there are limited references and resources outside of the official documentation.

PyTorch and TensorFlow follow different approaches when it comes to visualization, deployment, development, and debugging. The Article PyTorch vs TensorFlow — spotting the difference, describes the main differeces between PyTorch and Tensorflow which are the following (Dubovikov,2018):

While TensorFlow is produced by Google, PyTorch is maintained by Facebook.
TensorFlow is older and has a larger community than PyTorch, which is a “new” version of the Torch library.
TensorFlow is widely used in industry, while PyTorch is often used in academia.
In terms of visualization Tensorflow does not need a third party unlike PyTorch
In terms of deployment, TensorFlow is better because it lets you deploy your models on a specialized gRPC service and mobile is also supported. Otherwise, Python may use a flask or another alternative to code up a REST API on top of the model
In TensorFlow you define the graphics statically before a model can be executed so it's more static.PyTorch is more imperative and dynamic. You can define, change and execute nodes as you like, no special session interfaces or placeholders.
I encountered a few problems which were mostly debugging such as “file not found error” which I addressed by looking for the corresponding library path and updating my notebook with the library path name based on how I saved the repository date files in my drive. I decided to mount my drive into my notebook instead of uploading the data files as sample data so they don't disappear after a new session. However, I learned that importing my data this way was not very effective when sharing my data as other authorized users were not able to re-run my codes. Therefore, I imported the data files by using the shareable drive url.

In the following lines we will be exploring building RNN using PyTorch and visualizing our findings.
