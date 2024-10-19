# Linear Code Image Compression

This repository explores the concepts of linear codes, vector spaces, and their application in image compression using Python and SageMath.  It focuses on using an orthogonal basis for lossy image compression, demonstrating the trade-off between compression level and image quality.

## Overview

This project dives into two main areas:

1. **Error Correcting Codes:** Investigates repetition and parity codes, highlighting their capabilities and limitations in correcting single and multiple bit errors.  It also introduces the concept of linear codes using generator matrices and provides Python functions for encoding with repetition and parity methods.

2. **Lossy Compression:** Focuses on image compression using an orthogonal basis in R^8. It covers:

    * Understanding basis vectors and linear combinations in the context of an image.
    * Demonstrating the orthogonality of a given set of vectors.
    * Finding the coordinates of a vector in the new basis.
    * Applying compression using different thresholds and visualizing the results.
    * Experimenting with compression thresholds to observe the impact on image quality.


## Code Structure

The code is organized into Jupyter Notebook cells, alternating between Markdown explanations and SageMath/Python code blocks.  This allows for a clear and interactive exploration of the concepts.

Key files:

* `Deep Dive #2 - Vector Spaces.ipynb`: The main notebook containing the code and explanations for error correcting codes and image compression.

## Usage

To run the code, you will need a SageMath environment (e.g., CoCalc) or a Python environment with the necessary libraries installed (NumPy, matplotlib).  Simply open the `.ipynb` file and execute the cells.

## Key Concepts

* **Vector Spaces:** Understanding the fundamental properties of vector spaces and how they relate to image representation.
* **Orthogonal Basis:**  Using an orthogonal set of vectors as a basis for image compression.
* **Linear Transformations:** Applying linear transformations (using generator matrices) for encoding and decoding.
* **Lossy Compression:**  Trading off image quality for reduced data size by discarding information below a certain threshold.
* **Error Correcting Codes:** Using redundancy to detect and correct errors in transmitted data.


## Results

The project demonstrates the effectiveness of using an orthogonal basis for image compression.  By adjusting the threshold, we can control the amount of compression and the resulting image quality.  Visualizations are provided to illustrate the impact of different threshold values.

## Further Exploration

This project provides a foundation for exploring more advanced image compression techniques, such as using different orthogonal bases (e.g., Discrete Cosine Transform) or applying more sophisticated thresholding methods.

## Tools Used

* SageMath
* Python (NumPy, matplotlib)
* Jupyter Notebook
* LaTeX (for mathematical notation within the notebook)
* Whisper API (for voice transcription)
* GPT-3 (for text refinement and LaTeX formatting)
* CoCalc AI debugger

## Acknowledgements

This project was inspired by the linear algebra concepts covered in CS113. Special thanks to Prof. John Levitt for guidance and insightful discussions.  Additionally, AI tools like Whisper API and GPT-3 were utilized for enhancing the clarity and presentation of the work.
