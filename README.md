# Customer Segmentation & Prediction

This project is to achieve customer segmentation and predict the future customer categories of an online business store.

## 1 DataSet
The dataset is download from Kaggle website https://www.kaggle.com/carrie1/ecommerce-data . It consists of 8 columns and 541989 rows. 
The meaning of each column is described below:
-	InvoiceNo: Invoice number, represents each unique transaction. 
-	StockCode: Product code, represents each unique product. 
-	Description: Product name. 
-	Quantity: The quantities of each product per transaction. 
-	InvoiceDate: Invoice Date and time, represents the day and time when each transaction was generated. 
-	UnitPrice: Unit price. 
-	CustomerID: Customer number, represents each unique customer.
-	Country: Country name, represents the name of the country where each customer resides.

## 2 Process

<img width="800" alt="image" src="https://user-images.githubusercontent.com/74934323/102856277-2793a200-43f4-11eb-98b4-9abc74e68257.png">

Product segmentation and customer segmentation are achieved by using K-Means classification method. Features used for product segmentations are based on product names and price ranges. Features used for customer segmentations are customer’s purchase habits and based on the results from product segmentation. 

I applied 10 classification models (SVM (linear), SVM (Gussian), SVM (Polynomial), Decision Tree, LDA, Naive Bayes, Logistic Regression, AdaBoost, Random Forest, and KNN) to predict customer categories. 

## 3 Result

- Products are divided into 7 clusters, 
- and customers are divided into 11 groups.

- Linear SVM provides the best accuracy (98%) of predicting customer groups.

More details and results are presented in the Jupyter Notebook.
