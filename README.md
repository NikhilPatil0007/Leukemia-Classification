
# Leukemia Classification

This repository contains code for leukemia classification using deep learning models **VGG16** and **EfficientNetB3**. The project aims to classify leukemia from medical imaging data.

## 📂 Project Structure
```
Leukemia-Classification/
├── Classification_using_VGG16_EfficientNetB3.ipynb  # Main notebook for training and evaluation
├── data/                                            # Dataset folder (not included in the repo)
├── results/                                         # Results and visualizations
├── requirements.txt                                 # Python dependencies
└── LICENSE                                          # License file
```

## 📊 Dataset
The dataset used for this project contains high-resolution medical images of leukemia.  
**Dataset Source**: CNMC  
[Download Dataset](https://www.cancerimagingarchive.net/collection/c-nmc-2019/)

> **Note**: Due to size limitations, the dataset is not included in this repository. After downloading, place the dataset in the `data/` folder.

## ⚙️ Requirements
Install the required dependencies by running:
```bash
pip install -r requirements.txt
```

## 🚀 Usage
Follow these steps to run the project:

1. Clone the repository:
   ```bash
   git clone https://github.com/NikhilPatil0007/Leukemia-Classification.git
   cd Leukemia-Classification
   ```

2. Download the dataset and place it in the `data/` folder.

3. Open the notebook in Jupyter:
   ```bash
   jupyter notebook Classification_using_VGG16_EfficientNetB3.ipynb
   ```

4. Follow the instructions in the notebook to preprocess data, train the models, and evaluate the results.


## 💡 Future Work
- Experiment with additional deep learning models.
- Implement advanced augmentation techniques to improve accuracy.
- Explore deployment options for real-time predictions.

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repository, raise issues, or submit a pull request.

## 📄 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

