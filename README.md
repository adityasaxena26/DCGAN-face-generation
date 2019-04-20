# Deep Learning Nanodegree
## Generative Adversarial Networks
## Project: Face Generation

## Project Overview
In this project, you'll use generative adversarial networks to generate new images of faces.


Since the celebA dataset is complex and if you are implementing GANs in a project for the first time, it would be recommended to test your neural network on MNIST before CelebA.  Running the GANs on MNIST will allow you to see how well your model trains sooner.

If you're using [FloydHub](https://www.floydhub.com/), set `data_dir` to "/input" and use the [FloydHub data ID](http://docs.floydhub.com/home/using_datasets/) "R5KrjnANiKVhLWAkpXhNBe".

### Get the Data
You'll be using two datasets in this project:
- [MNIST](http://yann.lecun.com/exdb/mnist/)

  The MNIST dataset contains images of handwritten digits. The MNIST database of handwritten digits has a training set of 60,000 examples, and a test set of 10,000 examples. It is a subset of a larger set available from NIST. The digits have been size-normalized and centered in a fixed-size image.
- [CelebA](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)

  CelebFaces Attributes Dataset (CelebA) is a large-scale face attributes dataset with more than 200K celebrity images, each with 40 attribute annotations. The images in this dataset cover large pose variations and background clutter. CelebA has large diversities, large quantities, and rich annotations, including

    - 10,177 number of identities,

    - 202,599 number of face images, and

    - 5 landmark locations, 40 binary attributes annotations per image.

## Software and Libraries
This project uses the following software and Python libraries:

* [Python](https://www.python.org/download/releases)

* [NumPy](http://www.numpy.org/)

* [Matplotlib](http://matplotlib.org/)

* [Tensorflow](https://www.tensorflow.org)

You will also need to have software installed to run and execute a
[Jupyter Notebook](http://ipython.org/notebook.html).

If you do not have Python installed yet, it is highly recommended
that you install the [Anaconda](http://continuum.io/downloads)
distribution of Python, which already has the above packages and more included.

### Project Instructions
Clone the repository and navigate to the downloaded folder.
  ```
  git clone https://github.com/adityasaxena26/DCGAN-face-generation.git
  cd DCGAN-face-generation
  ```
Run the following to open up the notebook server:
```  
jupyter notebook
```
In your browser, open adi_face_generation.ipynb
