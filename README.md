# SiameseNeuralNetwork-FaceRecognition

Bu proje, Siamese ağı kullanarak yüz doğrulama görevini ele almaktadır. Proje, Labeled Faces in the Wild (LFW) veri kümesi üzerinde gerçekleştirilmiştir ve yüzler arasındaki benzerlikleri öğrenmek için kullanılmıştır.

## Veri Kümesi

Bu projeyi çalıştırmak için LFW veri kümesine ihtiyacınız vardır. Veri kümesini Kaggle API ile indirebilir veya aşağıdaki linki kullanarak manuel olarak indirebilirsiniz:

[https://www.kaggle.com/datasets/jessicali9530/lfw-dataset](https://www.kaggle.com/datasets/jessicali9530/lfw-dataset)

## Gereksinimler

Bu projeyi çalıştırmak için aşağıdaki gereksinimlere ihtiyacınız vardır:
- Python 3.x
- TensorFlow veya Keras
- Jupyter Notebook veya bir Python IDE

GPU hızlandırma kullanmak istiyorsanız, NVIDIA GPU'lu bir sistem gerekebilir. Proje, Google Colab Pro gibi bulut tabanlı hizmetlerde veya yerel bir bilgisayarda çalıştırılabilir. Ayrıca, modelin karmaşıklığını azaltarak daha az GPU belleği kullanmayı deneyebilirsiniz.

## Proje Çalıştırma

1. Veri kümesini indirdikten sonra, projeyi bir Python geliştirme ortamında veya Jupyter Notebook'ta açın.

2. "Face Recognition with Siamese Neural Network .ipynb" adlı Jupyter Notebook dosyasını açın ve kodu çalıştırmaya başlayın. Bu dosya, Siamese ağını oluşturmanıza, eğitmenize ve test etmenize olanak tanır.

3. Proje çalıştığında, eğitim sonuçları ve test sonuçları görüntülenecektir.

## Sonuçlar

Bu projenin sonuçları oldukça başarılıdır. Test veri kümesi üzerindeki başarı oranı %97.3 olarak ölçülmüştür. Bu, Siamese ağlarının yüz doğrulama görevinde etkili olduğunu göstermektedir.

"***"

# Siamese Neural Network - Face Recognition

This project addresses the face verification task using a Siamese network. It is implemented on the Labeled Faces in the Wild (LFW) dataset and is used to learn similarities between faces.

## Dataset

To run this project, you need the LFW dataset. You can download the dataset using the Kaggle API or manually using the following link:

[https://www.kaggle.com/datasets/jessicali9530/lfw-dataset](https://www.kaggle.com/datasets/jessicali9530/lfw-dataset)

## Requirements

To run this project, you need the following requirements:
- Python 3.x
- TensorFlow or Keras
- Jupyter Notebook or a Python IDE

If you want to use GPU acceleration, you may need a system with an NVIDIA GPU. The project can be run on cloud-based services like Google Colab Pro or a local computer. Additionally, you can try reducing the model's complexity to use less GPU memory.

## Running the Project

1. After downloading the dataset, open the project in a Python development environment or Jupyter Notebook.

2. Open the Jupyter Notebook file named "Face Recognition with Siamese Neural Network.ipynb" and start running the code. This file allows you to build, train, and test the Siamese network.

3. Once the project runs, the training and test results will be displayed.

## Results

The results of this project are quite successful. The accuracy rate on the test dataset was measured at 97.3%, demonstrating that Siamese networks are effective for face verification tasks.


