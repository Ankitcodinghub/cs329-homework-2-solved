# cs329-homework-2-solved
**TO GET THIS SOLUTION VISIT:** [CS329 Homework#2 Solved](https://www.ankitcodinghub.com/product/cs329-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115920&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS329 Homework#2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (3 votes)    </div>
    </div>
&nbsp;

Question 1

(a) [True or False] If two sets of variables are jointly Gaussian, then the conditional distribution of one set conditioned on the other is again Gaussian. Similarly, the marginal distribution of either set is also Gaussian.

(b) We consider a partitioning of the components of x into three groups xa, xb, and xc, with a corresponding partitioning of the mean vector µ and of the covariance matrix ∑ in the form

  µa µ =  µb  ,. µc

Find an expression for the conditional distribution p(xa|xb) in which xc has been marginalized out.

1

Question 3

Show that the covariance matrix Σ that maximizes the log likelihood function is given by the sample covariance

1 ∑N (xn − µML)(xn − µML)T.

ΣML =

N n=1

Is the final result symmetric and positive definite (provided the sample covariance is nonsingular)?

Hints.

(a) To find the maximum likelihood solution for the covariance matrix of a multivariate Gaussian, we need to maximize the log likelihood function with respect to Σ.

The log likelihood function is given by

lnp(X|µ, Σ) = − NDln(2π) − Nln|Σ| − 1 ∑N (xn − µ)TΣ−1(xn − µ).

2 2 2 n=1

(b) The derivative of the inverse of a matrix can be expressed as

∂ −1) = −A−1∂AA−1

(A

∂x ∂x

We have the following properties

∂ ∂ ln|A| = (A−1)T.

Tr(A) = I,

∂A ∂A

Question 4

(a) Derive an expression for the sequential estimation of the variance of a univariate Gaussian distribution, by starting with the maximum likelihood expression

2 = 1 ∑N (xn − µ)2.

σML N n=1

Verify that substituting the expression for a Gaussian distribution into the Robbins-Monro sequential estimation formula gives a result of the same form, and hence obtain an expression for the corresponding coefficients aN.

(b) Derive an expression for the sequential estimation of the covariance of a multivariate Gaussian distribution, by starting with the maximum likelihood expression

1 ∑N (xn − µML)(xn − µML)T.

ΣML =

N n=1

Verify that substituting the expression for a Gaussian distribution into the Robbins-Monro sequential estimation formula gives a result of the same form, and hence obtain an expression for the corresponding coefficients aN.

Hints.

(a) Consider the result µML = N1 ∑nN=1 xn for the maximum likelihood estimator of the mean µML, which we will denote by µML(N) when it is based on N observations. If we dissect out the contribution from the final data point xN, we obtain

(N) 1 N 1 1 N−1 1 N − 1 (N−1) µML = N n∑=1 xn = NxN + N n∑=1 xn = NxN + N µML

1

.

N

(b) Robbins-Monro for maximum likelihood

.

Question 5

Consider a D-dimensional Gaussian random variable x with distribution N(x|µ, Σ) in which th4e covariance Σ is known and for which we wish to infer the mean µ from a set of observations X = {x1, x2, ……, xN}. Given a prior distribution p(µ) = N(µ|µ0, Σ0), find the corresponding posterior distribution p(µ|X).

Program Question

You should download the HW2_programQuestion.ipynb file first.

In this coding exercise, we will implement the K-nearest Neighbors (KNN) algorithm. You are provided with a Jupyter Notebook in which you will have to fill in the functions as instructed therein. Be sure to read the notebook thoroughly for the instructions and also comment your code appropriately.

This is a classification problem and we will use the Breast Cancer dataset. This dataset is included as part of sklearn. We have loaded the dataset for you in the Jupyter notebook. Please familiarize yourself with the dataset first.

Table1: Accuracy for the KNN classification problem on the validation set

A training data (X train) is provided which has several datapoints, and each datapoint is a p-dimensional vector (i.e., p features). You are also provided with separate validation (X val) and test sets (X test). Your task is to implement the K-nearest neighbors algorithm to determine the ideal combination of the value of K and the metric norm. For this you have to play with different combinations of metric norm and different values of K.

Compute the accuracy for the X val set for every combination of K and metric norm. Once, you have decided the ideal value of K and a relevant metric norm using the validation set, use those values to report the accuracy for the test set X test. You have to use the following values of K = 3, 5 and 7. The different metrics norms to be implemented are: L1, L2 and L-inf. Do not use any library to implement the norms.

(a) How could having a larger dataset influence the performance of KNN?

(b) Tabulate your results in Table 1 for the validation set as shown below and include that in your file.

(c) Finally, mention the best K and the norm combination you have settled upon from the above table and report the accuracy on the test set using that combination.

(d) The Autograder for your code submission will grade on the correctness of your implementation for the following functions as given in the Jupyter notebook: distanceFunc, computeDistancesNeighbors, Majority and KNN.
