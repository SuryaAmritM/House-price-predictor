[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SuryaAmritM/House-price-predictor/blob/main/house_price_predictor.ipynb)

# 🏠 House Price Predictor

This project predicts house prices using machine learning. Given inputs like area, number of bedrooms, location, builder, and property status, it estimates the price using a trained Random Forest model.

---

## 📊 Demo

The model was trained on a dataset of real property listings and can be run interactively via terminal in a Jupyter Notebook or Google Colab.

---

## 🧠 Model Details

- **Algorithm:** Random Forest Regressor
- **Encoding:** Label Encoding for categorical features
- **Evaluation Metric:** R² Score

---

## 📂 Features Used

- Area (in sqft)
- Number of BHK
- Number of bathrooms
- Age of property
- Location
- Builder
- Property Status (Ready to move / Under Construction)

---

## 🚀 How to Use

1. Clone or download this repo
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open `house_price_predictor.ipynb` in Jupyter or Colab
4. Run the final cell and input property details when prompted
5. View the predicted price in lakhs of ₹

---

## 📁 Files in This Repository

| File                          | Description                                   |
| ----------------------------- | --------------------------------------------- |
| `chennai_house_price.csv`     | Cleaned dataset used for training             |
| `house_price_predictor.ipynb` | The complete training and prediction notebook |
| `requirements.txt`            | Python package dependencies                   |
| `README.md`                   | This project overview                         |

---

## ✅ Sample Input & Output

Enter area in sqft: 1200
Enter number of BHK: 2
Enter number of bathrooms: 2
Enter age of the property (in years): 5
Enter location: Adyar
Enter builder: Casagrand Builder Private Limited
Enter status (Ready to move / Under Construction): Ready to move

🏠 Predicted Price: ₹58.50 lakhs

---

## ✨ Future Improvements

- Switch to OneHotEncoding or embedding for categorical features
- Add a Streamlit or Gradio UI
- Deploy as a web app

---

## 🧑‍💻 Author

Built by Surya Amrit M (https://github.com/SuryaAmritM)

---
