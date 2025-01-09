# User-Churning
# Flow of the code

* Data Preprocessing: Involves loading the dataset, handling missing values, converting data types, and performing EDA.
* Feature Engineering: Creating RFM metrics, session-based metrics, and behavioral patterns.
* Clustering with HDBSCAN: Standardizing data, performing clustering, and visualizing clusters.
* Identifying Potential Churners: Calculating average values by cluster and filtering potential churners based on defined thresholds.

  # Process to run the code
  * The feature creation takes time and so to quickly analyse the results from created features directly, we have also add the user_features.csv file in the repo,which can be used directly to run the model(skipping the preprocessing and feature engineering steps)
 
  * Since the code uses GPU for faster execution, it should be run on CUDA enabled GPU's. I ran this code on both Kaggle and Colab. The initial installation of RAPIDS library and import statements will clarify if the GPU used has compatible CUDA version. If installation and import statements run successfully, the GPU is good to go.
 
  * The path to the files has to be adjusted according to the environment you are using.
