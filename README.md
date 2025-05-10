# 📊 Customer Preferences Analysis using Machine Learning

This project explores customer purchase preferences using classification models and data visualization techniques. The objective is to identify trends in customer behavior and provide insights that could power smarter product recommendations, similar to approaches used in collaborative filtering systems.

## 🧠 Project Overview

The notebook performs the following tasks:

- **Data Loading and Preprocessing**  
  - Reads customer preference data  
  - Handles missing values  
  - Encodes categorical variables  
  - Normalizes the dataset  

- **Exploratory Data Analysis (EDA)**  
  - Visualizes feature distributions  
  - Explores relationships between features and customer decisions  

- **Model Building and Evaluation**  
  - Trains multiple classification models including:
    - K-mediods  
    - Hirarical classification    

## 🧰 Technologies Used

- Python 3.x  
- jupter Notebook  
- Libraries:
  - `pandas`, `numpy` – data manipulation  
  - `matplotlib`, `seaborn` – data visualization  
  - `sklearn` – model training and evaluation  

## 📈 Results

The models help in understanding:
- What product features drive customer interest
- Which classification technique performs best in predicting customer preferences

These insights can serve as a building block for more advanced systems, like recommendation engines—potentially using collaborative filtering or optimization techniques (e.g., Particle Swarm Optimization) to fine-tune personalization at scale.

## 🚀 How to Run

1. Clone the repository  
2. Install required packages:  
   ```
   pip install -r requirements.txt
   ```
3. Launch the notebook:  
   ```
   jupyter notebook customers'_preferences_project.ipynb
   ```

## 📌 Future Work

- Expand dataset for better generalization  
- Integrate with a recommendation system pipeline  
- Use ensemble models or neural networks for improved accuracy  
- Optimize hyperparameters using swarm intelligence algorithms  

## 📃 License

This project is open-source under the MIT License.
