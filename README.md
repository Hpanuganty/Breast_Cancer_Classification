# Breast_Cancer_Classification
### Logistic regression and neural network models to classify breast cancer tumors as malignant or benign based on digitized biopsy images 

This dataset is publicly available on [Kaggle](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data) and looks at the physical features of a breast mass from digitized images from a file needle aspirate biopsy.

Breast cancer is the second leading cause of cancer death in women, with over 250,000 affected in 2018. Misdiagnoses of benign and malignant tumors can be detrimental towards treatment efforts as treatment options differ greatly between the two. This dataset consists of biopsies from breast cancer patients in Wisconsin and the database is UCI’s Machine Learning Repository.

The goal of this project is to _determine whether a breast mass tumor is malignant or benign based on several different physical factors._

### Classes and Variables 
This dataset consists of 3 classes: means, standard error (SE) and worst (i.e., mean of three largest values in each variable) 
and 32 variables: 
1. Radius: Distance from center to points on perimeter 
2. Texture: Standard deviation of gray-scale values 
3. Perimeter: Size of core tumor 
4. Area: Area of tumor 
5. Smoothness: Local variation in radius lengths 
6. Compactness: [(Mean of perimeter)^2/area] - 1.0 
7. Concavity: Depth of concave portions of contours in tumor 
8. Concave.points: No. of concave portions of the contour 
9. Symmetry: Tumor symmetry 
10. Fractal Dimension: Pattern changes depending on scale measured in

### Methodology
Employed two predictive models in R: logistic regression (baseline) and neural networks. We produced 4 logistic regression models and 4 neural network models testing the different classes: All variables, Mean Variables, Worst variables + SE variables. Additionally, we plotted a variable importance plot to identify which variable (out of the 32) was most effective in determining the malignancy or benignity of the tumor.
