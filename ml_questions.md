## Questions 
- [Linear Algebra](#Linear-Algebra)
- [Numerical Optimization](#Numerical-Optimization)
- [Basics of Probability and Information Theory](#Basics-of-Probability-and-Information-Theory)
- [ML Model Selection](#ML-Model-Selection)


### Linear Algebra
1. What are scalars, vectors, matrices, and tensors? 
2. What is Hadamard product of two matrices? Ans: entrywise product.
3. What is an inverse matrix and When does inverse of A exist? calculate inverse of a matrix?
4. What is the determinant of a square matrix? How is it calculated and What is the connection of determinant to eigenvalues? 
5. Discuss span and linear dependence
6. What is Ax = b? When does Ax =b has a unique solution? 
7. In Ax = b, what happens when A is fat or tall? 
8. What is a norm? What is L1, L2 and L infinity norm? 
9. What are the conditions a norm has to satisfy? 
10. Why is squared of L2 norm preferred in ML than just L2 norm? 
11. When L1 norm is preferred over L2 norm? 
12. Can the number of nonzero elements in a vector be defined as L0 norm? If no, why? 
13. What is Frobenius norm? Ans: Euclidean norm 
14. Why is multiplication by diagonal matrix computationally cheap? How is the  multiplication different for square vs. non-square diagonal matrix?
15. At what conditions does the inverse of a diagonal matrix exist?
16. What is eigen decomposition, eigenvectors and eigenvalues?
17. How to find Eigen values of a matrix? 
18. Write the Eigen decomposition formula for a matrix. If the matrix is real  symmetric, how will this change?
19. Is the Eigen decomposition guaranteed to be unique? If not, then how do we represent it.?
20. What are positive definite, negative definite, positive semi definite and negative semi definite matrices?
21. What is Singular Value Decomposition? Why do we use it? Why not just use ED? 
21. Given a matrix A, how will you calculate its Singular Value Decomposition? 
22. What are singular values, left singulars and right singulars?
23. What is the connection of Singular Value Decomposition of matrix A with functions of A? 
24. Why are singular values always non-negative? 
25. What is the Moore Penrose pseudo inverse and how to calculate it?
26. If we do Moore Penrose pseudo inverse on Ax = b, what solution is provided is A is fat? Moreover, what solution is provided if A is tall? 
27. Which matrices can be decomposed by ED and SVD? 
28. What is the trace of a matrix? 
29. How to write Frobenius norm of a matrix A in terms of trace? 
30. Why is trace off a multiplication of matrices invariant to cyclic permutations? 
31. What is the trace of a scalar? 
32. Write the Frobenius norm of a matrix in terms of trace? 

### Numerical Optimization
1. What is Overflow and underlflow?
2. How to tackle the problem of underflow or overflow for softmax function or log softmax function? 
3. What is poor conditioning? 
4. What is the condition number? 
5. What are grad, div and curl? 
6. What are critical or stationary points in multi-dimensions? 
7. Why should you do gradient descent when you want to minimise a function? 
8. What is a Jacobian matrix?
9. What is a Hessian matrix
### Basics of Probability and Information Theory 
1. Compare “Frequentist probability” vs. “Bayesian probability”? 
2. What is a random variable?
3. What is a probability distribution?
4. What is a probability mass function?
5. What is a probability density function?
6. What is a joint probability distribution?
7. What are the conditions for a function to be a probability mass function?
8.What are the conditions for a function to be a probability density function? marginal probability? Given the joint probability function, how will you calculate it?
9. State the Chain rule of conditional probabilities. 
10. What are the conditions for independence and conditional independence of  two random variables?
11. What are expectation, variance and covariance?
12. Compare covariance, correlation, causation.
13. What is the covariance for a vector of random variables? 
14. What is a Bernoulli distribution? Calculate the expectation and variance of a random variable that follows Bernoulli distribution?
15. What is a multinoulli distribution? 
16. What is a normal distribution? 
17. Why is the normal distribution a default choice for a prior over a set of real numbers? 
18. What is the central limit theorem?
19. What are exponential and Laplace distribution?
20. What are Dirac distribution and Empirical distribution?
21. What is Kullback-Leibler (KL) divergence?
22. Define cross-entropy Ans: Cross-entropy is commonly used to quantify the  difference between two probability distributions
23. What are structured probabilistic models or graphical models? 
24. What is population standard deviation and sample standard deviation? 
25. Why population s.d. has N degrees of freedom while sample s.d. has N-1  degrees of freedom? In other words, why 1/N inside root for pop. s.d. and 1/(N-1) inside root for sample s.d.? 
26. What is the formula for calculating the s.d. of the sample mean? 
27. Describe bias and variance with examples. 
28. What is Union bound and Hoeffding’s inequality? 
29. What is the bias-variance trade-off theorem? 
30. State the uniform convergence theorem and derive it.
31. What is sample complexity bound of uniform convergence theorem? 
32. What is error bound of uniform convergence theorem? 
32. From the bias-variance trade-off, can you derive the bound on training set size?
33. What is the VC dimension? 
34. What does the training set size depend on for a finite and infinite hypothesis set? Compare and contrast. 
35. What is the VC dimension for an n-dimensional linear classifier? 
36. How is the VC dimension of a SVM bounded although it is projected to an  infinite dimension? 21. Considering that Empirical Risk Minimization is a NP-hard problem, how does logistic regression and SVM loss work?

### ML Model Selection
1. How do you do a trade-off between bias and variance? 
2. Why is cross-validation required? 
3. Describe different cross-validation techniques.
4. What is hold-out cross validation? What are its advantages and disadvantages? 
5. What is k-fold cross validation? What are its advantages and disadvantages? 
6. What is leave-one-out cross validation? What are its advantages and disadvantages? 
7. Why is feature selection required? Describe some feature selection methods
8. What is forward feature selection method? What are its advantages and disadvantages? 
9. What is backward feature selection method? What are its advantages and disadvantages?
10. What is filter feature selection method and describe two of them?
11. What is mutual information and KL divergence? 
12. Describe KL divergence intuitively. Hint:  Curse of dimensionality 
13. What is local constancy or smoothness prior or regularization? 

### Support Vector Machine
1. How can the SVM optimisation function be derived from the logistic regression optimisation function? 
What is a large margin classifier?
2. Why SVM is an example of a large margin classifier? 
3. SVM being a large margin classifier, is it influenced by outliers? 
4. What is the role of C in SVM? 
5. In SVM, what is the angle between the decision boundary and theta? 
6. What is the mathematical intuition of a large margin classifier?
7. What is a kernel in SVM? Why do we use kernels in SVM? 
8. What is a similarity function in SVM? Why it is named so?
9. How are the landmarks initially chosen in an SVM? How many and where? 
10. Can we apply the kernel trick to logistic regression? Why is it not used in practice then?
11. What is the difference between logistic regression and SVM without a kernel? 
12. How does the SVM parameter C affect the bias/variance trade off? 
13. How does the SVM kernel parameter sigma2 affect the bias/variance trade  off?
14. Can any similarity function be used for SVM?
15. Logistic regression vs. SVMs: When to use which one? 

### Bayesian Machine Learning
1. What are the differences between “Bayesian” and “Freqentist” approach for Machine Learning?
2. Compare and contrast maximum likelihood and maximum a posteriori 
estimation.
3. How does Bayesian methods do automatic feature selection? 
4. What do you mean by Bayesian regularization? 
5. When will you use Bayesian methods instead of Frequentist methods? 

### Regularization
1. What is L1 regularization? 
2. What is L2 regularization? 
3. Compare L1 and L2 regularization.
4. Why does L1 regularization result in sparse models? 
5. What is dropout? 
6. How will you implement dropout during forward and backward pass? 

### Evaluation of Machine Learning systems 
1. What are accuracy, sensitivity, specificity, ROC? 
2. What are precision and recall? 
3. Describe t-test in the context of Machine Learning.
4. How does a ROC curve function?
5. Explain the difference between Type 1 and Type 2 errors?
6. What is meant by F1 score?

### Clustering 

1. Describe the k-means algorithm. 
2. What is distortion function? Is it convex or non-convex? 
3. Tell me about the convergence of the distortion function. 
4. Topic: EM algorithm 
5. What is the Gaussian Mixture Model? 
6. Describe the EM algorithm intuitively. 
7. What are the two steps of the EM algorithm 
8. Compare Gaussian Mixture Model and Gaussian Discriminant Analysis. 

### Dimensionality Reduction
1. Why do we need dimensionality reduction techniques? 
2. What do we need PCA and what does it do? 
3. What is the difference between logistic regression and PCA? 
4. What are the two pre-processing steps that should be applied before doing PCA?

### Basics of Natural Language Processing 

1. What is WORD2VEC? 
2. What is t-SNE? Why do we use PCA instead of t-SNE? 
3. What is sampled softmax? 
4. Why is it difficult to train a RNN with SGD? 
5. How do you tackle the problem of exploding gradients? 
6. What is the problem of vanishing gradients? 
7. How do you tackle the problem of vanishing gradients? 
8. Explain the memory cell of a LSTM. 
9. What type of regularization do one use in LSTM? 
10. What is Beam Search? 
11. How to automatically caption an image? 

### Sequence Modelling
1. Write the equation describing a dynamical system. Can you unfold it? Now, can you use this to describe a RNN? 
2. What determines the size of an unfolded graph? 
3. What are the advantages of an unfolded graph? 
4. What does the output of the hidden layer of a RNN at any arbitrary time t represent? 
5. Are the output of hidden layers of RNNs lossless? If not, why? 
6. RNNs are used for various tasks. From a RNNs point of view, what tasks are  more demanding than others? 
7. Discuss some examples of important design patterns of classical RNNs. 
8. Write the equations for a classical RNN where hidden layer has recurrence.  How would you define the loss in this case? What problems you might face while training it? 
9. What is back-propagation through time? 
10. Consider a RNN that has only output to hidden layer recurrence. What are its advantages or disadvantages compared to a RNN having only hidden to hidden recurrence? 
11. What is Teacher forcing? Compare and contrast with BPTT.
12. What is the disadvantage of using a strict teacher forcing technique? How to solve this?
13. Explain the vanishing/exploding gradient phenomenon for recurrent neural networks.
14. Why don’t we see the vanishing/exploding gradient phenomenon in feedforward networks?
15. What is the key difference in architecture of LSTMs/GRUs compared to traditional RNNs? 
16. What is the difference between LSTM and GRU?
17. Explain Gradient Clipping. 
18. Adam and RMSProp adjust the size of gradients based on previously seen gradients. Do they inherently perform gradient clipping? If no, why? 
19. Discuss RNNs in the context of Bayesian Machine Learning. 
20. Can we do Batch Normalization in RNNs? If not, what is the alternative? 
### Autoencoders 
1. What is an Autoencoder? What does it “auto-encode”? 
2. What were Autoencoders traditionally used for? Why there has been a resurgence of Autoencoders for generative modeling? 
3. What is recirculation? 
4. What loss functions are used for Autoencoders? 
5. What is a linear autoencoder? Can it be optimal (lowest training reconstruction error)? If yes, under what conditions? 
6. What is the difference between Autoencoders and PCA? 
7. What is the impact of the size of the hidden layer in Autoencoders? 
8. What is an undercomplete Autoencoder? Why is it typically used for? 
9. What is a linear Autoencoder? Discuss it’s equivalence with PCA. Which one is better in reconstruction? 
10. What problems might a nonlinear undercomplete Autoencoder face? 
11. What are overcomplete Autoencoders? What problems might they face? Does the scenario change for linear overcomplete autoencoders? 
12. Discuss the importance of regularization in the context of Autoencoders. 
13. Why does generative autoencoders not require regularization? 
14. What are sparse autoencoders? 
15. What is a denoising autoencoder? What are its advantages? How does it solve  the overcomplete problem? 
16. What is score matching? Discuss it’s connections to DAEs. 
17. Are there any connections between Autoencoders and RBMs? 
18. What is manifold learning? How are denoising and contractive autoencoders  equipped to do manifold learning?
19. What is a contractive autoencoder? Discuss its advantages. How does it solve the overcomplete problem? 
20. Why is a contractive autoencoder named so? 
21. What are the practical issues with CAEs? How to tackle them? 
22. What is a stacked autoencoder? What is a deep autoencoder? Compare and contrast. 
23. Compare the reconstruction quality of a deep autoencoder vs. PCA.
24. What is predictive sparse decomposition? 
25. Discuss some applications of Autoencoders. 

### Representation Learning 
1. What is representation learning? Why is it useful? 
2. What is the relation between Representation Learning and Deep Learning? 
3. What is one-shot and zero-shot learning (Google’s NMT)? Give examples. 
4. What trade offs does representation learning have to consider? 
5. What is greedy layer-wise unsupervised pretraining (GLUP)? Why greedy? Why layer-wise? Why unsupervised? Why pretraining?
6. What were/are the purposes of the above technique? (deep learning problem and initialization) 
7. Why does unsupervised pretraining work? 
8. When does unsupervised training work? Under which circumstances? 
9. Why might unsupervised pretraining act as a regularizer? 
10. What is the disadvantage of unsupervised pretraining compared to other forms of unsupervised learning? 
11. How do you control the regularizing effect of unsupervised pretraining? 
12. How to select the hyper-parameters of each stage of GLUP? 
### Monte Carlo Methods 
1. What are deterministic algorithms? 
2. What are Las vegas algorithms? 
3. What are deterministic approximate algorithms? 
4. What are Monte Carlo algorithms? 
