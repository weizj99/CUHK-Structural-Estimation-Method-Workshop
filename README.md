# CUHK Structural Estimation Method Workshop
## Introduction
This workshop aims at learning the structural estimation methods, especially its implementation. Focus will be put on combing the data with models. Two parts will be included, the first is about methodologies of structural estimation, and the second is about its application in fields like labor, trade, industrial organization, etc.

## Schedule (Updating)
### Week 1 (Sep 18th) Introduction to Structural Estimation, Sufficient Statistics and Calibration
#### Related Reading
#### Taylor's Introduction to Structural Estimation in Corporate Finance
[Taylor's introduction](http://finance-faculty.wharton.upenn.edu/luket/wp-content/uploads/sites/10/2017/04/Structural_estimation_2017.pdf)
#### Chetty's Sufficient Statistics Slides
[Chetty's Sufficient Statistics](https://rajchetty.com/wp-content/uploads/2021/04/slides_areview_suffstat.pdf)
#### Calibration
[Sargent's Calibration](https://tomasrm.github.io/teaching/quantmacro/data_macro.pdf)

[Bayesian Calibration](https://www.asc.ohio-state.edu/statistics/comp_exp/jour.club/kennedy01.pdfv)

[Johari's Calibration](https://www.studocu.com/en-us/document/stanford-university/game-theory-with-engineering-applications/lecture-notes-on-calibration/746869)



### Week 2 (Sep 25th) MLE, EM Algorithm, Bootstrap
#### Related Reading
#### Mikusheva's Bootstrap lecture note
[Mikusheva's Bootstrap Note](https://ocw.mit.edu/courses/14-384-time-series-analysis-fall-2013/2fdf997bca65d6ed82ba7a94f6cdc970_MIT14_384F13_lec9.pdf)
#### Xu's Bootstrap slides
[Xu's Bootstrap Note](https://homepage.ntu.edu.tw/~ckuan/pdf/2014fall/Lecture-Bootstrap-%E6%96%B0%E7%89%88141211-%E8%A8%B1%E8%82%B2%E9%80%B2.pdf)

### Week 3 (Oct 16th) GMM and SMM
#### Related Reading
#### Jalali's SMM note
[Jalali's note](https://scholar.harvard.edu/files/jalali/files/msm_book_chapter.pdf)

#### Quant Econ's SMM note
[Quant Econ note](https://notes.quantecon.org/submission/5b3db2ceb9eab00015b89f93)

#### Braun's GMM and SMM note
[Braun's SMM](https://christine-braun.github.io/Lecture_Notes/WarwickLabor/GMM.pdf)
[Braun's GMM](https://christine-braun.github.io/Lecture_Notes/WarwickLabor/SMM.pdf)

This workshop scheduled to be weekly, lasting for 10 or 11 weeks. For both parts, participants make presentation in turns. Each meeting will be less than 2 hours, the day and time is TBD. 

### Week 4 (Oct 30th): Deep Learning as Surrogates
#### Related Reading
[JFV's Deep Learning Materials](https://www.sas.upenn.edu/~jesusfv/teaching.html)
[Deep HAM](https://github.com/frankhan91/DeepHAM)



Since this workshop has wide positive externality (say, benefit future CUHK or more Econ students) and has no grading like a lecture, participants need to make some commitment  before they decide to participate, i.e., absent no more than 3 times in total. We will manage this Github repository together by uploading codes, slides, useful meterials, and arrange them by topics. 
## Part I: Methodologies and Theories
### Introduction
### Estimation Methods
#### Calibration
#### Maximum Likelihood Estimation (MLE)
#### General Moment Method (GMM)
#### Simulated Moment Method (SMM)
#### Non-parametric Methods
#### (TBD) Structural Estimation with Deep Learning (DL) and Generate Adversarial Networks (GAN)

### Statistical Computation Methods
#### Expectation Maximization (EM) Algorithm
#### Markov Chain Monte Carlo (MCMC)


## Part II: Topics and Practices(tentative)
For this part's presentation, 

### 1. use **no more than** 30 mins to make audiences know:  
  -the key idea of models,   
  -the theoretical predictions,    
  -the estimation targets.    

### 2. Use 45-60 mins for presenting details of estimation, including methodologies, data and implementation, which includes
 -how you implement them, 
 -what difficulties you met during the process, and 
 -what you think is the key technical points.   
 -differences between your results and the paper (if any), and why.   

For many papers, replication packages can be found easily, but we recommend do it again on your own, rewrite the code under the guidance and rearrange them. Also, reading the online appendix helps form a deeper understanding of techniques.  

The main goal of the estimation part is to get familiar with the implementation of structural estimation methods, so please **replicate one paper's result (key result is enough, and if there're many countries or regions, one country is enough; some technical points can be discussed further in workshop) and upload the codes as well as slides before each workshop**, so that the coding details can be learned together. 

Group work with no more than three members and presenting own papers using structural estimation (if any) are encouraged. 

### 3. Use about 15 mins for discussion. 
Another goal of this workshop is to practice presentation skills. Participants are from different fields, so it's important to convey the key idea of the model to someone even not familiar with that stream of literature. Although the technical part, on the other hand, is more common to participants, it's also challenging to organize and describe the process clearly to audiencies. This requires the presenter to know clearly about the paper.

Besides the presenter, audiences' critical, constructing comment also plays an important role. We hope to make informative discussion about the paper, especially ideas from different fields.

Below are some potential topics and related papers. These are flexible depending on participants, as long as they use structural estimation methods.

### Topic 1: International Trade
>Antras P, Fort T C, Tintelnot F. The margins of global sourcing: Theory and evidence from us firms[J]. American Economic Review, 2017, 107(9): 2514-2564.


### Topic 2: Spatial Economics


### Topic 3: Industrial Organization (or, in some sense, firm dynamics)
>Barwick P J, Cao S, Li S. Local protectionism, market structure, and social welfare: China’s automobile market[J]. American Economic Journal: Economic Policy, 2021, 13(4): 112-151.


The second one is quite challenging technically:
>Chen Z, Liu Z, Suárez Serrato J C, et al. Notching R&D investment with corporate income tax cuts in China[J]. American Economic Review, 2021, 111(7): 2065-2100.    
>König M, Storesletten K, Song Z, et al. From imitation to innovation: Where is all that Chinese R&D going?[J]. Econometrica, 2022, 90(4): 1615-1654.


### Topic 4: Structural Labor
> Ji Y. Job search under debt: Aggregate implications of student loans[J]. Journal of Monetary Economics, 2021, 117: 741-759.

### Topic 5: Tax Policy

### Topic 6: Networks Economics
> Acemoglu D, García-Jimeno C, Robinson J A. State capacity and economic development: A network approach[J]. American economic review, 2015, 105(8): 2364-2409.





## Some General Reference Links
### Richard Evan's Structural Estimation (in Python)
[Rick's Github Repositories](https://github.com/rickecon/StructEst_W20)
### Christine Braun's Topics in Labor Economics, Lecture 5-9 (in Matlab)
[Christine's Github Repositories](https://christine-braun.github.io/teaching-labor.html)
### Taber's Structural Estimation Theory Notes
[Taber's notes](https://users.ssc.wisc.edu/~ctaber/718/struct.pdf)
### Train's Discrete Choice Methods with Simulation
[Train's book](https://eml.berkeley.edu/books/train1201.pdf)
