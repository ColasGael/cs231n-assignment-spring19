# Solutions to CS231n assignments
**Version: Spring 2019**

This repository gathers my personal solutions to the CS231n assignments for the Spring 2019 offering. [CS231n](http://cs231n.github.io/) is a course on "Convolutional Neural Networks for Visual Recognition" given at Stanford University.

My solutions are compatible with **Python 3.7**. I used **PyTorch 1.0** as a Deep Learning framework.

## Unsolved assignments
Download the unsolved assignments here:
* Assignment 1: http://cs231n.github.io/assignments2019/assignment1
* Assignment 2: http://cs231n.github.io/assignments2019/assignment2
* Assignment 3: http://cs231n.github.io/assignments2019/assignment3

## Course content
If you want to learn the theory behind these assignments, you can find the course notes on the [CS231n website](http://cs231n.github.io/).

You can also watch the lecture videos from the Spring 2017 offering of this course on [YouTube](https://www.youtube.com/watch?v=vT1JzLTH4G4&list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv).

Finally GitHub user "mbadry1" put together a very clever summary of the lectures in this [repository](https://github.com/mbadry1/CS231n-2017-Summary). Don't forget to thank him if you find this summary useful!

## Setup
* For all the assignments, first follow the the CS231n [setup instructions](http://cs231n.github.io/setup-instructions/) to install the necessary virtual environment.
* If you want to work on Google Cloud, you can follow their tutorial on this [repository](https://github.com/cs231n/gcloud/).
* For **assignment 1 and 2**: to download the CIFAR-10 datasets needed for the assignments, run the following from the "assignment1" directory:
```
cd cs231n/datasets 
./get_datasets.sh
```
* For **assignment2**, also run the following from the "assignment2" directory:
```
cd cs231n
python setup.py build_ext --inplace
```
* For **assignment 3**: to download the COCO datasets needed for the assignment, run the following from the "assignment3" directory:
```
cd cs231n/datasets\\
./get_assignment3_data.sh
```

## Disclaimer
The goal of this repository is to help students interested in learning more about Computer Vision. Doing these assignments is a valuable way to learn the concepts and understand the implementations of Deep Learning methods. This repository provides a way to check the solutions.

By any mean should Stanford students currently enrolled in CS231n refer to these solutions. This constitutes a [Honor Code](https://communitystandards.stanford.edu/policies-and-guidance/honor-code) violation.

Finally, these are my personal solutions and should not be considered as the ground truth. If you spot some mistakes or imprecisions, feel free to open an issue.

## Acknowledgment
I would like to thank the Professors, Justin Johnson, Fei-Fei Li, Serena Yeung and Andrej Karpathy for putting together this amazing course! A special thanks for making all the resources available to the public.
I would also like to thank the teaching staff, all the Teaching Assistants, for making this course run smoothly and for helping out students.
