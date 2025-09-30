
---

# 🐾 Sea Animals Classifier

**Sea Animals Classifier** is a machine learning project developed in Python that classifies images of marine animals into predefined categories. Utilizing convolutional neural networks (CNNs), this model aims to accurately identify various marine species from image data.

## 📸 Dataset

The model is trained on a curated dataset of marine animal images, encompassing a diverse range of species. The dataset is preprocessed to standardize image sizes and normalize pixel values, ensuring optimal performance during training.

## ⚙️ Technologies Used

* **Programming Language**: Python 3.10.11
* **Libraries**:

  * `TensorFlow` / `Keras` – for building and training the CNN model
  * `NumPy` – for numerical operations
  * `Pandas` – for data manipulation
  * `Matplotlib` and `Seaborn` – for data visualization
* **Modeling Techniques**:

  * Convolutional Neural Networks (CNNs)
  * Data augmentation to improve model generalization

## 🛠 Features

* Image preprocessing and augmentation
* Model training and evaluation
* Performance metrics (accuracy, precision, recall, F1-score)
* Visualization of training and validation metrics

## 📁 Project Structure

* `mln_sea_animals_model.ipynb` – Jupyter notebook containing the main code for data preprocessing, model building, training, and evaluation
* `requirements.txt` – List of required Python packages

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/PawelJakubczyk/mln_sea_animals_classifier.git
   cd mln_sea_animals_classifier
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebook:

   ```bash
   jupyter notebook mln_sea_animals_model.ipynb
   ```

## 📈 Results

The classifier demonstrates high accuracy in identifying marine animals from images. Detailed performance metrics and visualizations are provided in the Jupyter notebook.

## 📄 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

---

