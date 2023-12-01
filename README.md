# Smart-Watch-Sensor-Data-Analysis-
# Dataset
Utilizing the WISDM Smartphone and Smartwatch Activity and Biometric dataset with data from 51 participants and a smartwatch capturing acceleration data.

Subject-id: Symbolic numeric identifier (1600-1650)
Activity Code: Symbolic letter (A-S, excluding "N")
Timestamp: Linux time
x, y, z: Accelerometer sensor readings for axes
# Data Selection
Focus on accelerometer data for activity identification. Randomly selected subset participants (1618, 1619, 1620) for proof of concept, ensuring diversity.

# Data Analysis
Preprocessing
Handling Missing Values:

Examined and treated as per study requirements.
Outliers:

Retained due to potential informative content.
Scaling:

Used standard scalar for uniform scaling.
Encoding:

One-hot encoded categorical variables.
PCA:

Reduced dimensionality to address overfitting.
Splitting:

Data split into 80:20 training and testing sets.
# Machine Learning Models
1. Random Forest(RF)
2. Decision Tree
