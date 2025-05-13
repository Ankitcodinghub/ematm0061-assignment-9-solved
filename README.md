# ematm0061-assignment-9-solved
**TO GET THIS SOLUTION VISIT:** [EMATM0061 Assignment 9 Solved](https://www.ankitcodinghub.com/product/ematm0061-assignment-9-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93039&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EMATM0061 Assignment 9 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
This document describes your ninth assignment for Statistical Computing and Empirical Methods (Unit EMATM0061) on the MSc in Data Science. Before starting the assignment it is recommended that you first watch video lectures 21, 22 and 23.

1 Basic concepts in classification

Write down your explanation of each of the following concepts. Give an example where appropriate.

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
<div class="column">
1. A classification rule 2. A learning algorithm 3. Training data

4. Feature vector

5. Label

6. Test error

7. Train error

8. The train test split 9. Linear classifier

The train test split

</div>
</div>
<div class="layoutArea">
<div class="column">
Suppose you want to build a classifier to predict whether a hawk belongs to either the “Sharp-shinned” or the “Cooper’s” species of hawks. The feature vector will be a four dimensional row vector containing the weight, and the lengths of the wing, the tail and the hallux. The labels will be binary – 1 if the hawk is “Sharp-shinned” and 0 if the hawk belongs to “Cooper’s” species.

Begin by loading the “Hawks” data frame from the “Stat2Data” library. Now extract a subset of the data called “hawks_total” with five columns – “Weight,”Wing“,”Hallux“,”Tail” and “Species”. The data frame should only include rows corresponding to hawks from either the “Sharp-shinned” or the “Cooper’s” species, and not the “Red-tailed” species. Convert the Species column to a binary variable with a 1 if the hawk belongs to the sharp- shinned species and 0 if the hawk belongs to the Cooper’s species. Finally remove any rows with missing values from one of the relevant columns.

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Now implement a train test split for your “hawks_total” data frame. You should use 60% of your data within your training data and 40% in your test data. You should create a data frame consisting of training data called “hawks_train” and a data frame consisting of test data called “hawks_test”. Display the number of rows in each data frame.

Next extract a data frame called “hawks_train_x” from your training data (from “hawks_train”) containing the feature vectors and no labels. In addition extract a vector called “hawks_train_y” consisting of labels from your training data. Similarly, create data frames called “hawks_test_x” and “hawks_test_y” corresponding to the feature vectors and labels within the test set, respectively.

Now let’s consider a very simple (and not very effective) classifier which entirely ignores the feature vectors. Instead the classifier simply predicts a single fixed value y ∈ {0, 1}. Hence, your classifier is of the form φy (x) ≡ y for all x ∈ R4. Begin by choosing a value yˆ ∈ {0,1} based on your training data – choose the value which minimises the training error.

Next compute the train and test error of φyˆ

What does this tell you about the relative sizes of your classes?

3 Linear discriminant analysis

Describe the probabilistic model that underpins linear discriminant analysis.

Train a linear discriminant analysis model to carry out the classification task described above. That is, to predict whether a hawk belongs to either the “Sharp-shinned” or the “Cooper’s” species of hawks, based on a four- dimensional feature vector containing the weight, and the lengths of the wing, the tail and the hallux.

Compute and report the train error and the test error.

As a challenging optional extra implement your own linear discriminant analysis model.

4 Logistic regression

Describe the probabilistic model which underpins logistic regression.

Recall that the sigmoid function S : R → (0, 1) is defined by S(z) = 1/(1 + e−z ). Generate the following plot which displays the sigmoid function:

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
1.00

0.75

0.50

0.25

0.00

</div>
</div>
<div class="layoutArea">
<div class="column">
−10 −5 0 5 10

z

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Now train a logistic regression model to predict whether a hawk belongs to either the “Sharp-shinned” or the “Cooper’s” species of hawks, based on a four-dimensional feature vector containing the weight, and the lengths of the wing, the tail and the hallux.

Compute and report both the training error and the test error.

As an optional extra consider the following formula for the log-likelihood of the weights w ∈ Rd and bias w0 ∈ R,

given data D = ((X1,Y1),··· ,(Xn,Yn)):

logl(w,w0)=􏰁logS􏰅(2Yi −1)·(wXi⊤ +w0)􏰆

Demonstrate the following formulas for the derivatives:

∂ 􏰁n

(2Yi −1)S􏰅(1−2Yi)·(wXi⊤ +w0)􏰆Xi, (2Yi −1)S􏰅(1−2Yi)·(wXi⊤ +w0)􏰆.

</div>
</div>
<div class="layoutArea">
<div class="column">
∂w logl(w,w0) =

∂ 􏰁n

</div>
</div>
<div class="layoutArea">
<div class="column">
∂w0 logl(w,w0) =

Explain the role the above formula has in training a logistic regression model.

</div>
</div>
<div class="layoutArea">
<div class="column">
You can learn more about the the glmnet approach to logistic regression here.

</div>
</div>
<div class="layoutArea">
<div class="column">
i=1

</div>
</div>
<div class="layoutArea">
<div class="column">
i=1

</div>
</div>
<div class="layoutArea">
<div class="column">
n i=1

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
</div>
