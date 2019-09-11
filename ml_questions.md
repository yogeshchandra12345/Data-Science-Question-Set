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

