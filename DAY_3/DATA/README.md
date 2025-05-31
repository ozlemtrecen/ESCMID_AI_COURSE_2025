# Data download and setup instructions for MALDI-TOF workshop

This document provides detailed instructions to download and set up the **DRIAMS B MALDI-TOF mass spectrometry dataset** required for the ESCMID AI and Machine Learning workshop.

---

## About the dataset: DRIAMS B

The **DRIAMS B database** is a large, high-quality collection of routine MALDI-TOF spectra acquired at the Canton Hospital Basel-Land. This dataset is approximately **3 GB** in size and contains spectral data for multiple bacterial and fungal species.

**Important:** Only download the **DRIAMS B** dataset, not the other DRIAMS subsets, as they are significantly larger and not required for this workshop.

---

## Using Google Colab for the Workshop

The workshop notebook is designed to run on **Google Colab**, a free, cloud-based Jupyter notebook environment provided by Google.

**Why use Google Colab?**

- It requires no installation of software or dependencies on your local machine.  
- Provides free access to GPUs and CPUs in the cloud.  
- Easy to share and collaborate on notebooks.  

However, Google Colab does **not** have persistent local storage, so all data must be uploaded or accessed through connected services like **Google Drive**.

---

## How to Prepare Your Data for Google Colab

1. **Download the DRIAMS B dataset** from the official Dryad repository:

   [https://datadryad.org/dataset/doi:10.5061/dryad.bzkh1899q#usage](https://datadryad.org/dataset/doi:10.5061/dryad.bzkh1899q#usage)

2. After downloading, you will have a compressed file named `driams_b.tar.gz`.

3. **Upload `driams_b.tar.gz` to your Google Drive** folder where you keep the workshop Colab notebook. This is essential because Colab can access files stored in your Google Drive.

---

## Mounting Google Drive in Colab

In the workshop notebook, the first code cell will:

- **Mount your Google Drive** to the Colab environment, allowing the notebook to read files directly from your Drive.  
- **Install necessary Python libraries** used for data processing and machine learning.  
- **Extract the dataset** from the uploaded compressed file (`driams_b.tar.gz`) to prepare it for analysis.

The mounting process will prompt you to authorize Google Colab to access your Google Drive. This is a standard and secure procedure.

---

## Important Tips

- Ensure that the `driams_b.tar.gz` file is uploaded **before** running the mounting and extraction cell in the notebook.  
- The extraction can take several minutes due to the dataset size, so please be patient.  
- If you have limited internet speed, start downloading the dataset well before the workshop session to avoid delays.

---

## Summary

| Step                          | Action                                                                                   |
|-------------------------------|------------------------------------------------------------------------------------------|
| 1                             | Download `driams_b.tar.gz` from Dryad repository                                        |
| 2                             | Upload `driams_b.tar.gz` to your Google Drive folder with the workshop notebook         |
| 3                             | Open the workshop notebook in Google Colab                                              |
| 4                             | Run the first code cell to mount Drive, install libraries, and extract the dataset      |
By following these instructions, you will have all the data ready and accessible to fully participate in the practical parts of the workshop.

---

If you encounter any issues with downloading, uploading, or mounting Google Drive, please reach out to the workshop instructors for assistance.
