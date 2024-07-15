# K-means Clustering and Image Compression

This repository contains an implementation of the K-means clustering algorithm using Python. The algorithm is applied to both a dataset and an image for clustering and compression purposes.

## Description

The project is divided into two main parts:
1. **K-means Clustering on a Dataset**: The algorithm clusters a given dataset into a specified number of clusters and visualizes the results.
2. **Image Compression using K-means**: The algorithm compresses an image by reducing the number of colors using K-means clustering.

## Requirements

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- OpenCV
- Random

## Installation

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/your-username/kmeans-clustering.git
    ```
2. Navigate to the project directory:
    ```bash
    cd kmeans-clustering
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Ensure you have the necessary data files:
   - `kmean.xlsx` for the dataset
   - `tom.jpg` for the image compression example

2. Run the Python script:
    ```bash
    python kmeans_clustering.py
    ```

## File Structure

- `kmeans_clustering.py`: The main script containing the implementation of K-means clustering and image compression.
- `README.md`: This README file.
- `requirements.txt`: A list of required Python packages.

## Example Output

The script will display the following:
1. Scatter plots showing the clustering process over multiple iterations.
2. Side-by-side comparison of the original and compressed images.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request.

