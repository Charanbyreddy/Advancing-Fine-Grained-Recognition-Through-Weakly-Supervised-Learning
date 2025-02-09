## 🚗🔍 Fine-Grained Image Classification
   - This project focuses on fine-grained image classification to distinguish between visually similar categories.
    It integrates traditional feature extraction techniques like HOG + SVM and HOG + MLP with advanced deep learning architectures like ELLF + CNN. 
    Additionally, it leverages Weakly Supervised Learning techniques to enhance model performance even with limited labeled data.
---

## **🚀 Key Features**

- **HOG + SVM**: Classic edge detection with SVM for model classification.
- **HOG + MLP**: Deep representation of HOG features using Multi-Layer Perceptrons.
- **ELLF + CNN**: Ensemble models leveraging CNNs for fine-grained recognition.
- **Weakly Supervised Learning**: Enhances performance with minimal labeled data.

---

## **🔍 Methodology**

### **1. HOG + SVM**

- **HOG (Histogram of Oriented Gradients)** is used to detect edges and shapes.
- **SVM (Support Vector Machines)** is applied to classify vehicles based on these features.



---

### **2. HOG + MLP**

- **HOG features** are fed into a **Multi-Layer Perceptron (MLP)**, which learns non-linear patterns in the data for improved accuracy on complex images.

---

### **3. ELLF + CNN**

- The **Ensemble of Localized Learned Features (ELLF)** method employs CNNs to extract localized, high-resolution features from images, focusing on minute differences between classes.
- This method achieves superior accuracy compared to traditional techniques.



---

## **📈 Results**

| **Model**        | **Accuracy** | **Precision** | **Recall** |
|------------------|--------------|---------------|------------|
| HOG + SVM        | 85%          | 84%           | 83%        |
| HOG + MLP        | 88%          | 87%           | 86%        |
| **ELLF + CNN**   | **95%**      | **94%**       | **93%**    |

---

## **🛠️ How to Run**

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/FineGrain-Image-Classification.git
   cd FineGrain-Image-Classification
