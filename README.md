# 🗑️ Waste Segregation using Deep Learning

A computer vision-based project to classify and segregate waste using image recognition techniques.

---

## Project Description

This project uses a deep learning model trained on image data to automatically classify waste into different categories.  
The goal is to aid smart and sustainable waste management systems by helping machines identify recyclable and non-recyclable waste through image input.

---

## Author

**Ali Akbar Khan**

---

## Technologies Used

- Python  
- Fastai  
- PyTorch  
- Gradio (for UI)  
- Jupyter Notebook  

---

## Model Details

- **Architecture**: `resnet18` pretrained CNN  
- **Training**: Fine-tuned for 10 epochs using Fastai's `vision_learner`  
- **Metrics**: Achieved high accuracy (close to 92%) on validation set  

---

## Dataset

The dataset contains labeled images of different types of waste, categorized into classes like:

- Recyclable  
- Organic  
- Hazardous  
- Others (can be customized)  

---

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/aliiakbarkhan/deep-learning-waste-segregation.git
cd deep-learning-waste-segregation
```
### 2. Install dependencies
```bash
pip install -r requirements.txt
```
### 3. Run the notebook

Use Jupyter or VSCode to open waste-segregation.ipynb and run all cells.

### 4. Or launch Gradio app (if available)
```bash
python app.py
```
### Sample Predictions
The model can take any image of waste and classify it into one of the predefined categories with high accuracy.
Here's a snapshot of predictions from the Gradio interface.

<img src="https://github.com/aliiakbarkhan/deep-learning-waste-segregation/blob/main/output.png" />

### File Structure
```bash
waste-segregation/
├── waste-segregation.ipynb     # Main notebook
├── model.pkl                   # Trained model (optional)
├── app.py                      # Gradio app (if created)
├── README.md                   # Project documentation
└── requirements.txt            # Dependencies
```



