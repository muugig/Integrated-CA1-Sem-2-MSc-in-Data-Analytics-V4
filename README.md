# Deep Learning Using Big Data in Recommendation Systems

## Table of Contents
- [Overview](#Overview)
- [Learning Outcomes](#Learning Outcomes)
- [Installation and Setup](#Installation and Setup)
- [Project Overview](#project-overview)
- [Installation](#installation)
- [Data](#data)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview
This project explores the application of deep learning techniques within the realm of Big Data to enhance recommendation systems. By leveraging large datasets, the aim is to improve the accuracy, efficiency, and personalization of recommendations provided to users. This integration seeks to address the challenges of scalability and dynamic adaptation in recommendation systems across various domains such as e-commerce, entertainment, and social networking services.

## Learning Outcomes
- **Data Management:** Assessment of storage and management requirements for handling Big Data in recommendation systems.
- **System Design:** Evaluation of architectural patterns suitable for distributed Big Data systems used in recommendation engines.
- **Algorithm Selection:** Critical analysis and selection of neural network algorithms for processing large-scale datasets, emphasizing scalability and real-time processing capabilities.

## Installation and Setup
1. **Clone the repository:**
   ```
   git clone https://github.com/yourusername/recommendation-system-bigdata.git
   ```
2. **Install dependencies:**
   ```
   pip install -r requirements.txt
   ```

## Usage
Follow these steps to run the project and analyze the outcomes:
1. **Launch the Jupyter Notebook:**
   ```
   jupyter notebook recommendation_system_demo.ipynb
   ```
2. **Execute the cells sequentially** to walk through the data preprocessing, model training, evaluation, and recommendation generation process.

## Technologies Used
- Python 3.8
- Jupyter Notebook
- TensorFlow 2.x for neural network models
- Apache Spark for Big Data processing
- Pandas and Numpy for data manipulation

## Data
This project utilizes the [MovieLens dataset](https://grouplens.org/datasets/movielens/), which contains millions of movie ratings. Preprocessing steps include normalization, user and item embedding, and data splitting for training and testing purposes.

## Features and Algorithms
- **Feature Engineering:** User demographics, movie metadata, and rating patterns are utilized as features.
- **Deep Learning Model:** A collaborative filtering approach using Convolutional Neural Networks (CNNs) to capture the complex patterns in user-item interactions.

## Results
The implementation demonstrates significant improvements in recommendation accuracy and personalization compared to traditional methods. Metrics such as Precision@K, Recall@K, and F1 Score are used to evaluate performance.

## Limitations and Future Work
- **Scalability:** While the project shows promising results, further optimization is needed for real-world scalability.
- **Dynamic Data:** Future iterations will explore models that can adapt more dynamically to new data without full retraining.

## Installation
This section should provide instructions on how to get your project running on another's machine. Specify requirements, libraries, and steps to install and set up your project. Example:

```bash
git clone https://your-repository-link.git
cd your-project-folder
pip install -r requirements.txt
```


## Data
takken from kaggle ml-100k
## Model
The implementation of the NCF model demonstrates notable effectiveness in predicting user ratings for movies, with a final test loss indicating the model's accuracy. The conversion of ratings to a binary like/dislike format and subsequent confusion matrix analysis provide additional insight into the model's practical utility in a recommendation system context. This approach underscores the potential of deep learning in enhancing the personalization and accuracy of Recommendation Systems, particularly when handling sparse and large-scale datasets. 


## Results
Results Visualization:

The plot delineating the preparation and approval misfortune over ages is created, showing the model's learning progress and intermingling conduct.
    • Loss: The y-axis represents the loss, which is a measure of how well the model is performing. A lower misfortune shows a superior attack of the model to the information.
    • Epochs: The x-axis indicates the epochs, showing the number of complete passes the machine learning algorithm has made through the entire training dataset.
    • Training Loss (Blue Line): This line shows the model's loss on the training set. We observe a sharp decline from the start, indicating that the model quickly learned from the initial state of relative ignorance about the data patterns.
    • Validation Loss (Orange Line): This line represents the loss on a validation set, which is separate from the data the model is trained on and is used to simulate the model's performance on unseen data. The approval misfortune diminishes and begins to smooth as the ages increment, recommending that the model is summing up well as opposed to overfitting.
    • Convergence: The two lines are converging, which is an indicator that the model is not overfitting the training data. Overfitting would be obvious in the event that the preparation misfortune kept on diminishing while the approval misfortune began to increment.
    • Stability: By the final epoch, both the training and validation loss values show little change, indicating that the model may have reached a point where further training will not result in significant improvements. This is where you'd consider stopping the training to prevent unnecessary computation and potential overfitting.


Prediction and Evaluation:

        ◦ Predictions are made on the test set, and a threshold of 3.5 is applied to convert continuous ratings into binary likes/dislikes.
        ◦ A confusion matrix is plotted to visualize the model's performance in categorizing the binary outcomes.

    • True Positive (TP) - Bottom Right: The model predicted the positive class correctly. In this case, there are 8221 instances where the model accurately predicted the class labeled '1'.
    • True Negative (TN) - Top Left: The model predicted the negative class correctly. There are 6020 instances where the model correctly predicted the class labeled '0'.
    • False Positive (FP) - Bottom Left: The model incorrectly predicted the positive class. This means that there are 2769 instances where the model predicted the class as '1', but it was actually '0'.
    • False Negative (FN) - Top Right: The model incorrectly predicted the negative class. There are 2990 instances where the model predicted the class as '0', but it was actually '1'.

## Contributing
If you're open to contributions, specify how others can contribute to your project. Outline any requirements for contributions, such as coding standards or testing procedures.

## License
State the license under which your project is released, allowing others to know how they can use, modify, or distribute your work.

## Contact
Provide your contact information or that of the project team for anyone who has questions or needs support. For example:
- email : igerlee63@gmail.com
- Email: [igerlee63@gmail.com)
- Project Link: [https://github.com/muugig/Integrated-CA1-Sem-2-MSc-in-Data-Analytics-V4/tree/master)

