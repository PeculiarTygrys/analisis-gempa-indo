# analisis-gempa-indo
Gempa bumi di laut umumnya disebabkan oleh pergerakan lempeng tektonik di dasar laut. Ketika lempeng-lempeng ini bertabrakan dan salah satu menyelam di bawah yang lainnya, tekanan yang terbentuk dapat menyebabkan gempa bumi. Gempa bawah laut seringkali memicu tsunami dan gelombang besar yang dapat merusak pantai dan mengancam keselamatan. Oleh karena itu, pemantauan lempeng tektonik sangat penting untuk mitigasi tsunami dan sistem peringatan dini.

## Data Understanding
tgl: tanggal acara

ot: stempel waktu kejadian

lat: garis lintang pusat kejadian (derajat), mulai dari 6N hingga 11S

lon: bujur pusat gempa (derajat), mulai dari 142E hingga 94E

depth: kedalaman kejadian (km)

mag: magnitudo kejadian, mulai dari 1 hingga 9,5

## Visualization Result
Indeks besaran gempa dikelompokan berdasarkan tanggal
![image](https://github.com/user-attachments/assets/e17cc9b3-69c9-413e-8287-be7accfcbb4c)
Indeks besaran gempa jika dilihat di dalam kalender
![image](https://github.com/user-attachments/assets/57c9966f-635f-48f7-8270-166e388a64de)
Peta sebaran gempa di Indonesia
![image](https://github.com/user-attachments/assets/ee4040ec-f626-4aed-8917-f056fc097b54)

## Technologies
Python Version: 3.6
Plugin: Pandas, Numpy, Missingno, Plotly

## Setup
Jupyter Notebook Setup Guide

This guide explains how to set up Python and Jupyter Notebook for your project.
Prerequisites

    Python 3.x installed on your machine. You can download it from python.org.
    pip (Python package manager) installed (usually comes with Python installation).

Installation
1. Install Python

    Windows: Download and run the installer from the official website. Make sure to check the "Add Python to PATH" option during installation.
    Mac/Linux: Python is usually pre-installed. If not, you can install it using package managers like brew (Mac) or apt-get (Linux).

2. Install Jupyter Notebook

Once Python is installed, open a terminal or command prompt and run the following command to install Jupyter Notebook:

bash

pip install notebook

3. Launch Jupyter Notebook

After installation, you can start Jupyter Notebook by running the following command:

bash

jupyter notebook

This will launch the Jupyter Notebook interface in your default web browser.
4. Optional: Installing Multiple Python Versions

If you have multiple Python versions installed or are using virtual environments, you can install different kernels for each environment.

To do this, follow these steps:

    Install the ipykernel package:

    bash

pip install ipykernel

Add the desired Python environment as a new kernel:

bash

    python -m ipykernel install --user --name=env_name

Replace env_name with the name of your environment.
5. Optional: Using Virtual Environments

To isolate dependencies, it's a good idea to use virtual environments. Here's how to set one up:

    Create a virtual environment:

    bash

python -m venv myenv

Activate the environment:

    Windows: myenv\Scripts\activate
    Mac/Linux: source myenv/bin/activate

Install Jupyter Notebook inside the environment:

bash

pip install notebook

Add the virtual environment as a kernel:

bash

    python -m ipykernel install --user --name=myenv

Contributing

Feel free to submit issues or pull requests if you find any bugs or want to add improvements to this guide.
License

This project is licensed under the MIT License. See the LICENSE file for details.

## Credits
Project ini digunakan untuk memenuhi tugas Topik Khusus dengan anggota
Annisa Ramadhanti - 11210930000010
Muhammad Shofian Tshauri - 11210930000012
Muhammad Sharhan Khatami - 11210930000026
