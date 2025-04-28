# cs420-homework-2-solved
**TO GET THIS SOLUTION VISIT:** [CS420 Homework 2 Solved](https://www.ankitcodinghub.com/product/cs420-solved-4/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117914&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS420 Homework 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
&nbsp;

Submission to:

Please submit your homework in pdf format to the CS420 folder in the following FTP. File name should be like this: 0123456789_tushikui_hw1.pdf.

ftp://public.sjtu.edu.cn username: xingzhihao

password: public

1 (10 points) PCA algorithm

Give at least two algorithms that could take data set X = {x1,…,xN}, xt ∈ Rn×1,∀t as input, and output the first principal component w. Specify the computational details of the algorithms, and discuss the advantages or limitations of the algorithms.

2 (10 points) Factor Analysis (FA)

Calculate the Bayesian posterior p(y|x) of the Factor Analysis model x = Ay + µ + e, with p(x|y) = G(x|Ay + µ,Σe), p(y) = G(y|0,Σy), where G(z|µ,Σ) denotes Gaussian distribution density with mean µ and covariance matrix Σ.

3 (10 points) Independent Component Analysis (ICA)

Explain why maximizing non-Gaussianity could be used as a principle for ICA estimation.

4 (50 points) Dimensionality Reduction by FA

Consider the following Factor Analysis (FA) model,

x = Ay + µ + e, (1) p(x|y) = G(x|Ay + µ,σ2I), (2) p(y) = G(y|0,I), (3)

where the observed variable x ∈ Rn, the latent variable y ∈ Rm, and G(z|µ,Σ) denotes Gaussian distribution density with mean µ and covariance matrix Σ. Write a report on experimental comparisons on model selection performance by BIC, AIC on selecting the number of latent factors, i.e., dim(y) = m.

∗ tushikui@sjtu.edu.cn

Specifically, you need to randomly generate datasets based on FA, by varying some setting values, e.g., sample size N, dimensionality n and m, noise level σ2, and so on. For example, set N = 100,n = 10,m = 3,σ2 = 0.1,µ = 0, and assign values for A ∈ Rn×m. The generation process is as follows:

(1) Randomly sample a yt from Gaussian density G(y|0,I), with dim(y) = m = 3;

(2) Randomly sample a noise vector et from Gaussian density G(e|0,σ2I), with σ2 = 0.1, et ∈ Rn;

(3) Get xt = Ayt + µ + et.

Collect all the xt as the dataset .

The two-stage model selection process for BIC, AIC is as follows:

Stage 1: Run EM algorithm on each dataset X for m = 1,…,M, and calculate the log-likelihood value ln[p(X|Θˆm)], where Θˆm is the maximum likelihood estimate for parameters; Stage 2: Select the optimal m∗ by

m∗ = argmaxm=1,…,MJ(m), (4) JAIC(m) = ln[p(X|Θˆk)] − dm (5)

(6)

The following codes might be useful.

Python: https://scikit-learn.org/stable/modules/generated/sklearn.

decomposition.FactorAnalysis.html#sklearn.decomposition.FactorAnalysis

5 (20 points) Spectral clustering

Use experiments to demonstrate that when spectral clustering works well, when it would fail. Summarize your results.

The following codes might be helpful.

Python: https://scikit-learn.org/stable/modules/generated/sklearn.cluster. SpectralClustering.html

2
