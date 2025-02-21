# Fine-Tuning VGG19 on the CIFAR10 Dataset

## Model Overview
<img width="808" alt="Screenshot 2025-02-17 at 16 44 10" src="https://github.com/user-attachments/assets/b7b9e3e9-bd14-418f-b510-e422c8d996c7" />

## Description
This model uses [VGG19](https://www.tensorflow.org/api_docs/python/tf/keras/applications/VGG19) which is an already trained AI model on the
[Imagenet Dataset](https://www.image-net.org/challenges/LSVRC/index.php) as a base-model. The training is done by freezing the appropriate pretrained layers *VGG19* and modifying the learning rate to fit the use of the model. The model was trained and tested using the [CIFAR10 DATASET](https://www.cs.toronto.edu/~kriz/cifar.html) to make predictions on 10 classes, achieving a validation accuracy of 83.6%.  

## Model Output
After training, the model obtained a validation accuracy of 83.6% (0.836)   
![result](https://github.com/user-attachments/assets/9712f345-d786-4fdd-a380-0b5f1229213a)

## Usage
**Clone the Project**

To clone this repository, use the following command:

```bash
git clone https://github.com/Bibliophiles/Fine-Tuning_VGG19_on_CIFAR10.git
```

These instructions are for running this project in Google Colab after cloning the repository.

Open Google Colab: Go to https://colab.research.google.com/.

**Upload the Notebook:**

In Colab, click "File" -> "Upload notebook". Navigate to the cloned repository on your local machine and select the .ipynb file.   

## Watch the Build on YouTube   

![thumbnail](https://github.com/user-attachments/assets/b4507c7b-9661-40ff-9a36-12efdb741ac8)   
*[View on YouTube](https://youtu.be/A26Tjvv_DLA?si=dsSKMges0KZ41ZR1)*
