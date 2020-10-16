# Intuitivo

Below is the list of the main libraries that we will use in AI Intuitivo.

## Installation Guide

Python >=  3.5

## Windows

There are three installation methods on Windows:

1- The Microsoft Store

2- The full installer


3- Windows Subsystem for Linux

## Linux

Check your version of Python by entering the following:

```bash
python ––version
```

Step 1: Update and Refresh Repository Lists
Open a terminal window, and enter the following:

```bash
sudo apt update
```

Step 2: Install Supporting Software
The software-properties-common package gives you better control over your package manager by letting you add PPA (Personal Package Archive) repositories. Install the supporting software with the command:

```bash
sudo apt install software-properties-common
```

Step 3: Add Deadsnakes PPA
Deadsnakes is a PPA with newer releases than the default Ubuntu repositories. Add the PPA by entering the following:

```bash
sudo add-apt-repository ppa:deadsnakes/ppa
```

The system will prompt you to press enter to continue. Do so, and allow it to finish. Refresh the package lists again:

```bash
sudo apt update
```

Step 4: Install Python 3
Now you can start the installation of Python 3.8 with the command:

```bash
sudo apt install python3.8
```

Allow the process to complete and verify the Python version was installed sucessfully:

```bash
python ––version
```

## Main Libraries

OpenCV >=  3.4.1

Sklearn

Tensorflow & Keras

Numpy & Scipy

Pathlib
