

### 1. Abstract and Introduction
+ Summary and background of the topic:[1]
> We are living in the century of big data. The effective use of data is becoming the key competency of almost any business in any industry. To make the right choices in the right time from data the concept of adaptive business intelligence (ABI) is created.  Apart from the original Business Intelligence (BI), ABI gives more attention to the facts that data are increasing and changing dramatically in every minute. This ABI system must be able to self-learn so that it can give real-time near-optimal the solutions or decisions reflecting this changes.

+ Why it is important (1)
> Random Forests (RF) is the extension of classification or regression trees, which means they are a combination of relatively simple models. By increasing the number the trees, the overfitting is effectively controlled or eliminated [1]. In modern ABI Systems, RF is becoming more and more important due to its significantly lower risk of overfitting and less variance, Which means a comparable accuracy.

+ How it has been studied or developed (1)
> In recent years, RF has been studied a lot and widely used in many area. In 2016, Random Forests was use to discover the relationship of Financial Record stored in different database [4]. In 2017, a novel random forests based class incremental learning method is proposed to recognize human activity automatically [2]. In 2018, a cascaded Random Forest is developed for hyper-spectral image classification [3]. This paper reviews the Random Forest techniques in ABI territory and Improve ground-level PM 2.5 concentration mapping using a random forests-based geostatistical approach



---

----------------------------------------------------------------------------------------
### 2. Concept and Theory[10]:
+ Good Description of the Concept and Theory (2)(In general)
> RF are usually referred as an ensemble of Decision Trees (TR). The image below illustrates an informal DT which is a classification tree (Classifier).
![image](https://cdn.edureka.co/blog/wp-content/uploads/2015/01/tree1.png)
> [6]
>
> For each node features are select to split the data into classes and decided which class this node belongs to. For example, in the above DT, nodes are firstly divided into two classes by the feature that whether it is a student or not. RF combine a set of small DT which created by embedding bootstrap random sampling and adopting Gini index as a feature selection standard [2].

+ How the Concept and Theory related to ABI (2)
> In ABI systems, data mining plays a very important role, which generates knowledges from information. There are two kinds of data mining, verification and discovery regarding to its mining goal. Verification data mining methods aim to the goodness of fitting hypothesis, while discover methods are used to identify patterns. These result patterns can help us either describing the underlying rules or predicting the values we are interested. The discover method for predicting are also mentioned as supervised learning or supervised model. It can be divided into Classification Model and Regression Model, these are the most popular kinds of model in Data Science. DT is the approach that can be adopted in both Classification as well as Regression [7].
> Apart from the traditional role of BI, ABI give more emphasis on building decisions automatically and continuously. There are a large number of studies on RF. Thanks to many state-of-the-art algorithm, the RF has become a efficient and effective learning method in online learning and incremental learning domains [2].


+ Advantages of the technique (2)
> In the ABI domains, RF has some key advantages as below:
> 1. RF is suitable for both Classification models regression Models.
> 1. Small training time: ABI systems are required to handle large data and or even data streams. RF's components DT are independent trees, they can be build simultaneously on different CPU cores. This dramatically increase the speed of decision generation [8].
> 2. High accuracy: DT is simple and strict-forward, however, a slightly change of the data can drastically affect the features selection and so affect the whole structure of tree. By subsampling N decision trees, the potential variance and bias are reduced and removed.
> 3. RF can give better result in Classification [1].

+ Disadvantages of the technique (2)
> RF also have several disadvantages, such as parallel training may not be applicable in a real scenario.
>


+ Limitations of the technique (2)
--------------------------------------------------------------------------------------
Good Description of the Concept and Theory (2)(In general)



--------------------------------------------------------------------------------------
### 3. Application[10]:
+ Example application related to ABI (2)  (specific)
> This section reviews the RF application in

+ Advantages of using the technique on the application (2)  （Based on the Application）
+ Disadvantages of using the technique on the application (2) （Based on the Application）
+ Detailed explanation on how to apply the technique on the specified application (2)
+ Other available techniques that can be used for the specified application (2)
--------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------
### 4. Future Development and Conclusion[3]:
+ The future of the technique (1)
+ The future of the technique in relation to ABI (1) (也许合适将来但不适合现在)
+ Conclusion (1)

### 5. nReferences[4]:
+ References and citations (1),
+ report structure (1),
+ English quality (1)
+ and word limit (1)



[1] Leo Breiman. 2001. Random Forests. Machine Learning 45, 1 (2001), 5–32. DOI: http://dx.doi.org/10.1023/A:1010933404324

[2] Hu, C., Chen, Y., Hu, L., & Peng, X. (2018). A novel random forests based class incremental learning method for activity recognition. Pattern Recognition, 78, 277-290.

[3] Szegedy, C., Liu, W., Jia, Y., Sermanet, P., Reed, S., Anguelov, D., ... & Rabinovich, A. (2015, June). Going deeper with convolutions. Cvpr.

[4] Kim, K., & Giles, C. L. (2016, June). Financial Entity Record Linkage with Random Forests. In Proceedings of the Second International Workshop on Data Science for Macro-Modeling (p. 13). ACM.

[5] Lior, R. (2014). Data mining with decision trees: theory and applications (Vol. 81). World scientific.
DATA MINING WITH DECISION TREES
In data mining, a decision tree is a predictive model which can be used to represent both classiﬁers and regression models. In operations research, on the other hand, decision trees refer to a hierarchical model of decisions and their consequences. The decision maker employs decision trees to identify the strategy most likely to reach her goal.

When a decision tree is used for classiﬁcation tasks, it is more appropriately referred to as a classiﬁcation tree. When it is used for regression tasks, it is called regression tree.


[6] tree image https://www.edureka.co/blog/decision-trees/


[7] Introduction to Decision Trees.

[8] Genuer, R., Poggi, J. M., Tuleau-Malot, C., & Villa-Vialaneix, N. (2017). Random forests for big data. Big Data Research, 9, 28-46.
