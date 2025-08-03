#  Personal Fitness Tracker

##  Overview  
This is a web application that predicts **calories burned** based on user input parameters such as age, gender, BMI, exercise duration, heart rate, and body temperature. The application uses **machine learning (Random Forest Regressor)** to make accurate predictions based on exercise and calorie data.

---

##  Features  
-  Interactive user interface with sliders for inputting personal parameters  
-  Real-time prediction of calories burned during exercise  
-  Comparison with similar results from the dataset  
-  Statistical comparison with other people in the dataset  

---

##  Technologies Used  
- **Streamlit**: For the web application interface  
- **Pandas & NumPy**: For data manipulation and analysis  
- **Scikit-learn**: For the machine learning model (Random Forest Regressor)  
- **Matplotlib & Seaborn**: For data visualization  

---

##  Dataset  
The application uses two datasets:  
- `calories.csv`: Contains calorie information for each user  
- `exercise.csv`: Contains exercise parameters including gender, age, height, weight, duration, heart rate, and body temperature  

---

## 🛠 Installation  

###  Prerequisites  
Ensure you have Python installed along with the following packages:
```bash
streamlit
pandas
numpy
matplotlib
seaborn
scikit-learn
```

You can install these packages using pip:
```
pip install streamlit pandas numpy matplotlib seaborn scikit-learn
```
---


### Running the Application
To run the application, navigate to the project directory and execute:
```
streamlit run app.py
```

The application will be available at http://localhost:8501 in your web browser.

---


## Usage
1. Adjust the sliders in the sidebar to input your parameters
2. View your predicted calories burned
3. Explore similar results from the dataset
4. Compare your statistics with others

---


## Project Structure
- `app.py`: Main application file with Streamlit interface and ML model
- `calories.csv`: Dataset containing calorie information
- `exercise.csv`: Dataset containing exercise parameters
- `fitness_tracker.ipynb`: Jupyter notebook for data exploration and model development
