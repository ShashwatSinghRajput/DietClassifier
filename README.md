# DietClassifier
The goal is to create models that can automatically categorize food images based on their visual content. This task is interesting because it has practical applications in dietary monitoring and personalized nutrition planning, and it requires handling challenges related to diverse food appearances.

## Basic Component:

The basic assignment focuses on constructing a machine learning model that distinguishes between rice and chips in input image files. The notebook encompasses diverse experiments on the dataset, various feature extraction methods, and classification models. I created three different training datasets: the original, a version with applied data augmentation, and another with food area cropping. Particularly noteworthy is my unique approach to feature extraction, which involves cropping the food area based on the bounding box around regions with high saturation. For image classification, I opted for several popular classification models, including Logistic Regression, Support Vector Machine, Naïve Bayes, an ensemble model, and CatboostClassifier.

## Q. What is MLEnd Yummy dataset?

The Yummy dataset comprises food images collected by students, including myself, under the guidance of our amazing professor, Jesus Requena-Carrion, from Queen Mary University of London. It consists of a total of 3,250 images, accompanied by a metadata CSV file containing additional details such as food preferences and vegetarian categorization (MLEnd dataset documentation). This dataset holds significance as it represents raw images collected by students, serving as an excellent starting point for practicing image preprocessing and feature extraction.

🙌 Big thanks to Professor Jesus for giving us this chance to work hands-on from gathering data to building a machine learning system!
