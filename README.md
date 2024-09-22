
#  Coral Reef Fish Species Diversity Prediction 

Welcome to the Coral Reef Fish Species Diversity Prediction project! 
We're diving deep into the colorful world of coral reefs to predict the diversity index of fish species based on environmental and anthropogenic factors.

## Project Overview 
The goal of this project is to build a machine learning model that predicts the **Diversity Index** of fish species in coral reef ecosystems. We've got data on coral cover, sea surface temperature, reef complexity, and more!

With this project, we hope to contribute to a better understanding of biodiversity in coral reefs and help with conservation efforts. Plus, it's a great excuse to play with some cool data and machine learning models!

## Steps to Reproduce
Want to replicate what we've done? No worries, follow these steps and you'll be swimming with predictions in no time! 

1. **Clone this repository**
   ```
   git clone https://github.com/yourusername/coral-reef-ml-project.git
   cd coral-reef-ml-project
   ```

2. **Install the required libraries**
   Install the dependencies listed in the `requirements.txt` file:
   ```
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook** 🚀  
   Fire up Jupyter Lab and run through the notebook step by step:
   ```
   jupyter lab Coral_Reef_ML_Project.ipynb
   ```

4. **Data** 
   The dataset contains 109 fish species and various environmental variables such as:
   - **Coral Cover** 
   - **Reef Complexity** 
   - **Sea Surface Temperature (SST)** 
   - **Depth** 
   - **Fishing Impact**
   
   These features were cleaned, transformed, and used to train a predictive model for the **Diversity Index** (a score from 0 to 1). The higher the diversity, the more species and the healthier the ecosystem!

5. **Models We Trained** 
   We tried out several models including:
   - **Linear Regression**: Our baseline model for predicting diversity.
   - **Random Forest Regressor**: Handles non-linear relationships like a champ!
   - **XGBoost Regressor**: The ultimate model that beat them all, winning the fishy race 🐠 with the lowest error and highest accuracy!

6. **Model Performance**   
   Our best model was XGBoost, with:
   - **MSE**: 0.07
   - **R²**: 0.72  
   Not bad for predicting the richness of underwater life

## Contributing 
Found an issue? Have a suggestion? We’d love to hear your thoughts!

## License
This project is open-source and licensed under the MIT License.

---

Now go ahead, train those models, predict fish diversity, and save the coral reefs! 
